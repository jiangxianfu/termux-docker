# Docker

这个项目是抄袭的 Atilo 的，我觉得叫这个名称太难记了，我就仅仅是将名称改成了Docker， 如果使用原版的请麻烦去Atilo项目去下载

## 新增了一个选项可以自由切换cn en

``` bash
docker images [cn|en]
docker pull images [cn|en]
```

A program to install linux on termux  


## Installation

``` bash
copy docker /data/data/com.termux/files/usr/bin/docker
chmod +x /data/data/com.termux/files/usr/bin/docker
# 运行前需要安装python3相关依赖包
```

## Usage

``` bash
docker [command] [Arguments]
docker           2.0
Usage: docker [Command] [Argument]

Docker is a program to help you install some GNU/Linux distributions on Termux.

Commands:
images           list available images
remove           remove installed images
pull             pulling an image
run              run an image
clean            clean tmps
help             show this help.
```

## Support Linux

| Distribution  | aarch64 |  arm  | x86_64 | i686  |
| ------------- | :-----: | :---: | :----: | :---: |
| Arch          |    √    |   √   |   ×    |   ×   |
| Alpine        |    √    |   √   |   √    |   √   |
| CentOS        |    √    |   ×   |   √    |   ×   |
| Debian        |    √    |   √   |   √    |   √   |
| Fedora        |    √    |   ×   |   √    |   ×   |
| Kali          |    √    |   √   |   √    |   √   |
| openSUSE      |    √    |   √   |   ×    |   ×   |
| Ubuntu        |    √    |   √   |   √    |   √   |
| Ubuntu LTS    |    √    |   √   |   √    |   √   |

## GUI

[Using GUI on termux](https://yadominjinta.github.io/2018/08/18/GUI-on-termux-EN.html)

## Group

Telegram:[Termux Group ZH_CN](https://t.me/joinchat/EBPa7EI3VrfhsRu-6iJ1yw)

# Relate Projects

**[EXALAB/AnLinux-App](https://github.com/EXALAB/AnLinux-App)**: APP to help install Linux on termux.  
**[sdrausty/TermuxArch](https://github.com/sdrausty/TermuxArch)**: Arch install script  
**[Neo-Oli/termux-ubuntu](https://github.com/Neo-Oli/termux-ubuntu)**: Ubuntu chroot on termux  
**[Hax4us/Nethunter-In-Termux](https://github.com/Hax4us/Nethunter-In-Termux)**: Install Kali nethunter (Kali Linux) in your termux application without rooted phone  
**[nmilosev/termux-fedora](https://github.com/nmilosev/termux-fedora)**: A script to install a Fedora chroot into Termux  
**[sp4rkie/debian-on-termux](https://github.com/sp4rkie/debian-on-termux)**: Install Debian 9 (stretch) on your Android smartphone

**[Hax4us/TermuxAlpine](https://github.com/Hax4us/TermuxAlpine)**: Use TermuxAlpine.sh calling to install Alpine Linux in Termux on Android  
