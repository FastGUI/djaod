<div align="center">

![DJAOD Logo](https://img.alicdn.com/bao/uploaded/i2/O1CN01T40tdG24PTHFqFNIA_!!4611686018427384439-2-rate.png)

# 🎵 DJAOD — DJ Music CMS System

### The All-in-One Intelligent Music Library Management Platform for Professional DJs & Producers

[![Version](https://img.shields.io/badge/version-1.0.59-blue.svg)](https://www.djaod.com/)
[![Node.js](https://img.shields.io/badge/Node.js-%3E%3D%20v22.20.0-brightgreen.svg)](https://nodejs.org/)
[![Downloads](https://img.shields.io/badge/downloads-21,702%2B-orange.svg)](https://www.djaod.com/download)
[![License](https://img.shields.io/badge/license-Commercial-red.svg)](https://www.djaod.com/)
[![Website](https://img.shields.io/badge/website-djaod.com-0366d6.svg)](https://www.djaod.com/)

**Streamline your audio assets with automated metadata extraction, structured library management, and multi-channel monetization — turn your massive music collection into a steady revenue stream.**

[🌐 Official Website](https://www.djaod.com/) &nbsp;|&nbsp;
[📦 Download](https://www.djaod.com/download) &nbsp;|&nbsp;
[💰 Pricing](https://www.djaod.com/pricing) &nbsp;|&nbsp;
[📖 Documentation](https://www.djaod.com/docs) &nbsp;|&nbsp;
[🎨 Theme Marketplace](https://www.djaod.com/templates) &nbsp;|&nbsp;
[🔌 Plugin Marketplace](https://www.djaod.com/plugins)

</div>

<div align="center">

[🇨🇳 简体中文](../) | [🇺🇸 English](../en/) | [🇹🇼 繁體中文](../tw/) | [🇹🇭 ไทย](../th/) | [🇻🇳 Tiếng Việt](../vi/) | [🇲🇲 မြန်မာ](../mm/) | [🇰🇭 ខ្មែរ](../kh/) | [🇰🇷 한국어](../kr/) | [🇯🇵 日本語](../jp/) | [🇷🇺 Русский](../ru/) | [🇲🇳 Монгол](../mn/)

</div>

---

## ✨ Key Features

### 🚀 Next-Gen Tech Stack
Powered by a **non-blocking async I/O engine + distributed database**, handling high-concurrency workloads with ease. Outperforms traditional CMS platforms — supports hundreds of DJ site operators managing libraries, orders, and members simultaneously with sub-second response times under heavy traffic.

### 🎹 Automatic BPM & KEY Detection
Upload a track and instantly extract **BPM, musical KEY, bitrate, channels, sample rate, and cover art** — all in one step. Eliminates the need for multiple external analysis tools, letting DJs focus on creativity instead of tedious metadata entry.

### ☁️ Cloud Storage & CDN Acceleration
Decoupled architecture: website logic runs independently while all media files live in cloud object storage with **global CDN acceleration**. Say goodbye to slow uploads, buffering playback, and server bandwidth bottlenecks — even massive audio libraries stream instantly.

### 🔒 Multi-Bitrate HLS Streaming
One upload automatically generates **320k / 256k / 192k / 128k** bitrate variants. Trial playback uses **M3U8 / HLS adaptive streaming**, preventing browser-based audio ripping. Visitors get the best quality their connection can handle while your source files stay protected.

### 🛒 Full E-Commerce Suite
Multi-variant products, customer reviews, inventory management, shipment tracking, multi-payment gateway support. Sell **DJ USB drives, equipment, event tickets, coupons, and digital resources** — everything you need to monetize your site.

### 🎤 Artist / Producer Platform
Submission → Review → **Configurable revenue split** → Earnings dashboard → Payout management. Build a complete music ecosystem: invite producers to upload tracks, set commission rates, and let them earn — all within your platform.

### 💬 Community & Social
Create or join circles, post updates, comment, like, repost, and share. Foster engagement and retention with a built-in social layer that turns casual visitors into active community members.

### 📢 Marketing Toolkit
**Flash sales · Group buys · Pre-orders · Loyalty points · VIP tiers** — rich promotional tools to boost member conversion rates and maximize revenue. Flexible configuration for diverse monetization strategies.

### 📺 Unified Content Hub
Manage **music tracks, albums, playlists, videos, e-commerce, communities, and artist submissions** from a single dashboard — a complete media platform without the overhead of juggling multiple systems.

---

## 🛠️ Tech Stack

| Category         | Technology                              |
| ---------------- | --------------------------------------- |
| Runtime          | Node.js >= v22.20.0                     |
| Backend Engine   | Non-blocking Async I/O Engine           |
| Database         | Distributed Database                    |
| File Storage     | Cloud Object Storage + Global CDN       |
| Streaming        | M3U8 / HLS Adaptive Bitrate             |
| Audio Analysis   | Auto BPM / KEY / Bitrate Detection      |

---

## 🎯 Use Cases

- 🎧 **Personal DJ Website** — Showcase portfolio, promote gigs, sell resources
- 🏢 **Record Label / Music Platform** — Manage multi-artist catalogs, run communities
- 🛍️ **DJ Music Download Site** — Membership-based paid downloads, VIP subscriptions
- 🎓 **DJ Education Platform** — Video courses + audio resources in one system

---

## 🏆 Trusted by Leading DJ Platforms

| Site | Category | URL |
| ---- | -------- | --- |
| **CNDJPooL** | All-in-One DJ Services | [jcdjpool.com](https://www.jcdjpool.com/) |
| **Hailuo EDM** | Music Samples & Sound Packs | [hlydjs.com](https://www.hlydjs.com/) |
| **Monster EDM** | Wedding DJ Music | — |
| **Tiger EDM** | Original EDM & Club Tracks | [pthedm.cn](https://www.pthedm.cn/) |
| **CPUDJ** | Bar & Club Dance Music | [cpudj.com](https://www.cpudj.com/) |
| **DJMIX** | Record Label & SET Releases | [djmix.cn](https://www.djmix.cn/) |
| **MLK EDM** | EDM News & Music | [mlkdj.com](https://www.mlkdj.com/) |

---

## 🚀 Quick Start

```sh
curl -sL https://download.djaod.com/install.sh -o install.sh && chmod +x install.sh && ./install.sh
```

- Beginners are recommended to use **BaoTa Panel** + one-click install script
- First install `Nginx`, `Node.js` and `Redis` via BaoTa Panel, but **do NOT install `MongoDB` via BaoTa Panel** — it cannot be configured for clustering (required by the system!)
- Once the script completes successfully, create a Node.js site in BaoTa Panel
- In Node.js site management, create the **frontend site** as a `"Default Project"`, set entry point to `/index.js`, startup command to `npm run index`, and port to `3080`
- In Node.js site management, create the **backend site** as a `"Default Project"`, set entry point to `/admin.js`, startup command to `npm run admin`, and port to `3000`
- Note: BaoTa Panel auto-starts sites after creation — stop them first, then use the commands below
- Start the frontend site:
```sh
systemctl start djaod-index.service
```
- Start the backend site:
```sh
systemctl start djaod-admin.service
```

## Video Tutorial
<iframe src="//player.bilibili.com/player.html?isOutside=true&aid=116588648928433&bvid=BV1RCLE6SEWY&cid=38397151746&p=1" width="100%" height="450"  scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>

> **Dead-simple deployment**: Upload source → Configure database → Point your domain → Go live.

---

## 📈 Monetization Pipeline

```
Upload tracks → Paid member downloads → Sell equipment/USB drives via e-commerce
                      ↓
         Artist submissions → Revenue share commissions
                      ↓
      Community engagement → VIP subscriptions → Recurring revenue
```

---

## 🌟 Why DJAOD?

| Feature | Traditional CMS / WordPress | DJAOD |
| ------- | -------------------------- | ----- |
| Audio BPM Analysis | Requires 3rd-party tools | ✅ Built-in auto-detection |
| Anti-Rip Protection | Easy to scrape via browser | ✅ HLS encrypted streaming |
| Cloud Storage | Consumes server bandwidth | ✅ CDN-accelerated |
| Artist Revenue Split | Not available | ✅ Native commission system |
| E-Commerce | Requires plugins | ✅ Built-in shop |
| High Concurrency | Prone to slowdowns | ✅ Async I/O engine |

---

## 🔗 Links

- 🌐 Official Website: [https://www.djaod.com/](https://www.djaod.com/)
- 📦 Download: [https://www.djaod.com/download](https://www.djaod.com/download)
- 💰 Pricing: [https://www.djaod.com/pricing](https://www.djaod.com/pricing)
- 📖 Docs: [https://www.djaod.com/docs](https://www.djaod.com/docs)
- 🎨 Themes: [https://www.djaod.com/templates](https://www.djaod.com/templates)
- 🔌 Plugins: [https://www.djaod.com/plugins](https://www.djaod.com/plugins)
- 🛠 Custom Development: [https://www.djaod.com/custom](https://www.djaod.com/custom)

---

## 📬 Contact

- 🏢 **Developer**: DaTu Network Studio (大图计算机网络工作室)
- 🌐 **Website**: [https://www.djaod.com/](https://www.djaod.com/)
- 📧 For inquiries and technical support, visit the official website

---

<div align="center">

### 📢 From "I've got the tracks" to "I've got the cash" — all you need is DJAOD!

[⭐ Star This Project](https://www.djaod.com/) &nbsp;|&nbsp;
[🔗 Fork & Share](https://www.djaod.com/)

---

© 2026 DJAOD. All rights reserved. [黔ICP备17003115号-4](https://beian.miit.gov.cn/)

</div>
