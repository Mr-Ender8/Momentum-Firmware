# Momentum Firmware  
🐬 Feature-rich, stable and customizable Flipper Firmware with admen mode and update reminders

## Grey's Custom Admin Mode (Customizable on First Flash)
- **Customizable on first flash**: Configure button sequence, password, hint, and app locking options.
- To enter Admin Mode: Hold **OK** > 3 seconds → enter configured button code sequence → enter strong keyboard-style admin password (example: PASSWORD123!).
- Device always starts in safe **Regular Mode** (limited high-risk tools).
- Admin Mode unlocks full tools for safe PIN Testing on your own devices only.
- Automatically exits after 5 minutes inactivity or power off.
- Optional password hint available.

## App Locking / Unlocking (Admin Mode Only)
- In Admin Mode: Go to Settings > Apps to lock or unlock specific apps and features.
- Locked apps are hidden or restricted in Regular Mode.

## BadUSB / Keyboard Injection
- Full access available in Regular Mode (restrictions lifted).
- Use **only on your own devices** for educational purposes.

## Sub-GHz, Rolling Code & Other Features
- Regular Mode: Basic functions only.
- Admin Mode: Full access (advanced transmission, raw replay, rolling code send/save — legal frequencies only).

## Update Reminder
- Fully customizable and toggleable in Settings (daily/weekly/on/off).

## Preserving U2F Keys and All Data
- U2F keys stored on the microSD card in the `/u2f` folder.
- Always perform a full backup before flashing: Settings > Storage > Backup, then copy entire microSD to computer.

This fork is designed for safe, responsible learning. Use only on your own devices and legal frequencies.