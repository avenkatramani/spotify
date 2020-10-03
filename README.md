# Spotify Playlist Creator (spotplay)

Welcome to spotify playlist creator, your destination for generating random playlists for upto 100 songs. :D

## Installation

* Python 3
* Install dependencies

```
pip install -r requirements.txt
```

## Usage

* Set API credentials in the background - `source credentials.sh`

### Getting a list of all genres available

```
./spotplay.py --genres
```

### Generating a playlist

This might prompt you to login to your spotify account

```
./spotplay.py --seed-genres pop sleep sad --count 100 --name "My Awesome Playlist" 
```