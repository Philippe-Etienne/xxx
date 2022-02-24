

# Games on  [Play Store](https://play.google.com/store/apps/developer?id=Philippe+etienne)

# Games
```
Create interesting games by pure python.
You can star this repository to keep track of the project if it's helpful for you, thank you for your support.
```


# Statement
```
Most of the game materals(including music, fonts and pictures) in this repository are collected from the web, copyright belongs to the original author.
This repository is created just for learning python(Commercial prohibition).
```


# Support List
|   ID      |  English Name             |  Chinese Name           |   Core Code                                                |   Introduction                                               |
|   :----:  |  :----:                   |  :----:                 |   :----:                                                   |   :----:                                                     |
|   Game1   |  bunnybadger              |  兔子和獾(射击游戏)     |   [click](./cpgames/modules/core/bunnybadger)              |   [click](https://mp.weixin.qq.com/s/_-AChGldQzdwXN-ljcCMFQ) |
|   Game2   |  voicecontrolpikachu      |  仿八分音符的声控小游戏 |   [click](./cpgames/modules/core/voicecontrolpikachu)      |   [click](https://mp.weixin.qq.com/s/NmK5fAMoOHahOf6OvV6XFA) | 
|   Game3   |  puzzlepieces             |  拼图小游戏             |   [click](./cpgames/modules/core/puzzlepieces)             |   [click](https://mp.weixin.qq.com/s/tcmrbNCptka2ZTfEs-W_Lg) |
|   Game4   |  ski                      |  滑雪游戏               |   [click](./cpgames/modules/core/ski)                      |   [click](https://mp.weixin.qq.com/s/2MVTEa4ut9TOAgBOOWEUSg) |
|   Game5   |  tankwar                  |  经典坦克大战小游戏     |   [click](./cpgames/modules/core/tankwar)                  |   [click](https://mp.weixin.qq.com/s/1xXULpT36P7LTO5HDbjptg) |
                                              |


# Install

#### Whl install
```sh
wget https://github.com/CharlesPikachu/Games/releases/download/v0.1.0/cpgames-0.1.0-py3-none-any.whl
pip install cpgames-0.1.0-py3-none-any.whl
```

#### Pip install
```
run "pip install cpgames"
```

#### Source code install
```sh
(1) Offline
Step1: git clone https://github.com/CharlesPikachu/Games.git
Step2: cd Games -> run "python setup.py install"
(2) Online
run "pip install git+https://github.com/CharlesPikachu/Games.git@master"
```


# Quick Start
```python
import random
from cpgames import cpgames

game_client = cpgames.CPGames()
all_supports = game_client.getallsupported()
game_client.execute(random.choice(list(all_supports.values())))
```


# Screenshot
![img](./docs/screenshot.gif)


# Projects in Charles_pikachu
- [Games](https://github.com/CharlesPikachu/Games): Create interesting games by pure python.
- [DecryptLogin](https://github.com/CharlesPikachu/DecryptLogin): APIs for loginning some websites by using requests.
- [Musicdl](https://github.com/CharlesPikachu/musicdl): A lightweight music downloader written by pure python.
- [Videodl](https://github.com/CharlesPikachu/videodl): A lightweight video downloader written by pure python.
- [Pytools](https://github.com/CharlesPikachu/pytools): Some useful tools written by pure python.
- [PikachuWeChat](https://github.com/CharlesPikachu/pikachuwechat): Play WeChat with itchat-uos.
- [Pydrawing](https://github.com/CharlesPikachu/pydrawing): Beautify your image or video.
- [ImageCompressor](https://github.com/CharlesPikachu/imagecompressor): Image compressors written by pure python.
- [FreeProxy](https://github.com/CharlesPikachu/freeproxy): Collecting free proxies from internet.
- [Paperdl](https://github.com/CharlesPikachu/paperdl): Search and download paper from specific websites.


# Citation
If you use this project in your research, please cite this project.
```
@misc{games2020,
    author = {Zhenchao Jin},
    title = {Games: Create interesting games by pure python},
    year = {2020},
    publisher = {GitHub},
    journal = {GitHub repository},
    howpublished = {\url{https://github.com/CharlesPikachu/Games}},
}
```


# More

#### WeChat Official Accounts
*Charles_pikachu*  
![img](./docs/pikachu.jpg)
