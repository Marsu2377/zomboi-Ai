# Zomboi

This is an edit from the original Python Script uploaded by JohnnyPtn. Optimized to handle perk logs and chat logs better to not crash chat reporting during high loads, such as when the skill recovery journal and bikini tools SE restore pods are used, which flood the bot causing chat reporting to error out and no longer report in the discord. 

This bot is seeminly more stable now for high population zomboid servers. This is used heavily for "The Doobie Brothers Community Server". Handling about 25-45 players on average. ACSII and other non-latin characters are also now handled better and will be replaced with question marks (?).

Unzip Zomboi-AI folder and install python 3.8.0 as recommended by johnnyptn Follow the readme that is included in the Zomboi-AI.zip folder, as that should be the original instructions for getting everything setup. Install all required dependenies, This package includes the new C# code as well if you would like to assit in translating the functionality of the python script to C#. Personally i dont like it as much as it doesn't seem as feature rich yet and I only need this bot to report player counts, joins/disconnects, skills, chat and admin logs.

Extra dependencies recommended by ChatGPT to handle data base log reads and chat character decoding.
pip install aiosqlite

&

pip install charset-normalizer
