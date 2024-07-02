# SoccerNet Jersey Number Recognition

Repository containing all necessary codes to get started on the SoccerNet Jersey Number Recognition challenge. 

In this year's SoccerNet Jersey Number challenge, participants are given short video tracklets of soccer players and are asked to identify the jersey number of the player. This task can be useful for consumer applications as it helps to build systems that can accurately identify and recognize players in real-time during a soccer game. This information can be used to create interactive experiences for fans, such as player statistics, player tracking, and in-game analysis. Additionally, this technology can also be used in broadcast production to add player labels and enhance the viewing experience. By encouraging research on player recognition, the SoccerNet Jersey Number challenge contributes to the development of more engaging and informative consumer applications for soccer fans.

### 2023 Challenge Leaderboard

<p><table class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th style = "background-color: #FFFFFF;font-family: Century Gothic, sans-serif;font-size: medium;color: #305496;text-align: left;border-bottom: 2px solid #305496;padding: 0px 20px 0px 0px;width: auto">Team</th>
      <th style = "background-color: #FFFFFF;font-family: Century Gothic, sans-serif;font-size: medium;color: #305496;text-align: left;border-bottom: 2px solid #305496;padding: 0px 20px 0px 0px;width: auto">Accuracy</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style = "background-color: #D9E1F2;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">ZZPM</td>
      <td style = "background-color: #D9E1F2;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">92.85</td>
    </tr>
    <tr>
      <td style = "background-color: white; color: black;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">UniBw Munich - VIS</td>
      <td style = "background-color: white; color: black;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">90.95</td>
    </tr>
    <tr>
      <td style = "background-color: #D9E1F2;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">zzzzz</td>
      <td style = "background-color: #D9E1F2;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">88.08</td>
    </tr>
    <tr>
      <td style = "background-color: white; color: black;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">Mike Azatov</td>
      <td style = "background-color: white; color: black;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">82.05</td>
    </tr>
    <tr>
      <td style = "background-color: #D9E1F2;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">MT-IOT</td>
      <td style = "background-color: #D9E1F2;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">81.7</td>
    </tr>
    <tr>
      <td style = "background-color: white; color: black;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">justplay</td>
      <td style = "background-color: white; color: black;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">77.77</td>
    </tr>
    <tr>
      <td style = "background-color: #D9E1F2;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">AIBrain Global Team</td>
      <td style = "background-color: #D9E1F2;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">75.18</td>
    </tr>
    <tr>
      <td style = "background-color: white; color: black;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">SARG UWaterloo</td>
      <td style = "background-color: white; color: black;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">73.77</td>
    </tr>
    <tr>
      <td style = "background-color: #D9E1F2;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">Kalisteo</td>
      <td style = "background-color: #D9E1F2;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">58.35</td>
    </tr>
    <tr>
      <td style = "background-color: white; color: black;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">FindNum</td>
      <td style = "background-color: white; color: black;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">54.91</td>
    </tr>
    <tr>
      <td style = "background-color: #D9E1F2;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">jn</td>
      <td style = "background-color: #D9E1F2;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">47.55</td>
    </tr>
    <tr>
      <td style = "background-color: white; color: black;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">Surya</td>
      <td style = "background-color: white; color: black;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">28.4</td>
    </tr>
    <tr>
      <td style = "background-color: #D9E1F2;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">tony506672558</td>
      <td style = "background-color: #D9E1F2;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">20.06</td>
    </tr>
    <tr>
      <td style = "background-color: white; color: black;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">lfriend</td>
      <td style = "background-color: white; color: black;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">5.68</td>
    </tr>
    <tr>
      <td style = "background-color: #D9E1F2;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">zhq</td>
      <td style = "background-color: #D9E1F2;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">4.07</td>
    </tr>
    <tr>
      <td style = "background-color: white; color: black;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">Basline (Random)</td>
      <td style = "background-color: white; color: black;font-family: Century Gothic, sans-serif;font-size: medium;text-align: left;padding: 0px 20px 0px 0px;width: auto">3.93</td>
    </tr>
  </tbody>
</table></p>

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

## Dataset format
Dataset is split into three folders: train/test/challenge. Each folder contains a json grountruth file (except the challenge set) and an "image" folder.
In the image folder, there is one folder per player with a list of thumbnails: each folder is named after the player ID.
The groundtruth json file is a one level python dictionnary with player ID (a String) as keys and player jersey number (an Integer) as value.
A value of "-1" is used to indicate the jersey number is not visible.


## Submission format
The file to submit for the challenge/test set on [EvalAI](https://eval.ai/web/challenges/challenge-page/1952/overview) must have the same format as the ground truth file: a dictionnary mapping player ID (a String) to player jersey number (an Integer). 
A value of "-1" must be used to indicate the jersey number is not visible.


## Our other Challenges

Check out our other challenges related to SoccerNet!
- [Action Spotting](https://github.com/SoccerNet/sn-spotting)
- [Replay Grounding](https://github.com/SoccerNet/sn-grounding)
- [Calibration](https://github.com/SoccerNet/sn-calibration)
- [Re-Identification](https://github.com/SoccerNet/sn-reid)
- [Tracking](https://github.com/SoccerNet/sn-tracking)
- [Dense Video Captioning](https://github.com/SoccerNet/sn-caption)

## Citation
The SoccerNet Jersey Number Recognition dataset introduced in this repository is derived from the [sn-gamestate](https://github.com/SoccerNet/sn-gamestate) and [sn-tracking](https://github.com/SoccerNet/sn-tracking) datasets. 
Four key authors contributed to building the sn-jersey benchmark: Vladimir Somers, Amir Mansourian, Anthony Cioppa, Silvio Giancola (no specific order).
If you use this dataset, please make sure to cite all authors to acknowledge their work.
Here is a list of relevant work to cite:

```bibtex
@inproceedings{Somers2024SoccerNetGameState,
        title = {{SoccerNet} Game State Reconstruction: End-to-End Athlete Tracking and Identification on a Minimap},
        author = {Somers, Vladimir and Joos, Victor and Giancola, Silvio and Cioppa, Anthony and Ghasemzadeh, Seyed Abolfazl and Magera, Floriane and Standaert, Baptiste and Mansourian, Amir Mohammad and Zhou, Xin and Kasaei, Shohreh and Ghanem, Bernard and Alahi, Alexandre and Van Droogenbroeck, Marc and De Vleeschouwer, Christophe},
        booktitle = cvsports,
        month = Jun,
        year = {2024},
        address = city-seattle,
        keywords = {}
}
```

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

```bibtex
@article{Cioppa2023SoccerNetChallenge-arxiv,
	title = {{SoccerNet} 2023 Challenges Results},
	author = {Cioppa, Anthony and Giancola, Silvio and Somers, Vladimir and Magera, Floriane and Zhou, Xin and Mkhallati, Hassan and Deli{\`e}ge, Adrien and Held, Jan and Hinojosa, Carlos and Mansourian, Amir M. and Miralles, Pierre and Barnich, Olivier and De Vleeschouwer, Christophe and Alahi, Alexandre and Ghanem, Bernard and Van Droogenbroeck, Marc and Kamal, Abdullah and Maglo, Adrien and Clap{\'e}s, Albert and Abdelaziz, Amr and Xarles, Artur and Orcesi, Astrid and Scott, Atom and Liu, Bin and Lim, Byoungkwon and Chen, Chen and Deuser, Fabian and Yan, Feng and Yu, Fufu and Shitrit, Gal and Wang, Guanshuo and Choi, Gyusik and Kim, Hankyul and Guo, Hao and Fahrudin, Hasby and Koguchi, Hidenari and Ard{\"o}, H\r{a}kan and Salah, Ibrahim and Yerushalmy, Ido and Muhammad, Iftikar and Uchida, Ikuma and Be'ery, Ishay and Rabarisoa, Jaonary and Lee, Jeongae and Fu, Jiajun and Yin, Jianqin and Xu, Jinghang and Nang, Jongho and Denize, Julien and Li, Junjie and Zhang, Junpei and Kim, Juntae and Synowiec, Kamil and Kobayashi, Kenji and Zhang, Kexin and Habel, Konrad and Nakajima, Kota and Jiao, Licheng and Ma, Lin and Wang, Lizhi and Wang, Luping and Li, Menglong and Zhou, Mengying and Nasr, Mohamed and Abdelwahed, Mohamed and Liashuha, Mykola and Falaleev, Nikolay and Oswald, Norbert and Jia, Qiong and Pham, Quoc-Cuong and Song, Ran and H{\'e}rault, Romain and Peng, Rui and Chen, Ruilong and Liu, Ruixuan and Baikulov, Ruslan and Fukushima, Ryuto and Escalera, Sergio and Lee, Seungcheon and Chen, Shimin and Ding, Shouhong and Someya, Taiga and Moeslund, Thomas B. and Li, Tianjiao and Shen, Wei and Zhang, Wei and Li, Wei and Dai, Wei and Luo, Weixin and Zhao, Wending and Zhang, Wenjie and Yang, Xinquan and Ma, Yanbiao and Joo, Yeeun and Zeng, Yingsen and Gan, Yiyang and Zhu, Yongqiang and Zhong, Yujie and Ruan, Zheng and Li, Zhiheng and Huangi, Zhijian and Meng, Ziyu},
	journal = arxiv,
	volume = {abs/2309.06006},
	year = {2023},
	publisher = {arXiv},
	eprint = {2309.06006},
	keywords = {SoccerNet, Challenge},
	eprinttype = {arXiv},
	doi = {10.48550/arXiv.2309.06006},
	url = {https://doi.org/10.48550/arXiv.2309.06006}
}
```

```bibtex
@inproceedings{cioppa2022soccernet,
  title={SoccerNet-Tracking: Multiple Object Tracking Dataset and Benchmark in Soccer Videos},
  author={Cioppa, Anthony and Giancola, Silvio and Deliege, Adrien and Kang, Le and Zhou, Xin and Cheng, Zhiyu and Ghanem, Bernard and Van Droogenbroeck, Marc},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={3491--3502},
  year={2022}
}
```
