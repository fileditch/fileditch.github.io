# FileDitch

An ad-free, minimalist, and lightweight website for high-speed, **100 GB anonymous file hosting**.

Built entirely with vanilla web technologies (HTML5, CSS3, JS) with zero frameworks, zero external tracking scripts, and no account requirements.

![UI Aesthetic](https://img.shields.io/badge/Aesthetic-Brutalist%20%2F%20Minimalist-7e73ff?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-emerald?style=flat-square)
![Dependencies](https://img.shields.io/badge/Dependencies-Zero-lightgrey?style=flat-square)

---

## 🚀 Features

### 📦 Anonymous Hosting
No registration, no accounts, and no paywalls. Just drag and drop your files, copy the link, and you're good to go.

### ⚡ Direct Media Streaming
* **Link Extraction:** Automatically resolves temporary or indirect URLs (`fileditchfiles.me/file.php?f=...`) into clean, usable links.
* **CORS Proxy:** Routes requests through a proxy worker to fetch direct links without hitting CORS restrictions.

---

## 🔒 Blocked Filetypes

We support almost all standard media formats. To keep the platform and its users safe, executables and scripts are blocked:

> `php`, `html`, `htm`, `js`, `exe`, `apk`, `sh`, `py`, `bat`, `cmd`, `msi`, `vbs`, `scr`, `cpl`, etc.
