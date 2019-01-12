# English RPi Project
Project unfinished, it's highly experimental and work mainly on wifi cards > 2013. The goal of this project is, by providing the name of your wifi card interface, it give you a number between 0 and 100 if your hotspot is next to you or far.

## Thanks
Thanks to [bmegli](https://github.com/bmegli) for the [wifi-scan](https://github.com/bmegli/wifi-scan) Library.

## Usage
You can see the instructions and download the files in the [release page](https://github.com/joxcat/english-rpi-project/releases/) of this project.

## To build
You only need to do a `make B=ss` to build it, the release will be in the bin folder.

- **Dependencies**
- [Arch](#Archlinux)
- [Debian / Ubuntu](#Debian-or-Ubuntu)

### Archlinux
- linuxXXX-headers *(replace XXX with your linux kernel version)*
- libmnl

### Debian or Ubuntu
- build-essential
- libmnl0 libmnl-dev
- linux-headers-XXX *(replace XXX with the result of `uname -r`)*
