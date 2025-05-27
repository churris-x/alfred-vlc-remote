# Alfred VLC Remote

![Basic usage](images/screenshot_basic.png)

## Prerequisites

- Alfred 3
- Alfred Powerpack
- VLC
- Optional: Alfred Remote iPhone app

## Installation

- Download `vlc_remote.alfredworkflow`
- Import it into your collection of Alfred workflows by double clicking it

## Usage

- Open Alfred
- Write the keyword `vlcr` followed by
    - `play`  / `pause`: toggles between playback and pause
    - `stop`: exits out of playback and show the playlist
    - `next`: next chapter or file
    - `prev`: previous chapter or file
    - `fullscreen`: toggles fullscreen
    - `downloads`: loads all content of your user's Downloads folder into VLC's playlist
    - `volup`: increases volume by one increment (of 32)
    - `volup`: decreases volume by one increment (of 32)
    - `volmax`: maxes out VLC's volume (use with care)
    - `mute`: toggles mute
    - `delayup`: increases audio delay by 50ms
    - `delaydown`: decreases audio delay by 50ms
    - `subs`: toggles through the available subtitles
    - `quit`: quits VLC


## License & Acknowledgements
This is an update version of the orignal
[vlc remote workflow](https://github.com/geberl/alfred-vlc-remote) by [Günther Eberl](https://github.com/geberl).
All code is under the GPLv3 License.

Many thanks to:

- [Thread on Alfred forums](https://www.alfredforum.com/topic/10027-vlc-remote/)
- [jeroenbegyn's AppleScript](https://github.com/jeroenbegyn/VLCControl) to control VLC
- [Which functions of an application IO with AppleScript](https://www.safaribooksonline.com/library/view/applescript-the-definitive/0596102119/ch01s02.html)
- [Clicky Steve's Alfred VLC workflow](http://www.packal.org/workflow/vlc-remote-control)


