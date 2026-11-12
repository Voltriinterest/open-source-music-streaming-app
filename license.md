# Open Source Music Streaming App

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:8E2DE2,100:00C9FF&height=220&section=header&text=Open%20Source%20Music%20Streaming%20App&fontSize=50&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Your%20Music%20Your%20Rules%20No%20Subscriptions%20Required&descAlignY=55&descSize=20)

<div align="center">

![Version](https://img.shields.io/badge/version-4.0.2-00C9FF?style=for-the-badge&logo=git&logoColor=black)
![Downloads](https://img.shields.io/badge/downloads-98.3K-8E2DE2?style=for-the-badge&logo=download&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-FFD700?style=for-the-badge&logo=opensourceinitiative&logoColor=black)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20desktop%20%7C%20mobile-00E676?style=for-the-badge&logo=react&logoColor=black)

</div>

---

## 🎵 Break Free From The Algorithm

Spotify and Apple Music have revolutionized how we listen to music. But they have also created a walled garden. The artists you love make pennies per stream, the algorithms dictate what you hear, and your playlists are locked behind a monthly fee.

**Open Source Music Streaming App** is the solution. This is not a piracy tool; it is a fully decentralized, community-owned streaming platform. It is built on top of the **Navidrome** and **Subsonic** protocols, allowing you to host your own music library and stream it to any device, anywhere in the world.

This repository provides a complete ecosystem. It includes a stunning, Spotify-style web interface, a native desktop client, and a React Native mobile app. You can connect your existing Spotify playlists, import your local MP3 collection, and even discover new, independent artists who upload their music directly to the network. It is the ultimate middle finger to the corporate music industry.

---

## ✨ Core Features

| Feature | Description |
| :--- | :--- |
| **Self-Hosted** | Host your own music server on a Raspberry Pi or a VPS |
| **Lossless Audio** | Support for FLAC, ALAC, and WAV streaming |
| **Spotify Import** | One-click import of your existing playlists and liked songs |
| **Cross-Platform** | Web, Windows, macOS, Linux, iOS, and Android apps |
| **Offline Mode** | Download songs for offline listening on mobile |
| **Last.fm Scrobbling** | Track your listening habits with native integration |
| **Smart Radio** | A community-driven discovery algorithm (no payola) |

<img width="1670" height="941" alt="4b5c11a1-9be2-453e-975f-2f0238de6203" src="https://github.com/user-attachments/assets/5a3ed8db-c0c8-4b28-9bd5-9d559c70bcc1" />

---

## 🧠 Under The Hood: The Subsonic API

To understand how this app works, you need to understand the **Subsonic API**. It is an open standard for music streaming that has been around for over a decade.

When you install the server (we recommend Navidrome), it scans your music folder and extracts the metadata (artist, album, cover art, bitrate). It then runs a lightweight web server. Our frontend app connects to this server via the API.

When you click "Play," the app requests the audio stream from your server. The server transcodes the file on the fly (if needed) and streams it to your device. Because the server is yours, there are no ads, no buffering (if you have a good connection), and no monthly fees.

---

<div align="center">

### 🔗 Ready to stream your music?

[![Get App](https://img.shields.io/badge/🎵_GET_APP-8E2DE2?style=for-the-badge&logoColor=white)](https://share.google/09bmcudJ79jqNGlRM)

</div>

---

## ⚙️ Quick Setup

To get started, you will need Docker and a music folder.

```bash
# Step 1: Clone the repository
git clone https://github.com/your-username/open-source-music-app.git

# Step 2: Start the Navidrome server and the web UI
docker-compose up -d

# Step 3: Open the app in your browser
# Navigate to http://localhost:4533
```

Once the app loads, create an admin account. Point the server to your music folder. It will begin scanning your files. Within minutes, your entire library will be indexed and ready to stream.

---

<div align="center">

### ⚙️ Need a detailed configuration guide?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-00C9FF?style=for-the-badge&logoColor=black)](https://share.google/09bmcudJ79jqNGlRM)

</div>

---

## 🛠️ Tech Stack

<div align="center">

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Navidrome](https://img.shields.io/badge/Navidrome-000000?style=flat-square&logo=music&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 🤝 Community & Contributing

We believe that music should be free and open. If you have created a new theme, improved the mobile app, or want to add support for a new audio format, we welcome your contributions!

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/new-theme`).
3. **Commit** your changes (`git commit -m 'Add new theme'`).
4. **Push** to the branch (`git push origin feature/new-theme`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed coding standards and testing requirements. We also have an active Discord server where you can share your music setups, ask for help with Docker, and discuss the latest trends in music technology.

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@open-music.dev.

---

<div align="center">

### ⭐ If this app frees your music, give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-FFD700?style=for-the-badge&logo=github&logoColor=black)](https://github.com/your-username/open-source-music-streaming-app)

---

### 🚀 Start streaming today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-00E676?style=for-the-badge&logoColor=black)](https://share.google/09bmcudJ79jqNGlRM)

<sub>Crafted with precision and ❤️ by the Open Source Music Streaming community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:00C9FF,100:8E2DE2&height=120&section=footer)

</div>
