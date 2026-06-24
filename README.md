# 📺 Live-TV & IPTV Portal

[![IPTV Playlist](https://img.shields.io/badge/IPTV-Playlist-blueviolet.svg?style=for-the-badge&logo=iptv)](https://github.com/bijondev/live-tv)
[![Platform Support](https://img.shields.io/badge/Platform-Windows%20%7C%20Android%20%7C%20SmartTV-orange.svg?style=for-the-badge)](https://github.com/bijondev/live-tv)
[![Build Status](https://img.shields.io/github/last-commit/bijondev/live-tv?style=for-the-badge&color=success)](https://github.com/bijondev/live-tv/commits/main)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

A curated, high-quality IPTV playlist (`.m3u8`) and client application distribution portal. Stream live TV, premium news, live sports (including FIFA World Cup broadcasts), documentaries, kids' entertainment, and a massive collection of VOD movies (Hindi, South Indian Hindi-Dubbed, Bangla, and Kalkata Bangla) in high definition and 4K quality.

This repository features a regularly updated M3U8 playlist along with standalone media player installations tailored for Windows and Android.

---

## 🚀 Key Features

*   📺 **Comprehensive Channel Selection:** Over 150+ live channels categorized logically for easy navigation.
*   ⚽ **Live Sports Hub:** Premium sports streams including FIFA event channels, T Sports, PTV, Sony Ten, SuperSport, Fox Cricket, and ESPN.
*   🎬 **Extensive Movie Library (VOD):** On-demand movies across genres—featuring Bangla, Hindi (including a dedicated **4K Hindi Movies** library), and Hindi-Dubbed South Indian cinema.
*   📰 **Real-Time News:** Keep up with live local and international news streams (Jamuna TV, DBC News, Ekattor HD, Channel 24, and more).
*   🦁 **High-Quality Documentaries & Kids Content:** Family-friendly networks such as National Geographic 4K, Discovery 4K, Animal Planet 4K, Cartoon Network HD, and Pogo.
*   📱 **Cross-Device Ready:** Configured to work seamlessly on PCs, mobile devices, Android TV, and smart IPTV players.

---

## 📂 Repository Contents

| File / Directory | Target Platform | Description |
| :--- | :--- | :--- |
| [**`playlist.m3u8`**](file:///Users/bijonkrishnabairagi/code/live-tv/playlist.m3u8) | All Devices / IPTV Players | The core IPTV playlist database in standard M3U/M3U8 format. |
| [**`Streamly.exe`**](file:///Users/bijonkrishnabairagi/code/live-tv/Streamly.exe) | Windows PC | A standalone, custom IPTV streaming client for desktop. |
| [**`free-tv.apk`**](file:///Users/bijonkrishnabairagi/code/live-tv/free-tv.apk) | Android / Fire TV / Smart TV | Mobile and TV-optimized application file for direct IPTV playback. |

---

## 📡 Live Stream URL (For External Players)

To stream using external IPTV players, copy the **Raw M3U8 URL** below:

```text
https://raw.githubusercontent.com/bijondev/live-tv/main/playlist.m3u8
```

---

## 🛠️ How to Play & Install

### 1. On Windows (Desktop)
*   **Method A (Recommended):** Download and run [**`Streamly.exe`**](file:///Users/bijonkrishnabairagi/code/live-tv/Streamly.exe) directly from this repository to access the preloaded playlist channels inside a dedicated interface.
*   **Method B (Alternative Players):**
    1. Download and open **VLC Media Player** or **PotPlayer**.
    2. Press `Ctrl + N` (VLC) or right-click and select Open > URL (PotPlayer).
    3. Paste the [Raw Playlist URL](#-live-stream-url-for-external-players) and click **Play**.

### 2. On Android / Android TV / FireStick
1. Enable installations from unknown sources in your device settings.
2. Download and install [**`free-tv.apk`**](file:///Users/bijonkrishnabairagi/code/live-tv/free-tv.apk) onto your device.
3. Open the app to immediately browse and stream channels.
4. *Alternative:* Import the raw M3U8 link into popular apps like **Televizo**, **OTT Navigator**, or **IPTV Smarters Pro**.

### 3. On Apple TV / iOS / macOS
1. Download a player such as **GSE Smart IPTV**, **iPlayTV**, or **LilyPlayer** from the App Store.
2. Choose **Add Remote Playlist** / **Web Playlist**.
3. Insert the [Raw Playlist URL](#-live-stream-url-for-external-players).

---

## 📺 Channel & Video Category Overview

The playlist is indexed into the following group sections:

| Group Name | Content Type | Key Channels / VODs |
| :--- | :--- | :--- |
| **FIFA / Sports** | Live Sports Broadcasts | Telemundo, ESPN, FOX, FS1, FS2, Bein Sports UHD, SuperSport 4K, Sony Ten, PTV Sport |
| **News** | Live News Feeds | Jamuna TV, DBC News, Ekattor HD, Channel 24, ATN News, News 24 HD, Star News |
| **Entertainment** | Live Bangla & Indian TV | Maasranga TV, Deepto TV, NTV, Bangla Vision, Channel I, Zee Bangla 4K, Star Jalsa 4K |
| **4K Hindi Movies** | Ultra HD VOD | Animal, Chandu Champion, Bad Newz, Drishyam 2, Crew, Chhaava |
| **Hindi Movies** | Standard VOD | Daadi Ki Shaadi, Bhooth Bangla, System, Kartavya, The Raja Saab |
| **Southindian Hindi Dubbed** | Action & Drama VOD | Arjun S/O Vyjayanthi, Sathi Leelavathi, Karuppu, Love Insurance Kompany |
| **Bangla Movies** | Regional VOD | Toofan, Jongli, Surongo, Hubba, Bonolota Express, Ghumpori |
| **Documentary** | Educational & Nature | Discovery 4K, National Geographic 4K, History TV18 4K, Sony BBC Earth 4K |
| **Kids** | Cartoons & Animation | Cartoon Network HD, Pogo, Nick 4K, BuddyStar HD, Joy |

---

## ⚖️ Disclaimer

*   **Content Responsibility:** The streams listed in the playlist are gathered from publicly accessible servers and links across the internet. This repository does not host, upload, or modify any media streams or live broadcasts.
*   **Usage Policy:** Users are encouraged to verify streaming permissions, licenses, and legalities in their local jurisdictions before accessing channels. This project is for personal use and educational lookup purposes only.
