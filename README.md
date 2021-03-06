# FFmpeg + nvenc build script

This script will compile FFmpeg with Nvidia NVENC support enabled.
It can also build OBS Studio using that FFmpeg build thus providing NVENC for
OBS as well.

It is brought to you by [Linux GameCast](http://linuxgamecast.com/) and
[Lutris](https://lutris.net)

## Usage

Clone the repo then use the `build.sh` script to compile the binaries

```
git clone https://github.com/lutris/ffmpeg-nvenc.git
cd ffmpeg-nvenc
./build.sh --dest /home/user/apps/ffmpeg-nvenc
```

The following command line options are available:

* -d / --dest <path> : Destination path for FFmpeg / OBS
* -o / --obs : Build OBS Studio
* -h / --help : Usage

## TODO

* Add support for multiple distributions (currently only tested on Ubuntu 16.04)

## Supporting the authors

If you find this script useful, you can consider
[supporting Linux GameCast](https://www.patreon.com/linuxgamecast).
