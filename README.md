# ps4Phoenix Host
Based on PSFree version 1.5.1

**ps4Phoenix** is a highly stable and mirrored web exploit host for the PlayStation 4 console. It utilizes the modern **PSFree** WebKit exploit combined with the **Lapse** kernel exploit to trigger GoldHEN and payload loading entirely **without the need for a USB drive (No USB Required)**.

## 🚀 Live Host (PS4 Browser Link)
Open your PS4 Web Browser and navigate to your GitHub Pages link once activated.

---

## ✨ Features

- **Auto-detection:** Automatically detects console type and firmware version (via `src/config.mjs`).
- **WebKit Exploit (PSFree):** Modern high-success-rate entry point via the console's web browser.
- **Kernel Exploit (Lapse):** Escalates privileges to kernel level smoothly on 9.00.
- **Payload Loader:** After successful kernel exploitation, it listens for payloads on port 9020.
- **Full Offline Cache Support:** Once loaded 100%, you can use the host completely offline without internet.

## 🛠️ Additional Custom Features
- Language switcher.
- HEN flavor selector.
- GoldHEN version selector (Up to date with v2.4b18).
- Descriptive payload selection.
- Unsupported payload loading protection.

---

## 📅 Supported Firmwares by ps4Phoenix

This table indicates firmware versions for which the _current version_ of this repository provides a functional and tested exploit chain.

| Device | PSFree (WebKit) | Lapse (Kernel) | GoldHEN's PayLoader |
| :--- | :--- | :--- | :--- |
| **PlayStation 4** | 7.00 - 9.60 | 7.00 - 9.60 | 7.00 - Latest |

---

## 👥 Credits:
- **Sleirsgoevy & ChendoChap:** For the original revolutionary PSFree implementation.
- **ArabPixel:** For the original repository code structure.
- **Nazky & Feyzee61**
