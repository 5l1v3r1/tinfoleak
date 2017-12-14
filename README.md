tinfoleak
=========

 Get detailed information about a Twitter user activity
 
 Now, you can view screenshots and download tinfoleak from here:
 http://vicenteaguileradiaz.com/tools/

### Installation

Install python dependencies:

`pip install -r requirements.txt`

On Ubuntu/Debian systems, you have to install `pyexiv2` using:

`sudo apt-get install python-pyexiv2`

### Usage

```
  _______ _        __      _            _    
 |__   __(_)      / _|    | |          | |   
    | |   _ _ __ | |_ ___ | | ___  __ _| | __
    | |  | | '_ \|  _/ _ \| |/ _ \/ _` | |/ /
    | |  | | | | | || (_) | |  __/ (_| |   < 
    |_|  |_|_| |_|_| \___/|_|\___|\__,_|_|\_\

	Tinfoleak v2.1 [SHA2017 Edition] - "Get intelligence from Twitter"
	Vicente Aguilera Diaz. @VAguileraDiaz
	Internet Security Auditors
	08/07/2017

usage: tinfoleak.py [-h] [-v] [-t TWEETS_NUMBER] [-i] [-s]
                    [-f FOLLOWERS_NUMBER] [-r FRIENDS_NUMBER]
                    [-w WORDS_NUMBER] [--conv] [--sdate SDATE] [--edate EDATE]
                    [--stime STIME] [--etime ETIME] [--hashtags] [--mentions]
                    [--likes LIKES_NUMBER] [--meta] [--media [D]] [--social]
                    [--geo FILE] [--top NUMBER] [--find TEXT]
                    [--search [LATLONKM]] [-o OUTPUT] [-u USERNAME]

Tinfoleak

optional arguments:
  -h, --help            show this help message and exit
  -v, --version         show program's version number and exit
  -t TWEETS_NUMBER, --tweets TWEETS_NUMBER
                        analyze TWEETS_NUMBER tweets (default: 200)
  -i, --info            get general information about the user
  -s, --sources         get the client applications used to publish every
                        tweet
  -f FOLLOWERS_NUMBER, --followers FOLLOWERS_NUMBER
                        get the last FOLLOWERS_NUMBER followers for the user
  -r FRIENDS_NUMBER, --friends FRIENDS_NUMBER
                        get the last FRIENDS_NUMBER friends for the user
  -w WORDS_NUMBER, --words WORDS_NUMBER
                        get the top WORDS_NUMBER most used words
  --conv                get user conversations
  --sdate SDATE         filter the results with SDATE as start date (format:
                        yyyy-mm-dd)
  --edate EDATE         filter the results with EDATE as end date (format:
                        yyyy-mm-dd)
  --stime STIME         filter the results with STIME as start time (format:
                        HH:MM:SS)
  --etime ETIME         filter the results with ETIME as end time (format:
                        HH:MM:SS)
  --hashtags            get information about hashtags
  --mentions            get information about user mentions
  --likes LIKES_NUMBER  get information about the last LIKES_NUMBER favorites
                        tweets
  --meta                get metadata information from user images
  --media [D]           [no value]: show user images and videos, [D]: download
                        user images to "username" directory
  --social              identify user identities in social networks
  --geo FILE            get geolocation information and generates an output
                        FILE (KML format)
  --top NUMBER          get top NUMBER locations visited by the user
  --find TEXT           search tweets based on filters. [+]word : include
                        "word", [-]word : not include "word", [+r] :
                        retweeted, [-r] : not retweeted, [+m] : multimedia,
                        [-m] : not multimedia
  --search [LATLONKM]   search tweets in global timeline or filtering by
                        LATitude, LONgitude, and KMs (distance)
  -o OUTPUT, --output OUTPUT
                        generates a OUTPUT file (HTML format)
  -u USERNAME, --user USERNAME
                        Twitter user name
```
