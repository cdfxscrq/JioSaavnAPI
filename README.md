## JioSaavn API [Unofficial]

#### JioSaavn API written in Python using Flask  

 ---
###### **NOTE:** You don't need to have JioSaavn link of the song in order to fetch the song details, you can directly search songs by their name. Fetching Songs/Albums/Playlists from URL is also supported in this API.  

 ---
  
#### Features:
##### Currently the API can get the following details for a specific song in JSON format:
- **Song Name**
- **Singer Name**
- **Album Name**
- **Album URL**
- **Duration of Song**
- **Song Thumbnail URL (Max Resolution)**
- **Song Language**
- **Download Link**
- **Release Year**
- **Album Art Link (Max Resolution)**
- **Song Title**
- .... and much more!

```json
{
    "album": "BIBA",
    "album_url": "https://www.jiosaavn.com/album/biba/98G3uzIs2qQ_",
    "autoplay": "false",
    "duration": "175",
    "e_songid": "ICERW0MFfQs",
    "has_rbt": "false",
    "image_url": "https://c.saavncdn.com/987/BIBA-English-2019-20190201201359-500x500.jpg",
    "label": "Joytime Collective",
    "label_url": "/label/joytime-collective-albums/",
    "language": "hindi",
    "liked": "false",
    "map": "Marshmello^~^/artist/marshmello-songs/Eevs5FiVgus_^~^Pritam Chakraborty^~^/artist/pritam-chakraborty-songs/OaFg9HPZgq8_^~^Shirley Setia^~^/artist/shirley-setia-songs/9qGdjoPJ1vM_^~^Pardeep Singh Sran^~^/artist/pardeep-singh-sran-songs/NIfiZRCrYQA_^~^Dev Negi^~^/artist/dev-negi-songs/NpCqdI4dD5U_",
    "music": "",
    "origin": "search",
    "origin_val": "biba",
    "page": 1,
    "pass_album_ctx": "true",
    "perma_url": "https://www.jiosaavn.com/song/biba/ICERW0MFfQs",
    "publish_to_fb": true,
    "singers": "Marshmello, Pritam Chakraborty, Shirley Setia, Pardeep Singh Sran, Dev Negi",
    "songid": "PIzj75J8",
    "starred": "false",
    "starring": "",
    "streaming_source": null,
    "tiny_url": "https://www.jiosaavn.com/song/biba/ICERW0MFfQs",
    "title": "BIBA",
    "twitter_url": "http://twitter.com/share?url=https%3A%2F%2Fwww.jiosaavn.com%2Fsong%2Fbiba%2FICERW0MFfQs&text=%23NowPlaying+%22BIBA%22+%40jiosaavn+%23OurSoundtrack&related=jiosaavn",
    "url": "http://h.saavncdn.com/987/cd902d048c13e5ce6ca84cc409746a5d.mp3",
    "year": "2019"
  }
```

#### Installation:

Clone this repository using
```sh
$ git clone https://github.com/cdfxscrq/JioSaavnAPI
```
Enter the directory and install all the requirements using
```sh
$ pip3 install -r requirements.txt
```
Run the app using
```sh
$ python3 app.py
```
Navigate to 127.0.0.1:5000 to see the Homepage

#### Usage:
```sh
http://127.0.0.1:5000/result/?query=<insert-jiosaavn-link-or-query-here>
```
**Example:** Navigate to http://127.0.0.1:5000/result/?query=https://www.jiosaavn.com/song/tum-hi-aana-from-marjaavaan/NCw-YiNJYms to get a json response of song data in return.

### You can fork the repo and deploy on VPS or deploy it on Heroku :)  
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/cyberboysumanjay/JioSaavnAPI/tree/master)



#### Star the Repo in case you liked it :)

# © [Sumanjay](https://cyberboysumanjay.github.io)
