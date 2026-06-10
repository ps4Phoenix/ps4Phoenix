# ps4Phoenix Enhanced Host
Based on PSFree version 1.5.1

**ps4Phoenix** is a highly stable, mirrored, and enhanced web exploit host for the PlayStation 4 console. It utilizes the modern **PSFree** WebKit exploit combined with the **Lapse** kernel exploit to trigger GoldHEN and payload loading entirely **without the need for a USB drive (No USB Required)**.

## 🚀 Live Host (PS4 Browser Link)
Open your PS4 Web Browser and navigate to:
> **`https://YOUR_GITHUB_USERNAME.github.io/ps4Phoenix/`**

*(Note: Replace `YOUR_GITHUB_USERNAME` with your actual GitHub username).*

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
- Offers more features when hosted locally on a PC or a PS4 using [PS4-Websrv](https://github.com/ArabPixel/ps4-websrv)
  - Send payloads from any smart device to the PS4.
  - Scans the local network to locate your PS4.

---

## 📅 Supported Firmwares by ps4Phoenix

This table indicates firmware versions for which the _current version_ of this repository provides a functional and tested exploit chain.

| Device | PSFree (WebKit) | Lapse (Kernel) | GoldHEN's PayLoader |
| :--- | :--- | :--- | :--- |
| **PlayStation 4** | 7.00 - 9.60 | 7.00 - 9.60 | 7.00 - Latest |

---

## 📝 TODO List

- [x] ~~Blackscreen/Save issue with certain games~~ *Issue is patched post-exploit*
- [ ] Determine root cause of memory panics and fix more directly.
- [ ] `lapse.mjs`: Just set the bits for JIT privileges.
- [ ] `view.mjs`: Support PS5 firmware structures.

---

## 👥 Contribution & Credits

Feel free to open a Pull Request (PR) to improve the host by modifying, updating, or adding new features!

### Credits:
- **Sleirsgoevy & ChendoChap:** For the original revolutionary PSFree implementation.
- **ArabPixel:** For the original Enhanced repository code structure.
- **Nazky:** For code and workflow inspirations.
- **Feyzee61:** For the second PSFree lapse kernel implementation.
- **Anonymous:** For PS4 firmware kernel dumps.

---

## 📄 Copyright and License
This project is licensed under the AGPL-3.0-or-later. Part of this repository belongs to the group `anonymous`.
