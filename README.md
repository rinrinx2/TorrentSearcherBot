[![TorrentSearcherBot Banner](https://raw.githubusercontent.com/bondeabhijeet/TorrentSearcherBot/main/torrentsearcher.png)](https://github.com/bondeabhijeet/TorrentSearcherBot)


# What does this repo mean?
 _A simple telegram bot written in python to search torrents_

<details>
  <summary> <b>Supported Services </b></summary>

  + YTS.AM | YTS.AG | YTS.MX | YTS.LT
  + 1337x.to | 1337x.st | 1337x.ws | 1337x.eu | 1337x.se | 1337x.is | 1337x.gd
  + <i>Working on more...</i>
</details>

# Want to deploy this bot yourself?
- Recommended operating system<br>
   ```Linux distribution```
   
- Cloning this repo
  ```
  git clone https://github.com/bondeabhijeet/TorrentSearcherBot
  ```
- Navigating inside the repo
  ```
  cd TorrentSearcherBot
  ```
  
- Installing python
  ```
  sudo apt-get install python3
  ```


- Installing requirements
  ```
  bash requirements.sh
  ```
  _By running this command, all the requirements will be installed on the system (including dependencies). *Details of the installation will be printed on the         screen_
- ## config.json file
     append all the details in this file according to the fields.
   - **API_KEY** : The token you recieve from [@BotFather](https://telegram.me/BotFather) to access the HTTP API.
   - **COMMANDS** : All the commands on which the bot will work on.
     + **Yts** : The command to search yts websites [Default = yts].
     + **Help** : The command to get the help message [Default = help].
     + **o1337x** : The command to search 1337x websites [Default = search1337x].
   - **NoOf1337xResults** : The number of results to be displayed from 1337x website.
# Deploying the bot
 ```
 python3 main.py
 ```
 _As simple as that_
