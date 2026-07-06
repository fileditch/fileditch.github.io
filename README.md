# 📁 FileDitch (alternative front-end)

super cool, unlimited, ad-free, high-speed, anonymous file hosting.

built entirely with vanilla web technologies with zero frameworks, zero external tracking scripts, and no account requirements.

![License](https://img.shields.io/badge/License-MIT-emerald?style=flat-square)
![Dependencies](https://img.shields.io/badge/Dependencies-Zero-lightgrey?style=flat-square)

<img width="1920" height="1590" alt="FileDitch Minimalist Frontend Screenshot" src="https://github.com/user-attachments/assets/d0a430da-48a7-4401-99e8-d8c13fbee5e1" />

---

## 🚀 features

* **👤 no sign-ups or accounts**
* **💾 file viewer** view media without downlaoding it
* **🚫 100% ad-free:** hides ads from the original site using a lightweight proxy.
* **📂 folder sharing:** full folder upload and sharing (not supported on the original site).
* **⚡ high-speed:** unlimited uploads (max 100gb per file) and high download speeds.
* **🔒 privacy:** no trackers or analytics scripts, and open-source.
* **⏳ optional temporal hosting:** deleted after 72h
* **🖼️ minimalistic design**
* **💲 free forever**

---

## 🛠️ how it works

while FileDitch offers a backend API for hosting files, their native frontend has a lot of ads and pop-ups. normally, when you share a link, the recipient must open pop-ups or look at (sometimes nsfw) ads to access the file.

this alternative frontend uses a **cloudflare workers proxy**. 
1. when a user requests a file, the proxy intercepts the standard link.
2. it fetches the temporary direct download link.
3. it gives the direct file link directly to the user **removing all trackers, pop-ups, and advertisements.**

---

## ⚠️ disclaimer

This project is an **unofficial alternative frontend** to the original [FileDitch](https://new.fileditch.com). 

please remember that the original creator solely pays for the server infrastructure. if you enjoy using this platform, consider supporting them directly to help keep the servers running:
* **email:** [info@fileditch.com](mailto:info@fileditch.com)
* **discord:** [join the discord](https://discord.gg/gACnap5kKx)

---

## 🔒 blocked filetypes

to ensure the safety of the platform and its users, executable files and scripts are blocked from being uploaded:

> **blocked filetypes:** `php`, `html`, `htm`, `js`, `exe`, `apk`, `sh`, `py`, `bat`, `cmd`, `msi`, `vbs`, `scr`, `cpl`, etc.

standard media, document, and archive formats are fully supported. to share a blocked filetype, try to create a folder where this file is in then zip it and share the zipped folder.

---

## 📄 license

This project is open-source and available under the [MIT License](LICENSE).
