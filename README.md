# FileDitch Host & Multi-Media Streamer

A dark-themed, minimalist, completely bloated-free single-file application combining high-speed **100 GB anonymous file hosting** with an instant, direct **multi-media bypass streaming player**. 

Built entirely with standard vanilla Web API stacks (HTML5, CSS3, JavaScript) with no heavy frameworks, no external runtime scripts, and zero account requirements.

![UI Aesthetic](https://img.shields.io/badge/Aesthetic-Brutalist%20%2F%20Minimalist-7e73ff?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-emerald?style=flat-square)
![Dependencies](https://img.shields.io/badge/Dependencies-Zero-lightgrey?style=flat-square)

---

## 🚀 Key Features

### 📦 Anonymous File Uploader
* **Massive File Capacity:** Upload individual assets up to **100 GB** in size.
* **XHR Upload Monitor:** Real-time upload queue tracker displaying true percentage values, network velocities, and dynamic ETA counters.
* **Flexible Transfer Modes:** Switch instantly between standard `Multipart Form-Data` envelopes and raw `Body Binary Stream` transfers.
* **Session Memory Queue:** Keeps a localized list of successfully completed files via browser storage, offering integrated image and audio element previews directly inside the user log panel.
* **Automated Clear Options:** Set standard queue rules to retain layout elements or automate removals (immediately or on a 5-second decay).

### ⚡ Direct Multi-Media Link Streamer
* **Temporary Token Bypass:** Takes temporary/indirect links (`fileditchfiles.me/file.php?f=...`) and handles extraction dynamically.
* **Worker Routing Proxy:** Calls a specialized proxy worker to retrieve target layout code safely from the client browser without cross-origin configuration issues.
* **Robust Entity Resolving:** Built-in string parser that seamlessly repairs broken encoding maps and nested components (converting `&amp;` -> `&`, `&#39;` -> `'`, etc.) to prevent dynamic token truncated errors on special-character file names.
* **Smart Contextual Rendering Engine:** Identifies target files on the parsed streams and matches them against native media slots:
  * 🎵 **Audio:** Native audio stream component with global pause handling.
  * 🎬 **Video:** Responsive inline hardware-accelerated video wrapper.
  * 🖼️ **Images:** High-contrast responsive rendering viewport.
  * 📄 **Documents:** Sandboxed container for seamless rendering of PDFs, logs, JSON maps, and plaintext.
  * 📦 **Archives & Fallbacks:** Automatically defaults to a stylized prompt panel with structural asset data downlinks for unknown extensions or archives.

---

## 🔒 Extension Enforcement Rules

Most standard media formats are completely accepted. To maintain client and server security, runtime or executable file extensions are strictly handled:
* **Blocked Upload Formats:** System directly filters dangerous local variants before initiating requests: `php`, `html`, `htm`, `js`, `exe`, `apk`, `sh`, `py`, `bat`, `cmd`, `msi`, `vbs`, `scr`, `cpl`, etc.
* **Post-Parse Guard:** The Streamer runs automated background evaluation rules *after link extraction*. If a dynamic redirection resolves into an unexpected script variant, the execution container will automatically break and display an explicit error state to the user.

---

## 🛠️ Installation & Usage

Because the app is compiled as a standalone static structure, installation requires no node builds, server setups, or extra dependencies:

1. Clone or download this repository.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
3. **To Host:** Drop any file under 100 GB onto the target interactive bounding container.
4. **To Stream:** Paste any valid indirect Fileditch reference link into the module box and hit **Stream & Preview File**.

---

## 📡 Architecture Behind the Bypass Engine
