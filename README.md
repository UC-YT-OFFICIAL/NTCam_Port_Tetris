# NtCam Port

Nothing Camera (16.1.00.93.20) with the Nothing **NtCam camera HAL**, ported to
**CMF Phone 1 (Tetris)** custom ROMs as a KernelSU module.

DISCLAIMER

- Nothingâ„¢ and Nothing Camera are owned by Nothing Technology Limited.
- This project is an unofficial port and is not affiliated with or endorsed by Nothing Technology Limited.
- The project license applies to the port/module only, not to Nothing's proprietary apps, HAL, blobs, or trademarks.

- 
**Download:** latest module on the [Releases](../../releases/latest) page.

---

## Tester Guide

### Requirements

- **Root:** KernelSU / KernelSU Next / SukiSU Ultra, etc.
- **Meta Module:** Required
  - Recommended: **Hybrid Mount** (Mode: Default â€“ OverlayFS) âœ…

### Installation

1. Flash the Meta Module and reboot.
2. Flash the NtCam Port module and reboot.
3. Open your root manager and grant root access to **Nothing Camera** (`com.nothing.camera`).
4. Open the camera. Setup complete.

ðŸ¥° Thanks for testing and supporting the project!

### FAQ

**1. Camera app not listed in the root manager**
â†’ The module is not mounting on your ROM. Make sure the Meta Module is installed,
enabled, and you rebooted after flashing.

**2. Camera app is listed but does not open**
â†’ Grant root access to Nothing Camera, then reopen it.

**3. Root granted, but the camera still won't open or crashes**
â†’ Send a crash log (steps below).

### How to send a crash log

1. Install **LogFox** and grant it root access.
2. Open LogFox in **Root mode**.
3. Open the camera. When it crashes, LogFox shows the crash log in a notification.
4. Copy the full log and send it to the developer, along with your **ROM name** and **root manager**.

---

## Credits

**Port by:** @UCYTOFFICIAL Â· @CyberZaki

Finally, I successfully ported the Nothing Camera APK + Camera HAL to Tetris Custom ROM,
with the valuable contributions and support of many members. â¤ï¸

A huge â¤ï¸ thank you to everyone who contributed to this project and supported the porting process.

**Special thanks to these members for providing important logs and files from the stock ROM
while I was porting the Nothing Camera APK:**

- @iconic_67
- @RahulSinghBhadoriya
- @O_Block_6_3_rd
- @AnshumanAhirwar

**Special thanks to these members for helping with testing during the Nothing "MTK Camera HAL" port:**

- @N1TESHHHH
- @iconic_67
- @MythicEditz

**And thank you to everyone who supported the project and motivated me with your positive reactions:**

- @funnysky943
- @hermitclaw
- @Yourtathagata12
- @velocity0p
- @Life_sucks090
- @RahulSinghBhadoriya

Really appreciate everyone's support, testing, logs, files, and feedback throughout the development. â¤ï¸
