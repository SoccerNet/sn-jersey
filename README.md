# SoccerNet Jersey Number Recognition

Repository containing all necessary codes to get started on the SoccerNet Jersey Number Recognition challenge. 

In this year's SoccerNet Jersey Number challenge, participants are given short video tracklets of soccer players and are asked to identify the jersey number of the player. This task can be useful for consumer applications as it helps to build systems that can accurately identify and recognize players in real-time during a soccer game. This information can be used to create interactive experiences for fans, such as player statistics, player tracking, and in-game analysis. Additionally, this technology can also be used in broadcast production to add player labels and enhance the viewing experience. By encouraging research on player recognition, the SoccerNet Jersey Number challenge contributes to the development of more engaging and informative consumer applications for soccer fans.

More information coming soon

## Description of the task

Given short video tracklets of soccer players that can be a few hundreds frames long, the participants are asked to identify the jersey number of each player (Players with non visible jersey numbers are annotated with the "-1" value). The task is challenging because of the low quality of the thumbnails (low resolution, high motion blur) and because the jersey numbers might be visible on a very small subset of the whole tracklet.

## How to download the dataset

The SoccerNet Jersey Number dataset is composed of 2853 tracklets of players extracted from the SoccerNet tracking videos. The challenge set is composed of 1211 separate players tracklets with hidden annotations.

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
