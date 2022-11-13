<h1 align="center">Welcome<img src="https://user-images.githubusercontent.com/1303154/88677602-1635ba80-d120-11ea-84d8-d263ba5fc3c0.gif" width="40px" alt=""><br></h1>
<p align="center">DEFF-V8</p>
<div align="center">
<img src="https://telegra.ph/file/5c664494a7635ffba59e8.jpg" width="150" height="150" border="0" alt="PFFP">

<br> Gunakan dengan risiko Anda sendiri!

[![JavaScript](https://img.shields.io/badge/JavaScript-d6cc0f?style=for-the-badge&logo=javascript&logoColor=white)](https://javascript.com) [![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)

<a href="https://chat.whatsapp.com/C0y1iHxWw9n8odBcK3Rs5z"> <img src="https://img.shields.io/badge/whatsapp-Support_Group-blue?style=social&logo=whatsapp" alt="support" /></a>

> Dibuat dengan Baileys dan Map() ( sebagai command switch ) <br />

</div><br />
<br />

## Highlights

-   [x] Simple Penggunaan,
-   [x] Mudah digunakan,
-   [x] Mudah untuk dirawat/diperbaiki,
-   [x] Dan ringan

## Config

Isi semua yang dibutuhkan di file [`config.js`](https://github.com/DEFF-Y/DEFFBOTZ-V8/blob/main/config.js)<br />

## Request atau report bug

Untuk request atau report bug bisa chat saya disini [Whatsapp](https://wa.me/wa.me/43650422222666)

## Instalasi On Termux

### Clone Repo

```bash
$ pkg update && pkg upgrade
$ pkg i nodejs && pkg i git && pkg i yarn && pkg i libwebp && pkg i ffmpeg && pkg i imagemagick
$ git clone https://github.com/ZackMans/DEFFBOTZ-V8
$ cd RKY
$ yarn install && node index.js
# Scan QR
```

## Instalasi

### Dibutuhkan

1.  [Nodejs](https://nodejs.org/en/download) 16x/17x
2.  [FFmpeg](https://ffmpeg.org)
3.  [LibWebp](https://developers.google.com/speed/webp/download)
4.  [imagemagick](https://imagemagick.org/script/download.php)

### Install FFmpeg

-   Untuk pengguna Windows, kamu bisa lihat tutorial disini [WikiHow](https://www.wikihow.com/Install-Ffmpeg-on-Windows)<br />
-   Untuk pengguna Linux, kamu bisa pakai manager paket kamu sendiri. Contohnya;

```bash
# apt (Ubuntu)
apt install ffmpeg -y

# pacman (Arch Linux)
pacman -S ffmpeg
```

### Install LibWebp

-   Untuk pengguna Windows,

1.  Unduh libWebP untuk Windows dari [sini](https://developers.google.com/speed/webp/download)
2.  Ekstrak ke C:\
3.  Ganti nama folder yang diekstrak ke `libwebp`
4.  Buka PowerShell dan jalankan perintah berikut;

```cmd
setx /m PATH "C:\libwebp\bin;%PATH%"
```

> Bila sukses terinstal dengan baik, silahkan check dengan perintah berikut di Command Prompt

```cmd
webpmux -version
```

-   Untuk pengguna Linux, kamu bisa pakai manager paket kamu. Contohnya;

```bash
# apt (Ubuntu)
apt install libwebp-dev -y

# pacman (Arch Linux)
pacman -S libwebp
```

### Install imagemagick

-   Untuk pengguna Windows, kamu bisa lihat tutorial disini [Ziixon93](https://ziixon93.blogspot.com/2020/07/cara-memasang-imagemagick-di-xampp.html?m=1)<br />
-   Untuk pengguna Linux, kamu bisa pakai manager paket kamu sendiri. Contohnya;

```bash
# apt (Ubuntu)
apt install imagemagick -y

# pacman (Arch Linux)
pacman -S imagemagick
```

### Clone Repo

```bash
# clone repo
git clone https://github.com/ZackMans/ZackBotMans

# ubah posisi direktori kamu
cd RKY

# install semua module
npm install
# atau
yarn install

# bila libray @adiwajshing/baileys error, jalan kan kode yg ada dibawah ini

cd ./node_modules/@adiwajshing/baileys
npm install -g typescript
npm run build:tsc
```

### Start Bot

Start and Scan QR<br />

```bash
npm start
```

# Thanks To

-   [`@adiwajshing/baileys`](https://github.com/adiwajshing/baileys)
-   [`Nurutomo`](https://github.com/4ksanzz)



```Thanks to all who have participated in the development of this script```

Support Me
Thank For Base Zackmans & Dika Ardnt
-   [`Saweria`](https://saweria.co/4ksanzz)
