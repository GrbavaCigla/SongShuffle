# SongShuffle
Youtube songs for terminal geeks!
## Requirements
_**[Python 3.X.X](https://www.python.org/downloads/release/python-373/)**_ (Tested on [Python3.6.6](https://www.python.org/downloads/release/python-366/) and [Python3.7.0](https://www.python.org/downloads/release/python-370/))<br />
_**[VLC Player](https://www.videolan.org/vlc/download-windows.html)**_
## Installation
```
pip3 install pafy
pip3 install youtube-dl
pip3 install beautifulsoup4
pip3 install python-vlc
pip3 install tqdm
pip3 install PrettyTable
```
or
```
pip3 install -r requirements.txt
```
## Usage
`--help` or `-h` prints out help page.<br />
`--sync` or `-s` finds best Song ID for YouTube.<br />
`--echo` or `-e` prints out all songs in database.<br />
`--remove` removes song, takes 1 argument (ID).<br />
`--add` adds song, takes 1 argument (Read formatting for more!).<br />
`--ignoredb` or `-i` ignores database file.<br />
`--play` or `-p` plays song, takes 1 argument (Read formatting for more!).<br />
`--shuffle` or `-8` plays songs in shuffling order.<br />
Add `--byud` next to `--play` to play song by it's id.<br />
Add `--video` or `-v` to play Song's music spot.<br/>
Add `--ytautoplay` or `-y` next to `--play` to turn on youtube autoplay feature. **_NEW_**
## Formatting
- Spaces are represented by `.`(dot).<br />
- Split title and artist with `-`(dash).<br />
Example:<br />
`./main.py --add Song.With.Spaces-Some.Artist`
## TODO
- Replace VLC with PyGame for portability
- ~~Integrate YouTube autoplay feature~~-
- Add Songshell for control
- Add URL saving to database
- Finish my custom argparser
## Changelog
- Added `--byid`
- Added `--video`
- Added `--ytautoplay`
- Argument system reworked
## Known Issues
- Sometimes error 403: Access Denied of URL
- Sometimes length of video is shortened.
- Remove from database doesn't work
- Never versions of VLC doesn't work well.
## Credits
Created by [Alexa Ognjanovic](https://www.github.com/GrbavaCigla/)
