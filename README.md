# CCTV
Close-Circuit Telegram Vision revolutionizes location tracking with its open-source design and Telegram API integration. Offering precise tracking within 50-100 meters, users can monitor others in real-time for logistics or safety, redefining how we navigate our surroundings

Usage example:
--------------
1. Installation 
```
git clone https://github.com/IvanGlinkin/CCTV.git
cd CCTV
pip install -r requirements.txt
```

2. Registering Telegram creds
```
visit https://my.telegram.org/auth web-site
input your phone number
input the confirmation/login code
follow "API development tools" link
register the application
get App's api_id, api_hash, title and name
```

3. Settings<br>
Upon first launch script will create `config.yaml` file and request all needed settings.<br>
This settings can be manually changed later:
```
api_config:
  api_hash: ***
  api_id: 00000000
  phone: "+123456789000"
location:
  lat: 51.51404
  lon: -0.15063
  meters: 1200
misc:
  speed_kmh: 50
  timesleep: 30
```

4. Launch
```
python3 start.py
```

5. Read the data by opening ./reports-html/_combined_data.html

Help message:
-------------
```

 ██████╗██╗      ██████╗ ███████╗███████╗     ██████╗██╗██████╗  ██████╗██╗   ██╗██╗████████╗                      
██╔════╝██║     ██╔═══██╗██╔════╝██╔════╝    ██╔════╝██║██╔══██╗██╔════╝██║   ██║██║╚══██╔══╝                      
██║     ██║     ██║   ██║███████╗█████╗█████╗██║     ██║██████╔╝██║     ██║   ██║██║   ██║                         
██║     ██║     ██║   ██║╚════██║██╔══╝╚════╝██║     ██║██╔══██╗██║     ██║   ██║██║   ██║                         
╚██████╗███████╗╚██████╔╝███████║███████╗    ╚██████╗██║██║  ██║╚██████╗╚██████╔╝██║   ██║                         
 ╚═════╝╚══════╝ ╚═════╝ ╚══════╝╚══════╝     ╚═════╝╚═╝╚═╝  ╚═╝ ╚═════╝ ╚═════╝ ╚═╝   ╚═╝                         
                                                                                                                   
████████╗███████╗██╗     ███████╗ ██████╗ ██████╗  █████╗ ███╗   ███╗    ██╗   ██╗██╗███████╗██╗ ██████╗ ███╗   ██╗
╚══██╔══╝██╔════╝██║     ██╔════╝██╔════╝ ██╔══██╗██╔══██╗████╗ ████║    ██║   ██║██║██╔════╝██║██╔═══██╗████╗  ██║
   ██║   █████╗  ██║     █████╗  ██║  ███╗██████╔╝███████║██╔████╔██║    ██║   ██║██║███████╗██║██║   ██║██╔██╗ ██║
   ██║   ██╔══╝  ██║     ██╔══╝  ██║   ██║██╔══██╗██╔══██║██║╚██╔╝██║    ╚██╗ ██╔╝██║╚════██║██║██║   ██║██║╚██╗██║
   ██║   ███████╗███████╗███████╗╚██████╔╝██║  ██║██║  ██║██║ ╚═╝ ██║     ╚████╔╝ ██║███████║██║╚██████╔╝██║ ╚████║
   ╚═╝   ╚══════╝╚══════╝╚══════╝ ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝     ╚═╝      ╚═══╝  ╚═╝╚══════╝╚═╝ ╚═════╝ ╚═╝  ╚═══╝

usage: start.py [-h] [-lat LATITUDE] [-long LONGITUDE] [-m METERS] [-t TIMESLEEP] [-s SPEED_KMH] [-tn TELEGRAM_NAME] [-ti TELEGRAM_API_ID]
                [-th TELEGRAM_API_HASH]

Custom settings for script launch

optional arguments:
  -h, --help            show this help message and exit
  -lat LATITUDE, --latitude LATITUDE
                        Latitude setting
  -long LONGITUDE, --longitude LONGITUDE
                        Longitude setting
  -m METERS, --meters METERS
                        Meters setting
  -t TIMESLEEP, --timesleep TIMESLEEP
                        Timesleep setting
  -s SPEED_KMH, --speed_kmh SPEED_KMH
                        Speed setting
  -tn TELEGRAM_NAME, --telegram_name TELEGRAM_NAME
                        Telegram session name
  -ti TELEGRAM_API_ID, --telegram_api_id TELEGRAM_API_ID
                        Telegram API ID
  -th TELEGRAM_API_HASH, --telegram_api_hash TELEGRAM_API_HASH
                        Telegram API hash
```

Media mentions:
---------------
[EN] https://www.linkedin.com/feed/update/urn:li:activity:7191073927949938688/

[EN] https://www.404media.co/this-tool-shows-some-telegram-users-approximate-physical-location/

[EN] https://www.newsbytesapp.com/news/science/locations-of-telegram-users-are-now-easy-to-find/story

[EN] https://www.transforminggov.ca/taxonomy/1kd79926usd10/

[EN] https://sector035.nl/articles/2024-18

[EN] https://twitter.com/404mediaco/status/1787880234294951949

[EN] https://twitter.com/hack_git/status/1786271191847539117

[EN] https://www.youtube.com/watch?v=AV6E-bUYVSs

[RU] https://dzen.ru/b/ZjMjQrQIlkH8ypnH

[RU] https://tgstat.ru/channel/@infosec_globe/2642

[RU] https://botiprobiva.org/cctv-api-dlya-otslezhivaniya-mestopolozheniya-v-telegram/

[RU] https://istories.media/news/2024/05/07/vipusknik-universiteta-minoboroni-rf-razrabotal-instrument-kotorii-pozvolyaet-uznat-primernie-adresa-polzovatelei-telegrama/

[RU] https://holod.media/2024/05/08/rossiiskii-khaker-razrabotal/

[RU] https://vk.com/wall-225594201_181?ysclid=lvxhixzl7o951682138



Video example:
--------------
[![Close-Curcuit Telegram Vision PoC](https://raw.githubusercontent.com/IvanGlinkin/media_support/main/CCTV_youtube.png)](https://www.youtube.com/watch?v=y9jEiZS5pAc "Close-Curcuit Telegram Vision PoC")
Banned by YouTube

https://github.com/IvanGlinkin/media_support/raw/main/CCTV_Github.mp4

Screenshots:
------------
![](https://raw.githubusercontent.com/IvanGlinkin/media_support/main/CCTV1.png)
![](https://raw.githubusercontent.com/IvanGlinkin/media_support/main/CCTV2.png)
![](https://raw.githubusercontent.com/IvanGlinkin/media_support/main/CCTV4.png)
