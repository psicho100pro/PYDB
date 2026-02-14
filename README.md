# 📊 [PYthonDaschBoard (PYDB)](https://github.com/yourusername/PYDB)

![](assets/screenshot.png) image when the code was first published

## 💡 Inspiration and Motivation
The main inspiration for this project is the excellent [PADD](https://github.com/pi-hole/PADD). While PADD is a fantastic tool, I encountered two personal hurdles:

* **Aesthetics**: The original PADD visual style didn't quite fit my preferences.
* **Codebase**: I believe it will be easier to build a new solution from scratch in Python than to try and modify the original Bash-based code, even though I have never used Python before.

---

## 🛠️ What is PYthonDaschBoard?
PYDB is a **terminal-based dashboard**. Unlike the original, it's not just for Pi-hole; it aims to be a universal.

### Supported Services (Planned/Implemented)
* 🛡️ [Pi-hole](https://github.com/pi-hole/pi-hole)
* 🔒 [Unbound](https://github.com/NLnetLabs/unbound)
* 🚫 [AdGuard Home](https://github.com/AdguardTeam/AdGuardHome)
* 📧 [Rspamd](https://github.com/rspamd/rspamd)
* 🖥️ **System Information**: Comprehensive hardware overview (CPU, RAM, Temperatures, Disk usage, and system status).

---

## ⚙️ Technical Stack
* **UI**: I use the [rich](https://github.com/Textualize/rich) library to ensure a clean look within the terminal.
* **Configuration**: All settings are handled via a lightweight **TOML** file. No complex scripts—just edit one file and you're good to go.
