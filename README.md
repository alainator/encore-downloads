# Encore downloads

**Encore** is a karaoke party app: one device hosts the party, a TV shows the music video with the lyrics, and everyone
adds songs from their phone's browser. These are the installers. Get them from the
[latest release](../../releases/latest).

## Which one do I need?

| You want to… | Get | On |
|---|---|---|
| **Host the party** on an Android tablet or phone | `Encore-Station-<version>.apk` | Android 8 or newer |
| **Host the party** on a Windows PC or laptop | `Encore-Setup-<version>.exe` (or the portable `.zip`) | Windows 10 / 11, 64-bit |
| **Show the party on a TV** | `Encore-TV-<version>.apk` | Android TV, Google TV, NVIDIA SHIELD, Chromecast with Google TV, Fire TV |
| **Join and add songs** | nothing to install | any phone's browser: scan the QR code on the TV |

Guests never install anything. iPhones and iPads join from the browser like everyone else.

## Installing

### Android tablet or phone (Encore Station)
1. Open the latest release on the device and tap `Encore-Station-<version>.apk`.
2. When Android asks, allow your browser to **install unknown apps**, then tap **Install**.
3. Open **Encore Station** and pick your songs folder.

### Android TV, Google TV, SHIELD, Chromecast with Google TV (Encore TV)
Easiest: once Encore Station is running, install the free **Downloader** app on the TV (Play Store), open it and
type the address the Station shows under **System → TVs → Encore TV on a friend's TV** (it ends in `/tv.apk`). Or copy `Encore-TV-<version>.apk` to the TV with a USB
stick and open it with a file manager.

### Fire TV (Encore TV)
1. Install **Downloader** from the Amazon Appstore.
2. Settings → My Fire TV → Developer options → **Install unknown apps** → turn on for Downloader.
3. In Downloader, type the address the Station shows (it ends in `/tv.apk`), or this release's
   `Encore-TV-<version>.apk` link, and install.

### Windows
1. Download `Encore-Setup-<version>.exe` and run it.
2. Windows may say **"Windows protected your PC"**: the installer isn't signed with a paid certificate. Click
   **More info → Run anyway**.
3. Encore opens in your browser; choose your songs folder. If Windows Firewall asks, allow **private networks** so
   phones and TVs on your Wi-Fi can reach it.

No installer wanted? Unzip `Encore-Windows-portable-<version>.zip` and run `Encore.exe`.

## Updating
Install the new version over the old one: your songs, settings and party history stay. (The Android apps update in
place because every release is signed with the same key.)

## Songs
Encore plays karaoke videos you already have (a video with lyrics, or one made by Karaoke Studio). It doesn't come with
songs and doesn't download any.
