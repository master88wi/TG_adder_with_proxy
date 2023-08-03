# Features: 
- Multiple accounts support
- Asynchronous scraper and adder 
- Proxy support (now u can bind proxy to a specific account)
- Filtering users by last online time and first name (more filters in later releases)
- Random time sleep from 2 to 10 seconds
- Mtproxy support only for old version - secret must be a hex-string representing 16 bytes (may be fixed later)
- Free tool

Still in development, soon more features will be added 

# Getting api_id and api_hash
* Go to http://my.telegram.org and log in.
* Click on API development tools and fill the required fields.
* copy "api_id" n "api_hash" after clicking create app 

# Installation and usage on Windows
- Install python at least version 3.10 [how to install](https://www.digitalocean.com/community/tutorials/install-python-windows-10)
- Download the archive directly and unzip it or u can install git and download archive using git clone [install git](https://github.com/git-guides/install-git) (https://github.com/git-guides/install-git)

## Usage via terminal 
- Open terminal - click win + R and then type cmd.exe
- ```pip3 install telethon```
- ```git clone https://github.com/evilbream/TG_adder_with_proxy```
- ```cd Tg_adder_with_proxy``` change directory to downloaded folder.
- ```exclude_list.txt``` - it'll open exclude_list.txt. If u want to filter users by first name run it and add words. Users with these words in first name will be excluded
- ```python account_manager.py```  -  To run account manager. Now u can add account(s) w or without proxy, delete account(s), change proxy for the specific account(s), view all accounts and test the ability to log in to account(s)
- ```python main_parser.py``` - To scrape members from the group
- ```python main_adder.py``` - Add scraped members to ur group

## Usage via PyCharm
- Download and install PyCharm community edition [jetbrains.com](https://www.jetbrains.com/pycharm/download/?section=windows)
- Open downloaded folder Tg_adder_with_proxy with PyCharm
- Run in PyCharm account_manager.py
- Add account(s) to database with or without proxy
- Add data to exclude.txt if you want to filter users by first name 
- Run in  PyCharm main_parser.py to scrape members 
- Run  in  PyCharm main_adder.py to add members

### Errors n questions
If u have any questions or errors fill free to text me

* Telegram - [malevolentkid](https://t.me//malevolentkid)
