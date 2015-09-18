
# spotify-osx

  Simple Osascript interface to receive current track information from Spotify.

## Installation

```
$ cp spotify.scpt /usr/local/bin/spotify
$ chmod +x /usr/local/bin/spotify
```

## Usage

```
  Usage: spotify <argument>

  Arguments:
    artist - show artist name
    track  - show track name
    album  - show album name
```

## Sample

```
$ spotify artist # Opeth
$ spotify track  # River
$ spotify albumn # Pale Communion
```

## tmux

  To show the current artist and track name in the right status bar, you could
  simply add following snippet to your ```.tmux.conf``` file.

```
set-option -g status-right '#(spotify artist) - #(spotify track)'
```

## License

  MIT
