# Auto-reencode
### Purpose
Mass convert lesser known formats such as asf, flv, and wmv to mp4 contained x264 files using ffmpeg.
* Retains file's original bitrates (audio/video).
* Retains file's original date/time stamp.
* Temp files for 2 pass encode are written to /tmp (should be tmpfs).

### Usage
Call the script in the directory containing the target files to convert.

### Links
AUR Package: https://aur.archlinux.org/packages/auto-reencode

### Dependencies
* bash
* coreutils
* ffmpeg
* findutils
