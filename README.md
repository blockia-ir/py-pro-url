# URL Uploader Pro Bot

Telegram Bot using pyrogram libray

Create By Hossein Pira





- [Run To Heroku](https://heroku.com/deploy?template=https://github.com/blockia-ir/py-pro-url)

- [Telegram](https://t.me/h3dev)

- [installation video in heroku](http://orabel.ir/url-pro-uploader.mp4)
- [installation video in vps](https://orabel.ir/install-in-vps.mp4)


# install on Locally/VPS
```
git clone https://github.com/blockia-ir/py-pro-url

pip3 install -U -r requirements.txt

Edit config.py with variables.

python bot.py
```

<h3>How to edit config.py</h3>

<p> Here is sample edited config.py for deploy to Locally/VPS. copy and past and edit with your variables</p>

<pre>
class Config(object):

    # get a token from @BotFather
    BOT_TOKEN = "5568340867:AAGuPzlgwqgHtgqmdL7yt12PRLrXFjt98Zg"
    
    # Get these values from my.telegram.org
    API_ID = 12345
    API_HASH = "uPzlgwqgHtgqmdL7yt12PRLrXFj"
    
    # No need to change
    DOWNLOAD_LOCATION = "./DOWNLOADS"
    ADMIN_LOCATION = "./ADOWNLOADS"
    CREDENTIALS_LOCATION = "./CREDENTIALS"
    ADL_BOT_RQ = {}
    CHUNK_SIZE = 128
    TG_MAX_FILE_SIZE = 4194304000
    HTTP_PROXY = ""
    PROCESS_MAX_TIMEOUT = 3700
    DEF_WATER_MARK_FILE = ""
    
    # TG Ids
    LOG_CHANNEL = -1001798969594
    OWNER_ID = 1288398723
    
    # bot username without @
    BOT_USERNAME = "AdvanceUrlUploaderBot"
    
    # auth users
    AUTH_USERS = [1288398722, 1288398724, 1288398725]
    AUTH_USERS.append(OWNER_ID)
</pre>

# bot texts :
fot edit bot texts , you need to click the fork option in the project .
and go to Uploader/script.py and edit texts .

And then open the link below to run it in your repository.
Attention, put the address of your repository instead of the xxx sign.
<pre>
https://heroku.com/deploy?template=xxx
</pre>
