# RollercoinBot

Python Bot, can play some [minigames](https://rollercoin.com/?r=kpod94x1).

## Games
- 2048
- CoinFlip
- CoinClick (Firefox)
- Flappy Rocket

## Installation
- Download or clone the git
- Python 3.6+ needs to be installed (python 3.9 currently not supported!)
- Install all the requirements ```pip install -r requirements.txt```
  - On windows you may need Microsoft Visual Studio with some packages installed (if numpy installation fails, try to read the error message and look what is missing)
- Open up rollercoin.com/game/choose_game on your main monitor
- Start the script ```python bot.py```
- Linux requires installing the requirements and running the bot as sudo because of pyautogui
- Also Linux required executing ```xhost +``` before starting the script to prevent another internal error

If you find any other bug during execution, open up an issue here on github.

Use it at your own risk.
