<div align="center">

<img src="images/logo.svg" width="96" alt="Tomato">

## `🍅 Tomato Autoscript — Premium VPN Server 🚀` *

`made with 🤍 from Mr dudul`

---

**One script, every protocol. Deploy a premium VPN server on your VPS in about 2 minutes.**

SSH · OpenVPN · VMess · VLESS · Trojan · ZiVPN · HCR · BHTTP · SlowDNS · UDP Custom

<a href="https://store.dudul.my.id/license">
  <img src="https://img.shields.io/badge/🛒%20Order%20License-store.dudul.my.id-695aa6?style=for-the-badge" alt="Order License">
</a>
<a href="https://tomatosc.my.id">
  <img src="https://img.shields.io/badge/🌐%20Website-tomatosc.my.id-ec185d?style=for-the-badge" alt="Website">
</a>

<img src="https://img.shields.io/badge/Rust-SSH%20Core-000000?style=flat-square&logo=rust&logoColor=white">
<img src="https://img.shields.io/badge/Xray-VMess%20·%20VLESS%20·%20Trojan-5b4bb7?style=flat-square">
<img src="https://img.shields.io/badge/Debian-12%20·%2013-A81D33?style=flat-square&logo=debian&logoColor=white">
<img src="https://img.shields.io/badge/Ubuntu-22.04%20·%2024.04%20·%2026.04-E95420?style=flat-square&logo=ubuntu&logoColor=white">

</div>

<div align="center">
  <img src="images/menu.png" width="260" alt="Main menu">
  <img src="images/dash.png" width="260" alt="Dashboard">
</div>

### Why Tomato?
- ⚡ **Lightweight** — the SSH core is written in **Rust** and runs comfortably on a **1 core / 1 GB RAM** VPS.
- 🔐 **Quota & IP limits on every protocol** — SSH, OpenVPN and ZiVPN included, not just Xray.
- 🔄 **One-click updates** — if anything fails midway, it rolls back automatically and every account stays intact.
- 🛒 **Ready to sell** — REST API for selling websites, multi-server Telegram bot, a subscription page for every account.
- 🛡️ **Regular security updates** — binaries are rebuilt whenever an important CVE lands; end-of-life OS versions are not forced to keep running.

### Protocols & Ports
| Service | Port |
|---|---|
| 🦀 SSH (Tomato Proxy) | `109` `143` |
| 🌐 SSH WebSocket | `80` `443` · nTLS `2086` `8080` `8880` |
| 🔒 SSH SSL / SNI | `443` `8443` |
| 📡 OpenVPN TCP · UDP · SSL | `1194` `2200` `443` |
| ✨ VMess · VLESS · Trojan (WS, gRPC, HTTPUpgrade, XHTTP) | TLS `443` · nTLS `80` |
| ⚡ ZiVPN UDP | `5667` `6000-19999` |
| 💉 HCR · BHTTP | `2087` · `2082` `2096` |
| 🧬 SlowDNS · UDP Custom | `53` `5300` · `1-65535` |
| 🎮 UDPGW | `7100` `7200` `7300` |

> One SSH account works on every SSH-based path (WS, SSL, OpenVPN, HCR, BHTTP, SlowDNS, UDP Custom).

### Features
| 👤 Accounts | 📊 Control | 🤖 Automation |
|---|---|---|
| Create, Renew, Detail, Trial | Quota & IP limit on all protocols | Auto-delete expired accounts |
| Custom UUID & password | Lock / Unlock + Autolock | Auto-remove when quota runs out |
| Check login with IP & ISP | Multi-login & quota alerts | Auto backup to Telegram |
| Subscription links for all protocols | Real-time bandwidth monitoring | Encrypted web backup & restore |
| Multi-server Telegram bot | Anti-DDoS & anti-torrent | Free DNS record & auto TLS |
| REST API for selling websites | Xray relay routing | Scheduled auto reboot |

### Preview
<details open>
<summary><b>🖥️ Terminal Menus</b></summary>
<br>
<div align="center">
  <img src="images/ssh-menu.png" width="220" alt="SSH menu">
  <img src="images/vmess-menu.png" width="220" alt="VMess menu">
  <img src="images/vless-menu.png" width="220" alt="VLESS menu">
  <img src="images/trojan-menu.png" width="220" alt="Trojan menu">
  <img src="images/zivpn-menu.png" width="220" alt="ZiVPN menu">
  <img src="images/settings-menu.png" width="220" alt="Settings menu">
</div>
</details>

<details open>
<summary><b>📱 Subscription Pages & Server Status</b></summary>
<br>
<div align="center">
  <img src="images/subs-ssh.png" width="180" alt="Sub SSH">
  <img src="images/subs-vmess.png" width="180" alt="Sub VMess">
  <img src="images/subs-vless.png" width="180" alt="Sub VLESS">
  <img src="images/subs-trojan.png" width="180" alt="Sub Trojan">
  <img src="images/subs-zivpn.png" width="180" alt="Sub ZiVPN">
  <img src="images/status.png" width="180" alt="Server status">
</div>
</details>

<details open>
<summary><b>🤖 Telegram Bot</b></summary>
<br>
<div align="center">
  <img src="images/bot.png" width="240" alt="Telegram bot">
</div>
</details>

### VPS Requirements
| | Minimum |
|---|---|
| CPU | 1 Core |
| RAM | 1 GB |
| Storage | 10 GB |
| Architecture | x86_64 / AMD64 |
| OS | Debian 12 / 13 · Ubuntu 22.04 / 24.04 / 26.04 (fresh install) |
| Access | root |

> ★ Recommended: **Ubuntu 24.04 LTS** or **Debian 12**.

### How to Order & Install
1. 🛒 Buy a license at **[store.dudul.my.id/license](https://store.dudul.my.id/license)** — pick a duration and IP limit, pay, and the license is active right away.
2. 🔑 Open your license page in the store and copy the install command shown there, then run it on your VPS as **root**.
3. 🌐 Follow the on-screen steps (use your own domain or the built-in free DNS).
4. ✅ Done — type `menu` to start creating accounts.

> Moving to a new VPS IP? Change it yourself from the license page in the store.

### Payment Methods
`QRIS` · `DANA` · `ShopeePay` · `Bank Transfer` · `PayPal`

<div align="center">

<a href="https://store.dudul.my.id/license">
  <img src="https://img.shields.io/badge/🍅%20Order%20Tomato%20Now-store.dudul.my.id-ec185d?style=for-the-badge" alt="Order Now">
</a>

</div>

### Donation
<div align="left">
  <a href="https://saweria.co/dudulrealnofek">
    <img src="https://img.shields.io/badge/Saweria-Donate%20/%20Support%20the%20Work-F47C20?style=for-the-badge&logo=ko-fi&logoColor=white" alt="Saweria Donate">
  </a>
</div>

#### Credit

 > - [MrDudul](https://t.me/dudulrealnofek)
 > - Telegram Group: [t.me/tfnuklir](https://t.me/tfnuklir)

<div align="center">

  `made with 🤍 from Mr Dudul`

</div>
