# coinmover_bybit

## prerequisites:  
sudo apt install python3-pip  
pip install pybit  

Bybit: Create an APIkey 

## installation:  
Copy coinmover_bybit.py and config.ini to your server.  
edit config.ini , fill in:  
api key  
api secret  
percentage_move = percentage of profits to be moved to spot  
sleeptime = after how many minutes you want to run this again  
discord_webhook = your webhook if you want to use discord notifications 

When all configuration is done, you can run the script: python3 coinmover_bybit.py  
If your want to run the script in the backgroud while logged off, you can use 'screen'. within screen, start the script, then ctrl-a d to disconnect the screen. You can always return to this with 'screen -r'.

Not done yet: 
maximum margin in use
