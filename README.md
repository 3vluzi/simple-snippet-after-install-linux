# Simple Snippet After Linux Installation
## npm Install
`sudo apt install npm`

## SciFi Terminal
- https://github.com/GitSquared/edex-ui#how-do-i-get-it
- https://github.com/GitSquared/edex-ui/releases

- `wget -c https://github.com/GitSquared/edex-ui/releases/download/v2.2.2/eDEX-UI.Linux.x86_64.AppImage`	[64-Bit]
- `wget -c https://github.com/GitSquared/edex-ui/releases/download/v2.2.2/eDEX-UI.Linux.i386.AppImage`	[32-Bit]

- `chmod +x eDEX-UI.Linux.x86_64.AppImage`
- `./eDEX-UI.Linux.x86_64.AppImage`


## Generate SSH KEY
`ssh-keygen -t ed25519 -C "YOUR_EMAIL"`

## Fix Corrupted install 
`sudo dpkg --configure -a`
## Disable sleep
- `sudo vi /etc/default/acpi-support # and then set SUSPEND_METHODS="none"`
- `sudo /etc/init.d/acpid restart`
## Remove Bad SOftware
`sudo apt-get remove --purge package_name`
## Add Video background Terminal
`sudo apt install terminology`
## Install pip3
`python3 get-pip.py`\
`sudo apt install python3-pip`

## Install Paket Module
`pip3 install NAMAPAKET ##find in https://pypi.org/`

## Install deb file 
`sudo apt install ./namafile.deb`

## Add PATH
`sudo nano /etc/environment`

## Make executable
`sudo chmod +x namafile`

## Own file 
`sudo chown -R username:username FOLDERNAME`

## Install Win Font
`sudo add-apt-repository multiverse`\
`sudo apt update && sudo apt install ttf-mscorefonts-installer`\
`sudo fc-cache -f -v`

## Install Filezilla
`sudo apt install filezilla`

## Install Screen Recorder
`sudo apt install simplescreenrecorder`

## install codec
`sudo apt install ubuntu-restricted-extras`

## install github desktop GUI 
`wget -qO - https://packagecloud.io/shiftkey/desktop/gpgkey | sudo tee /etc/apt/trusted.gpg.d/shiftkey-desktop.asc > /dev/null`\
`sudo sh -c 'echo "deb [arch=amd64] https://packagecloud.io/shiftkey/desktop/any/ any main" > /etc/apt/sources.list.d/packagecloud-shiftkey-desktop.list'`\
`sudo apt-get update`\
`sudo apt install github-desktop`

## ffmepg install
`sudo apt-get clean ; sudo apt-get update ; sudo apt-get check ; sudo apt-get purge ffmpeg* -y ; sudo apt-get autoremove -y ; sudo apt-get -f satisfy ffmpeg -y`\
source: https://forum.linuxconfig.org/t/ffmpeg-solve-unmet-dependencies/5356

## Install  VLC
`sudo apt install vlc`\
`sudo apt install vlc-plugin-access-extra libbluray-bdj libdvdcss2`\
`sudo dpkg-reconfigure libdvd-pkg`

## Optional Install VLC Plugin
`vlc-plugin-bittorrent`\
Bittorrent plugin for VLC

`vlc-plugin-fluidsynth`\
FluidSynth plugin for VLC

`vlc-plugin-jack`\
JACK audio plugins for VLC

`vlc-plugin-notify`\
LibNotify plugin for VLC

`vlc-plugin-qt`\
multimedia player and streamer (Qt plugin)

`vlc-plugin-samba`\
Samba plugin for VLC

`vlc-plugin-skins2`\
multimedia player and streamer (Skins2 plugin)

`vlc-plugin-svg`\
SVG plugin for VLC

`vlc-plugin-video-output`\
multimedia player and streamer (video output plugins)

`vlc-plugin-video-splitter`\
multimedia player and streamer (video splitter plugins)

`vlc-plugin-visualization`\
multimedia player and streamer (visualization plugins)

`vlc-plugin-vlsub`\
VLC extension to download subtitles from opensubtitles.org

## Install pytube
`pip3 install pytube`
GUI https://stackoverflow.com/questions/67416714/pytube-set-file-location-changes-to-working-directory

## Install Whois
`sudo apt install whois`

## Install nmap
sudo apt install nmap

## install git
`sudo apt install git`

## add kali repo 
`sudo sh -c "echo 'deb https://http.kali.org/kali kali-rolling main non-free contrib' > /etc/apt/sources.list.d/kali.list"`\
`sudo apt update`

## SSH import mysql
`mysql -u USERNAME -p DBNAME < SOURCE_IMPORTED.sql`


## ASCII Art 
`pip3 install ascii_magic`\
usage: 
`import ascii_magic`\
`my_art = ascii_magic.from_image_file('images/moon.jpg')`\
`ascii_magic.to_terminal(my_art)`\

## Download all content in remote folder
`wget -r -np -R "index.html*" -e robots=off  --no-parent https://download.quranicaudio.com/quran/abdurrahmaan_as-sudays/`

# Developer Must Have
- python
https://www.python.org/downloads/

- JupyterBook
https://jupyter.org/install

- XAMPP/LAMPP
https://www.apachefriends.org/download.html

- Filezilla 
https://filezilla-project.org/download.php?type=client

- Visual Studio Code
https://code.visualstudio.com/download

- Android Studio
https://developer.android.com/studio

- Github Linux Desktop
https://github.com/shiftkey/desktop/tree/release-2.9.4-linux1

- Etcher Bootable USB Maker
https://www.balena.io/etcher/

# FUN
## EDEX-UI
https://github.com/GitSquared/edex-ui/releases

## TypeFX Python
https://github.com/urbanware-org/typefx/blob/main/python3/typefx.py

## Sneaker Effect https://github.com/bartobri/no-more-secrets
- `cat namafile.txt | nms
`
## hollywood effect 
- `sudo apt-add-repository ppa:hollywood/ppa`
- `sudo apt update`
- `sudo apt install byobu hollywood`
