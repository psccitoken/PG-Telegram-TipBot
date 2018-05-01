# Telegram iDealCash Tipbot - 

#### Forked from Telegram Reddcoin Tipbot.
####  https://github.com/samgos/reddbot-telegram

## Dependencies 

*  `apt-get install python3`
*  `apt-get install python3-pip`
*  `pip3 install beautifulsoup4`
*  `pip3 install python-telegram-bot --upgrade`

* In order to run the tip-bot effectively, a Bitcoin-core based client is needed. For this idealcashd is used

## Setup

* Install the deps
* Install idealcashd to /usr/bin/idealcashd 
* Run and exit program
### NOTE if not using idealcashd compiled from the experimental branch of the github, you will have to provide the idealcash.conf file and place it manually in the ~/.idealcash/ directory.
* edit the idealcash.conf file located at ~/.idealcash/idealcash.conf to contain the following:

* `staking=0`
* `enableaccounts=1`
### Staking cannot be enabled while running for the tipbot.

* Run idealcashd and let it start syncing


* Setup a bot with the user @BotFather through PM on Telegram, after going through a setup you will be given a bot token. Edit the command.py file and replace the parameter 'BOT_TOKEN' with the one you just recieved. 

*  Run the script 
`python3 command.py`

*  Initiate the bot by inviting it to a chat or via PM, some commands are `/balance` , `/price` , `/help` and to find out the format related to tip others and withdrawal of funds use `/commands`.

### Setting up the bot as so still leaves the wallet unencrypted, so please go to extra measures to provide extra security. Make sure to have SSH encryption on whatever device/droplet you run it on. 

*  Please fork the code, happy tipping! 



