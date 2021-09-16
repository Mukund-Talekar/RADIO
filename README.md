## LOVELY RADIO
SUPPORTS 500 GROUPS NO NEED OF BOT 😉






## Requirements

- Telegram API_ID , 
API_HASH and
SESSION_NAME




## HEROKU
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/TEAM-LOVELY/RADIO)

### Get YouTube live stream link 
#### install youtube_dl
```pip install youtube_dl```

```
import youtube_dl
ydl_opts = {}
url = input("enter your url:- ")
with youtube_dl.YoutubeDL(ydl_opts) as ydl:
	meta = ydl.extract_info(url, download=False)
	formats = meta.get('formats', [meta])
	for f in formats:
		print(f['url'])
```
```If you have a https:// address change it to http:// otherwise you get an "HTTP error 403 forbidden```

## Credits 
- <a href="https://t.me/tgcallslib">pytgcalls</a>
- <a href="https://t.me/pyrogram">pyrogram</a>



