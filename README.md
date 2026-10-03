# NtCam Port

Nothing Camera **16.1.00.93.20**, including the Nothing **NtCam Camera HAL**, ported for **CMF Phone 1 (Tetris)** custom ROMs and distributed as a **KernelSU module**.

> **Unofficial community port for Tetris-based custom ROMs.**

---

## Disclaimer

- **Nothing™** and **Nothing Camera** are trademarks and proprietary products of **Nothing Technology Limited**.
- This project is an **unofficial community port** and is **not affiliated with, endorsed by, sponsored by, or otherwise associated with Nothing Technology Limited**.
- The **Nothing Camera application, Camera HAL, proprietary libraries, blobs, and related components remain the property of their respective owners**.
- This repository does **not** claim ownership of or grant rights to any proprietary Nothing software, trademarks, or copyrighted components included in the port.
- The project and its module files are provided for development, testing, and community use on supported devices and ROMs.

---

## Download

Download the latest available module from the **[Releases](../../releases/latest)** page.

---

# Tester Guide

## Requirements

### Root Access

A supported root solution is required:

- **KernelSU**
- **KernelSU Next**
- **SukiSU Ultra**
- Other compatible KernelSU-based root solutions

### Meta Module

A **Meta Module** is required for mounting the port correctly.

**Recommended:**

- **Hybrid Mount**
- Mount Mode: **Default – OverlayFS**
- Ksu User - Disable It - Unmount Module By Default .
---

## Installation
#ksu/ksunext/sukisu-ultra/Apatch - Disable (Mount module by default)
1. Install the required **Meta Module**.
2. Reboot your device.
3. Flash the **NtCam Port** module.
4. Reboot again.
5. Open your root manager and grant root access to **Nothing Camera**:
   `com.nothing.camera`
6. Launch the camera application.

The setup is complete.

> 🥰 Thank you for testing and supporting the project!

---

# Frequently Asked Questions

### 1. Nothing Camera does not appear in the root manager

This usually indicates that the module is not being mounted correctly on your ROM.

Make sure that:

- The required Meta Module is installed.
- The Meta Module is enabled.
- You have rebooted after installing or enabling the modules.

---

### 2. Nothing Camera appears in the root manager but does not open

Grant root access to:

`com.nothing.camera`

After granting access, reopen the camera application.

---

### 3. Root access is granted, but the camera still crashes or refuses to open

Please provide a complete crash log so the issue can be investigated.

Follow the crash-log procedure below.

---

# Crash Log / Bug Reporting

When reporting a crash or compatibility issue, please provide:

- The **complete crash log**
- Your **ROM name and version**
- Your **root manager and version**
- Your **Android version**
- Your **device information**

### How to Capture a Crash Log

1. Install **LogFox**.
2. Grant LogFox root access.
3. Open LogFox in **Root mode**.
4. Launch **Nothing Camera**.
5. Reproduce the crash or issue.
6. When the camera crashes, LogFox will provide the crash log.
7. Copy the **complete log** and send it along with your ROM and root-manager information.

> Please avoid sending shortened or incomplete logs whenever possible. Full logs make debugging significantly easier.

---

# Credits

## Port Maintainers

**Port by:**

- **@UCYTOFFICIAL**
- **@CyberZaki**

The Nothing Camera APK and Camera HAL were ported to **Tetris-based custom ROMs** with contributions, testing, logs, files, and feedback from multiple members of the community.

---

## Special Thanks — Stock ROM Resources

Special thanks to the following members for providing important logs and files from the stock ROM during the Nothing Camera porting process:

- **@iconic_67**
- **@RahulSinghBhadoriya**
- **@O_Block_6_3_rd**
- **@AnshumanAhirwar**

---

## Special Thanks — Testing

Special thanks to the following members for helping with testing during the **Nothing MTK Camera HAL** port:

- **@N1TESHHHH**
- **@iconic_67**
- **@MythicEditz**

---

## Community Support

A sincere thank you to everyone who supported the project, provided feedback, shared testing results, and helped motivate further development:

- **@funnysky943**
- **@hermitclaw**
- **@Yourtathagata12**
- **@velocity0p**
- **@Life-sucks090**
- **@RahulSinghBhadoriya**

---

## Acknowledgements

This project would not have been possible without the contributions of everyone who provided:

- Stock ROM files and proprietary resources
- Debugging and crash logs
- Compatibility testing
- Technical feedback
- Development support
- Community feedback and encouragement

Thank you to everyone who contributed to the development and testing of the **NtCam Port**. ❤️

---

## Project Status

This project is intended for **testing and community development** on supported **CMF Phone 1 (Tetris)** custom ROMs.

Compatibility may vary between ROMs, kernels, root solutions, and system configurations.
