# Real-Time-Data-Collection-Dota-2

## General Description
This repository is created as a part of the research of "Machine learning models for DOTA 2 outcomes prediction."

## How to reproduce results?
1. Firstly, you need to unzip the game state integration (GSI) file and move it inside the game's configuration files. For example in Linux, it should be like this <i>/home/test/.steam/debian−installation/steamapps/common/Dota2beta/game/Dota/cf g/gamestateintegration</i>. Based on your system please locate the folder.
2. Secondly, open the Python code in Jupyter Notebook and run. 
3. Thirdly, launch the game, and once you come to "ALL PICK" hero selection process of the game, the Python file starts to run and generate real-time data files in the Python located directory.
4. Finally, once the game ends, terminate the code using stop kernel in Jupyter Notebook.
