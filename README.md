It's a free version of solana urban bot, that will help you to mint, but not guaranteed.

Easy setup which uses ChromeDriver to open up a new chrome instance and mint the nft you are looking for quicker than a human. This bot does not guarantee you will get your NFT, this bot simply goes faster than humans to mint and automates everything since you do not have to click yourself.
You can launch multiple instances of the bot to bypass minting limit / wallet
I appreciate any support, here is my solana wallet: HeUaPBnuWdG4xbCoksn6h7PxwEvCrpkeeUW5XAgrkMNB

Support
 Window

 Mac (Intel + m1)

 Linux (Not verified)

 MagicEden.io

 MonkeLabs.io

This bot uses ChromeDriver so on mac there is a possiblity that you will have to allow the software to run in your privacy settings. Check mac folder for more info.

The chrome window will appear WITHOUT loading the images, this is to ensure the fastest loading.

Tutorial
Clone the repository / Download zip file

git clone https://github.com/WhiteListArtist/urban-minting-bot.git

OR

Download Zip File

Be sure you have installed Python correctly, here is a link to download

Open command prompt

Install all python module

pip install selenium requests webdriver-manager

and

python -m pip install git+https://github.com/np-8/webdriver_manager.git

(currently using this since the last webdriver manager main isn't working)

Replace Phantom Passphrase and password in config.json

launchpadLink --> Launchpad link on magic eden

seedPhrase --> your phantom wallet passphrase (Careful do not share this key)

password --> A password for your wallet

Open CMD and go to directory

cd /path/to/directory/magiceden-mint-bot/windows

Run the python file

windows : python main.py

mac : python3 main.py



