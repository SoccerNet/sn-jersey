# SoccerNet Jersey Number Recognition

Repository containing all necessary codes to get started on the SoccerNet Jersey Number Recognition challenge. 
More information coming soon


## How to download the dataset

A [SoccerNet pip package](https://pypi.org/project/SoccerNet/) to easily download the data and the annotations is available. 

To install the pip package simply run:

<code>pip install SoccerNet</code>

Then use the API to downlaod the data of interest:

```
from SoccerNet.Downloader import SoccerNetDownloader as SNdl
mySNdl = SNdl(LocalDirectory="path/to/SoccerNet")
mySNdl.downloadDataTask(task="jersey-2023", split=["train","test","challenge"])
```

## Our other Challenges

Check out our other challenges related to SoccerNet!
- [Action Spotting](https://github.com/SoccerNet/sn-spotting)
- [Replay Grounding](https://github.com/SoccerNet/sn-grounding)
- [Calibration](https://github.com/SoccerNet/sn-calibration)
- [Re-Identification](https://github.com/SoccerNet/sn-reid)
- [Tracking](https://github.com/SoccerNet/sn-tracking)
- [Dense Video Captioning](https://github.com/SoccerNet/sn-caption)

## Citation

Please cite our work if you use our dataset:
```bibtex
@article{Cioppa2022Scaling,
  title={Scaling up SoccerNet with multi-view spatial localization and re-identification},
  author={Anthony Cioppa and Adrien Deli{\`e}ge and Silvio Giancola and Bernard Ghanem and Marc Van Droogenbroeck},
  journal={Scientific Data},
  year={2022},
  month={June},
  volume={9}
}
```
