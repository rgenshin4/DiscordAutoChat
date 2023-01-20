# bot-discord-auto-random-chat
<h3 align="center">Auto Sends Random Message Every Time</h3>

# TUTORIAL FOR WINDOWS
  1. download and install python
  2. download or git clone https://github.com/rgenshin4/DiscordAutoChat
  3. input your token discord in Config.json file
  4. open install.bat
  5. open start.bat
  6. input delay chat message in seconds
  7. write in discord chat `!ikuzo <number of messages>`
  
# TUTORIAL FOR ANDROID
  1. dowload and install Termux
  2. input your token discord in Config.json file (in folder bot-discord-auto-random-chat)
  3. input this command in termux:<br>
     <q>apt update && apt upgrade</q><br>
     <q>termux-setup-storage</q><br>
     <q>git clone https://github.com/mityoe860/bot-discord-auto-random-chat</q><br>
     <q>pkg install python3</q><br>
     <q>pip install -U discord==1.7.3</q><br>
     <q>pip install -U discord.py==1.7.3</q><br>
     cd to your bot-discord-auto-random-chat folder</br>
     <q>pip install -r requirements.txt</q><br>
     <q>python3 main.py</q><br>
  4. input delay chat message in seconds
  5. write in discord chat `!ikuzo <number of messages>`
    
# NOTE
  1. You can edit or add messages in line 46 file main.py
  2. Auto delete messages only delete when above your message is your own message. if you don't want like it, you can delete "Limit=1" in line 87 file main.py (it will make your messages instantly delete)
  
<h2 align="center">!!! DWYOR !!!</h2>
#thanksMITO
