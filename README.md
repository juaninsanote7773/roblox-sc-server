# ro-sc-share
dependencies (python):
* Pillow (pip install pillow)
* pyautogui (pip install pyautogui)
* requests (pip install requests)

# how to setup this server:
* create a render.com server
* fork this repository
* use your repository

replace the commands with:
* install command: npm install
* start command: npm start

# sender_logic_py
This should be executed from the secondary computer or VM,
sends frames and recieves inputs from roblox.

# roblox_logic_lua
These are the roblox place scripts. change the url in
ServerScriptService.Script to your render.com server
link.

# IMPORTANT THINGS TO NOTE
If you're trying to modify the image quality,
the max payload for render.com servers is 100kb, which is pretty limited.
