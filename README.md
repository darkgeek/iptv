# iptv
`iptv` is a CLI IPTV player for M3U playlists with search function by leveraging on `rofi`, suitable for both desktop and TV.

![iptv](https://github.com/darkgeek/iptv/blob/master/screenshot.png?raw=true)

The playlist will be updated once a day whenever you run `iptv`.

## Dependencies
- [curl](https://github.com/curl/curl)
- [rofi](https://github.com/davatorium/rofi)
- [mpv](https://github.com/mpv-player/mpv)

All dependencies can be installed with your package manager.

## Installation
```
sudo wget https://raw.githubusercontent.com/shahin8r/iptv/master/iptv -qO /usr/local/bin/iptv && sudo chmod +x /usr/local/bin/iptv
```

Run `iptv` with your playlist URL to load all the channels (only needed on first run).
```
iptv https://raw.githubusercontent.com/Free-TV/IPTV/master/playlist.m3u8
```

## Usage
Run `iptv`.
