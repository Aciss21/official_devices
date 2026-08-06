# Installation Guide — Xiaomi Mi 11 Lite 4G (courbet)

## ⚠️ Warning

- Your warranty is void.
- All official release builds are tested and safe to use.
- If you decide to experiment, mess something up, corrupt your storage, turn your phone into a fancy paperweight, or brick it beyond recovery — **don't blame us**.
- You are doing this at **your own risk**.

## 📝 Requirements

- Unlocked bootloader.
- Latest Axion Recovery.
- Backup all your data.
- At least 30% battery.
- Flash only builds for **courbet**.

---

## Clean Flash

1. Download the latest **axion-*-courbet.zip**.
2. Extract the ROM and obtain **recovery.img**.
3. Boot into Fastboot Mode.

```bash
fastboot flash recovery recovery.img
fastboot reboot recovery
```

4. Select **Factory Reset**.
5. Choose **Format Data / Factory Reset**.
6. Select **Apply Update → Apply from ADB**.

```bash
adb sideload axion-*-courbet.zip
```

7. If flashing additional packages, reboot back to recovery.
8. Format Data once again.
9. Reboot System.

---

## Dirty Flash (OTA)

1. Settings → System → System Update.
2. Download the latest build.
3. Reboot.
4. Wait for installation to finish.

---

## Local Update

1. Download the latest update package.
2. Settings → System → System Update.
3. Select **Local Update**.
4. Choose the ZIP.
5. Reboot.

---

## ℹ️ Notes

- First boot may take **5–10 minutes**.
- Always use the latest firmware.
- Report bugs with proper logs.
