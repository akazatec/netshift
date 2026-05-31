# 🌐 NetShift

<p align="center">
  <img src="banner.png" width="800"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20by-akazatec-blueviolet?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Bash-4.0%2B-green?style=for-the-badge&logo=gnubash"/>
  <img src="https://img.shields.io/badge/Platform-Kali%20%7C%20Linux-black?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge"/>
</p>

**NetShift** is a lightweight bash-based local IP modifier tool with a clean neon terminal UI.
Built for network learners and Linux enthusiasts — runs on Kali Linux and any Debian-based system.

> ⚠️ **Educational Purposes Only** — This tool is built to demonstrate how local IP address modification works on Linux systems. Any misuse for unauthorized network activity is strictly prohibited. The author is not responsible for any misuse.

---

## ✨ Features

- 🎨 **Neon Terminal UI** — Eye-catching interface with colors and animations.
- 🌐 **Auto Interface Detection** — Automatically detects active network interfaces.
- ⚡ **Fast & Lightweight** — Pure bash, no heavy dependencies.
- 🔍 **IP Validation** — Checks if entered IP format is correct before applying.
- 📦 **Auto Dependency Install** — Installs missing packages automatically.

---

## ⚙️ Requirements

- Linux / Kali Linux
- `net-tools` (auto-installed if missing)
- `sudo` / root access

---

## 🛠️ Installation

### 🐧 Kali / Debian Linux

```bash
sudo apt update && sudo apt upgrade
sudo apt install git
git clone https://github.com/akazatec/netshift
cd netshift
chmod +x netshift.sh
bash netshift.sh
```

---

## 🚀 Usage

```bash
bash netshift.sh
```

Tool automatically detects your active network interface.

### 📌 Steps:
1. Tool run karo — automatically network scan karega
2. Active interface detect hone ke baad **IP prompt aayega**
3. Apna **naya IP address type karo** aur Enter dabaao
4. Format: `192.168.1.100` ya same range mein koi bhi IP

### 💡 Example:
```
[🌐] ACTIVE INTERFACE: eth0

┌──[akazatec㉿NetShift]-[~]
└─$ 172.18.31.65
```

✅ IP successfully change ho jayegi!

> ⚠️ Note: Same network range mein IP dena — pehle 3 parts same honge.
> Example: `172.18.31.XXX` mein sirf last number change karo (1-254)

---
## 🗂️ File Structure

| File | Description |
| :--- | :--- |
| `netshift.sh` | Main bash script — core of the tool. |
| `banner.png` | Terminal UI preview image. |
| `README.md` | Project documentation. |
| `LICENSE` | MIT License details. |

---

## 🤝 Contributing

Contributions are welcome!
Fork → Changes → Pull Request — simple hai.

## ⚖️ License

This project is licensed under the **MIT License** — see [LICENSE](LICENSE) for details.

## 👤 Author

**akazatec**
- GitHub: [@akazatec](https://github.com/akazatec)

---

<p align="center">
  <i>"Shift your network. Own your IP."</i>
</p>
