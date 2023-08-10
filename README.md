<br/>

<div align="center" style="margin: 30px;">
	<img src="https://raw.githubusercontent.com/ronaldstoner/LLMLabyrinth/master/img/logo.png" align="center" /> 
	<br />
	<h2>LLMLabyrinth</h2>
	<h3>⚔️ An AI generated text-based adventure game⚔️</h3>
</div>

<div align="center">

[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org/)
[![GitHub tag](https://img.shields.io/github/tag/ronaldstoner/LLMLabyrinth?include_prereleases=&sort=semver)](https://github.com/ronaldstoner/LLMLabyrinth/releases/) [![issues - badge-generator](https://img.shields.io/github/issues/ronaldstoner/LLMLabyrinth)](https://github.com/ronaldstoner/LLMLabyrinth)

</div>

<br/>

# Let's Game With AI
LLMLabyrinth is a call back to the old school text based console adventure games with a twist. Descriptions are generated by a local GPT model in order to add dynamic elements to an exciting adventure. 

Find and combine the 3 items to win the game!

# Screenshot
<img src="https://raw.githubusercontent.com/ronaldstoner/LLMLabyrinth/master/img/game.png" align="center" /> 

# Features
- Directional walking (omg!)
- AI LLM generated room descriptions
- Room themes
- Inventory
- Item combinations
- Win state
 	
# Install

1. Clone this repo
2. Set up a virtual enviroment
	`python3 -m venv env`
3. Activate the virtual environment
	`source env/bin/activate`
4. Install the requirements
	`pip3 install -r requirements.txt` - install python dependencies
5.  Download the LLM model and place it in the `models` directory
	- LLM: default to [ggml-gpt4all-j-v1.3-groovy.bin](https://gpt4all.io/models/ggml-gpt4all-j-v1.3-groovy.bin). If you prefer a different GPT4All-J compatible model, just download it in the applicable folder

6. Run the game
	`python3 main.py`

# Commands
| Command | Action |
|--|--|
| n | north |
| e | east |
| s | south |
| w | west |
| i | check inventory |
| combine | combine items |
| q | quit |
