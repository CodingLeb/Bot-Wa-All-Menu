# Bot-Wa-All-Menu
HI, Saya disini Sebagai Author mengharapkan agar kalian untuk tidak di salah Gunakan. Disini Saya tidak bertangung jawab atas Terjadi Penipuan DLL yang mengakibatkan Anda menjadi korban.

### a little about this bot
- ✔️ | **Simple** 
- ✔️ | **Button Template** 
- ✔️ | **Multi Device** 
- ✔️ | **Button Document(Experiment)** 
---------
### Some of the features include
- ✔️ | Menfess
- ✔️ | AntiCall
- ✔️ | Game & Rpg Game
- ✔️ | Nsfw 
- ✔️ | Sticker 
- ✔️ | Kerang Ajaib 
- ✔️ | Quotes
- ✔️ | Anime 
- ✔️ | Premium 
- ✔️ | Tools 
---------

## ```USER RAILWAY```

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app)

## ```USER REPLIT```
[![Run on Repl.it](https://repl.it/badge/github/ImYanXiao/Elaina-MultiDevice)](https://repl.it/github/ImYanXiao/Elaina-MultiDevice)
## TERMUX USER
```bash
$ pkg upgrade && pkg update
$ pkg install git -y
$ pkg install nodejs -y
$ pkg install ffmpeg -y
$ pkg install imagemagick -y
$ git clone https://github.com/ImYanXiao/Elaina-MultiDevice
$ cd Elaina-MultiDevice
$ npm i 
```
If error try using yarn instead of npm
```bash
$ pkg install yarn -y
$ yarn install
$ node .
```
---------

## TERMUX WITH UBUNTU

```bash
apt update && apt full-upgrade
apt install wget curl git proot-distro
proot-distro install ubuntu
echo "proot-distro login ubuntu" > $PREFIX/bin/ubuntu
ubuntu
```
---------

[ INSTALLING REQUIRED PACKAGES ]

```bash
ubuntu
apt update && apt full-upgrade
apt install wget curl git ffmpeg imagemagick build-essential libcairo2-dev libpango1.0-dev libjpeg-dev libgif-dev librsvg2-dev dbus-x11 ffmpeg2theora ffmpegfs ffmpegthumbnailer ffmpegthumbnailer-dbg ffmpegthumbs libavcodec-dev libavcodec-extra libavcodec-extra58 libavdevice-dev libavdevice58 libavfilter-dev libavfilter-extra libavfilter-extra7 libavformat-dev libavformat58 libavifile-0.7-bin libavifile-0.7-common libavifile-0.7c2 libavresample-dev libavresample4 libavutil-dev libavutil56 libpostproc-dev libpostproc55 graphicsmagick graphicsmagick-dbg graphicsmagick-imagemagick-compat graphicsmagick-libmagick-dev-compat groff imagemagick-6.q16hdri imagemagick-common libchart-gnuplot-perl libgraphics-magick-perl libgraphicsmagick++-q16-12 libgraphicsmagick++1-dev
```

---------

[ INSTALLING NODEJS & ELAINABOT-MD]

```bash
ubuntu
curl -fsSL https://deb.nodesource.com/setup_current.x | sudo -E bash -
apt install -y nodejs gcc g++ make
git clone https://github.com/ImYanXiao/Elaina-MultiDevice
cd Elaina-MultiDevice
npm install
npm update
```

---------

## FOR WINDOWS/VPS/RDP USER 💻

* Download And Install Git [`Click Here`](https://git-scm.com/downloads)
* Download And Install NodeJS [`Click Here`](https://nodejs.org/en/download)
* Download And Install FFmpeg [`Click Here`](https://ffmpeg.org/download.html) (**Don't Forget Add FFmpeg to PATH enviroment variables**)
* Download And Install ImageMagick [`Click Here`](https://imagemagick.org/script/download.php)

```bash
git clone https://github.com/ImYanXiao/Elaina-MultiDevice
cd Elaina-MultiDevice
npm install
npm update
```

---------

## Run ⏳

```bash
node .
```

---------

## ```Arguments node . [--options] [<session name>]```

## `--self`
* activate self mode (ignores other)

## `--pconly`
* If that chat not from private bot, bot will ignore

## `--gconly`
* If that chat not from group, bot will ignore

## `--swonly`
* If that chat not from status, bot will ignore

## `--prefix <prefixes>`
* `prefixes` are seperated by each character
Set prefix

## `--server`
* Used for [heroku](https://heroku.com/) or scan through website

## `--restrict`
* Enables restricted plugins (which can lead your number to be **banned** if used too often)
* Group Administration `add, kick`

## `--img`
* Enable image inspector through terminal

## `--autoread`
* If enabled, all incoming messages will be marked as read

## `--nyimak`
* No bot, just print received messages and add users to database

## `--test`
* **Development** Testing Mode

---------

## ```How To Customise Message Display```
```js
// Syntax
conn.sendButton(
      jid, // jid of the user to send the message to
      text, // text to send
      foooter, // footer to send
      buffer, // buffer to send (optional), if you want to send button image, location, etc
      buttons, // buttons to send, example [['text1', 'id1'], ['text2', 'id2']]
      quoted, // quoted message to send (optional)
      options // options to send, example { asLocation: true }
)

// example 
conn.sendButton(m.chat, 'Hello world!', '@BochilGaming', null, [
      ['Hello', 'hello'], ['Bye', 'bye']
])
// example button location
conn.sendButton(m.chat, 'Hello world!', '@BochilGaming', 'https://github.com/BochilGaming', 
      [['Hello', 'hello'], ['Bye', 'bye']], 
      null, { asLocation: true }
)
```
---------

### 📮 S&K
1. Not For Sale
2. Don't forget give star this repo
3. Don't use this repository wrong!
4. If you have problem chat me in owner number

---------

## ```Thanks to ✨```
* [`Allah SWT`]
* [`My parents`]
* [`All Friends`]
* [`All Contributors`]
* [`All Creator Bot`]

