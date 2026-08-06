Installation Guide — Xiaomi Mi 11 Lite 4G (courbet)

«[!WARNING]

- Your warranty is void.
- All official release builds are tested and safe to use.
- If you decide to experiment, mess something up, corrupt your storage, turn your phone into a fancy paperweight, or brick it beyond recovery — don't blame us.
- You are doing this at your own risk and take full responsibility for anything that may happen.»

«[!NOTE]

- The device must have an unlocked bootloader and the required recovery.
- Make a full data backup before flashing.
- Ensure your device has at least 30% battery.
- Flash only files meant for Xiaomi Mi 11 Lite 4G (courbet).
- First boot may take 5–10 minutes. Do not interrupt or force reboot unless it exceeds 10 minutes.
- Please make an IMEI backup.»

---

Clean Flash Guide

1. Download the latest axion-*-courbet.zip from the official website.
2. Extract the ROM and obtain the recovery.img.
3. Connect your phone to your PC and reboot into Fastboot Mode by holding Power + Volume Down.
4. Flash the recovery:

fastboot flash recovery recovery.img

5. Reboot into recovery:

fastboot reboot recovery

6. Select Factory Reset.
7. Tap Format Data / Factory Reset and confirm.
8. Select Apply Update → Apply from ADB, then sideload the ROM:

adb sideload axion-*-courbet.zip

9. If you have additional packages (e.g. GApps), choose Yes to reboot back into recovery after sideloading. Otherwise choose No.
10. Perform Factory Reset → Format Data / Factory Reset once more.
11. Select Reboot System Now.

---

Dirty Flash (OTA Update)

«[!NOTE]

- Dirty flash preserves your data.
- Not supported for major Android upgrades (e.g. Android 15 → Android 16).»

OTA Update

1. Go to Settings → System → System Update.
2. Download the latest update.
3. Tap Reboot.
4. The device will reboot into recovery and install the update automatically.
5. Once completed, reboot into the system.

---

Local Update

1. Download the latest update package.
2. Open Settings → System → System Update.
3. Tap Local Update / Select Package.
4. Select the downloaded ZIP file.
5. Confirm and tap Reboot.

---

Notes

«[!IMPORTANT]

- First boot may take 5–10 minutes.
- Do not interrupt the installation process.
- Always use the latest recommended firmware before flashing.
- Report reproducible issues with proper logs (logcat and dmesg).»
