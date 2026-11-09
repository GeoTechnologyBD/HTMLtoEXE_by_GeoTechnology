<div align="center">

# 🚀 HTML to Native EXE Builder

**Transform your web projects into powerful, standalone Windows applications.**

[![Version](https://img.shields.io/badge/Version-1.0.0-blue.svg?style=for-the-badge)](https://geotech.site.je)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-0078D6.svg?style=for-the-badge&logo=windows)](https://geotech.site.je)
[![Company](https://img.shields.io/badge/Company-GeoTechnology-orange.svg?style=for-the-badge)](https://geotech.site.je)
[![License](https://img.shields.io/badge/License-Proprietary-red.svg?style=for-the-badge)](https://geotech.site.je)
[![Founder](https://img.shields.io/badge/Founder-Abdullah%20Al%20Mahdi-green.svg?style=for-the-badge)](https://geotech.site.je)

*Developed with ❤️ by GeoTechnology | Released on November 9, 2026*

</div>

---

## 📖 Table of Contents
- [About the Software](#-about-the-software)
- [Key Features](#-key-features)
- [How It Works](#-how-it-works)
- [System Requirements](#-system-requirements)
- [Installation Guide](#-installation-guide)
- [How to Use (Step-by-Step)](#-how-to-use-step-by-step)
- [Build Modes Explained](#-build-modes-explained)
- [Troubleshooting & FAQ](#-troubleshooting--faq)
- [License & Terms](#-license--terms)
- [Contact & Support](#-contact--support)

---

## 🌟 About the Software

**HTML to Native EXE Builder** is a cutting-edge, lightweight software developed by **GeoTechnology**. It is designed to seamlessly convert your HTML5, CSS3, and JavaScript web projects into standalone, native Windows Executable (`.exe`) files.

Unlike traditional tools like Electron or PyInstaller (which bundle heavy Python/Node.js runtimes), this builder utilizes Microsoft's **WebView2 engine** and the **native C# compiler**. This ensures your final EXE runs natively, features lightning-fast startup times, and requires **zero third-party frameworks** installed on the end-user's computer.

---

## ✨ Key Features

| Feature | Description |
| :--- | :--- |
| 📦 **Single File EXE** | Embed all your HTML, CSS, JS, images, and audio directly into one `.exe` file. |
| 📁 **External Folder Mode** | Keep your web assets in an external `www` folder for easy debugging and real-time modification. |
| 🎨 **Custom Icons** | Personalize your application with any `.ico` file. (Falls back to a clean default icon). |
| ⚡ **Native Performance** | Built on the same rendering engine as Microsoft Edge, ensuring modern web support and high FPS. |
| 🐍 **No Python Required** | The final EXE is a pure Windows application. End-users do not need Python or any other software. |
| 🛡️ **Portable & Safe** | Generates fast-starting applications. Data and cookies are securely stored in `AppData`. |

---

## ⚙️ How It Works

1. **Select Assets:** Choose your `index.html` or the entire project folder.
2. **Configure:** Set the App Name and Icon.
3. **Build:** The software compiles your assets using the Windows native `csc.exe` compiler.
4. **Distribute:** Share the generated `.exe` file with anyone!

---

## 💻 System Requirements

### For the Builder (Developer's PC)
> *These are the requirements to run the Builder software.*

- **OS:** Windows 10 or Windows 11 (64-bit recommended)
- **RAM:** 2 GB or higher
- **Storage:** 50 MB of free space
- **Framework:** .NET Framework 4.8 (Pre-installed on modern Windows)
- **Internet:** Required *only* for the first build (to download WebView2 DLLs).

### For the Final App (End-User's PC)
> *These are the requirements for the EXE you create.*

- **OS:** Windows 10 (Version 1903 and above) or Windows 11
- **Runtime:** Microsoft Edge WebView2 Runtime (Pre-installed on modern Windows PCs).
- **RAM:** 2 GB or higher

---

## 🛠️ Installation Guide

1. **Download:** Obtain the `HTMLtoEXE_v1.0.0_setup.exe` from [here](https://github.com/GeoTechnologyBD/HTMLtoEXE_by_GeoTechnology/tree/main/HTMLtoEXE_v1.0.0) or from [our website](https://geotech.site.je/product/software/windows/html_to_exe_by_geotechnology_v1.0.0).
2. **Run:** Double-click the installer. Allow Administrator privileges if prompted (UAC).
3. **Agree:** Read and accept the End-User License Agreement (EULA).
4. **Install:** Choose your destination folder (Default: `C:\Program Files (x86)\GeoTechnology\HTML to Native EXE Builder\`).
5. **Launch:** Check the "Launch" box and click Finish.

---

## 🚀 How to Use (Step-by-Step)

1. **HTML File or Folder:**
   - Click **File** for a single `.html` file.
   - Click **Folder** for a project with CSS/JS. *(Ensure the main file is named `index.html`)*.
2. **App Name:** Enter the desired name for your application (e.g., `SpaceBlaster`).
3. **App Icon:** Click **Browse** to select a `.ico` file.
4. **Output Folder:** Choose where the final `.exe` will be saved.
5. **Embed Mode:** Leave the checkbox checked to create a Single EXE.
6. **Build:** Click **⚙ Build EXE** and wait for the success message!

---

## 📦 Build Modes Explained

| Mode | How it works | Best for... |
| :--- | :--- | :--- |
| **Single EXE**<br>*(Checked)* | Compresses all your web assets into a `.zip` and hides it inside the `.exe`. Extracts to `AppData` temporarily when run. | Distributing your app to end-users. (Clean and professional). |
| **External Folder**<br>*(Unchecked)* | Creates the `.exe` alongside a `www` folder containing your HTML/CSS/JS files. | Development and debugging. (You can edit files without rebuilding). |

---

## ❓ Troubleshooting & FAQ

<details>
<summary><b>Q: My antivirus flags the generated EXE as a virus. Why?</b></summary>
<br>
This is a common "False Positive" for self-extracting executables (because the EXE unpacks files during runtime). Since you built the EXE locally using your own HTML files, it is 100% safe. You may need to add it to your antivirus exclusion list.
</details>

<details>
<summary><b>Q: The app crashes or shows an error on startup?</b></summary>
<br>
The target PC might be missing the "WebView2 Runtime". It is pre-installed on Windows 10 and 11. If missing, download it from the <a href="https://developer.microsoft.com/en-us/microsoft-edge/webview2/">Microsoft Official Website</a>.
</details>

<details>
<summary><b>Q: The window opens but shows a blank screen?</b></summary>
<br>
Ensure your main HTML file is named exactly <code>index.html</code> and all file paths (for images/CSS) are relative (e.g., <code>./style.css</code>), not absolute (e.g., <code>C:\folder\style.css</code>).
</details>

---

## ⚖️ License & Terms

**Copyright (c) 2026 GeoTechnology. All rights reserved.**

This software is licensed, not sold. 
- You **may** use this software to build and distribute your own personal or commercial applications.
- You **may not** reverse engineer, decompile, or resell the Builder software itself.

For the full End-User License Agreement, please refer to the `license.rtf` provided during installation.

---

## 📞 Contact & Support

Need help, found a bug, or want to say hi? We'd love to hear from you!

- 🌐 **Website:** [https://geotech.site.je](https://geotech.site.je)
- 👨‍💻 **Founder:** Abdullah Al Mahdi
- 🏢 **Company:** GeoTechnology

<div align="center">
  <br>
  <i>Building the future, one app at a time.</i><br>
  <b>GeoTechnology © 2026</b>
</div>
