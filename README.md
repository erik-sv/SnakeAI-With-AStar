# SnakeAI using A* Pathfinding
![SnakeAI](https://github.com/wylieglover/SnakeAI-With-AStar/assets/70774631/1b3ba6e4-01ef-439f-b6d1-42c9f17b1742)

# Local Development Setup
Before starting, these components must be installed (requirements.txt has them, look below for instructions)

- python
- pip

Contents of requirements.txt:

- pygame
- torch
- numpy
- matplotlib (for plotting training results)

Start by cloning this repository into a local folder/directory:
```sh
git clone https://github.com/wylieglover/SnakeAI-with-AStar.git
```

Navigate into the repository's folder and run this command to download the necessary components:
```sh
pip install -r requirements.txt
```

Then finally run the ```agent.py``` file with the command below to begin training!
```sh
python3 agent.py
```

There are optional command line arguments, neither are required:

- ```--logs``` (change the logging level in the terminal. Default none, only shows completed game stats in console)
    - ```debug``` shows A* engine path logs and Agent moves. Spams the console somewhat.
    - ```all``` shows all logs, including when the model doesn't make a move but A* does. This spams the console but contains all data.
- ```--speed``` (change the speed at which the game plays, similar to framerate)
    - ```50``` for low
    - ```75``` for medium (Default)
    - ```200``` for fast
    - ```500``` to heat your home