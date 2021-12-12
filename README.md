

## Deploy
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/for-test-by-w5/DogeBot/)

# Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip)
* [Libwebp](https://developers.google.com/speed/webp/download)
* Any text editor

## `ADD BUILDPACK`

```
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
https://github.com/DuckyTeam/heroku-buildpack-imagemagick
heroku/nodejs
```

## `CHANGE SESSION`

[`Click Here`](https://github.com/for-test-by-w5/DogeBot/blob/master/session.json#L1)

# Installation
## Clone Repo & Installation dependencies
```bash
🦄 git clone https://github.com/DGXeon/DogeBot.git
🦄 cd DogeBot
🦄 npm start
```
## For Termux
```bash
🦄 apt update
🦄 apt upgrade
🦄 pkg update && pkg upgrade 
🦄 pkg install bash
🦄 pkg install libwebp
🦄 pkg install git -y
🦄 pkg install nodejs -y 
🦄 pkg install ffmpeg -y 
🦄 pkg install wget
🦄 pkg install imagemagick -y
🦄 git clone https://github.com/DGXeon/DogeBot
🦄 cd DogeBot
🦄 ls
🦄 rm -rf session.json
🦄 npm install
🦄 npm start
🦄 scan qr code within 15seconds
```

