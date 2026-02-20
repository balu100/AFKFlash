# AFKFlash

AFKFlash is a lightweight notification addon designed to help players manage long queue times in **World of Warcraft**. It alerts you when your character becomes AFK so you can return before being logged out and losing your queue position.

> ⚠️ This addon **does not prevent AFK** and does not automate gameplay. It only provides notifications.

---

## ✨ Features

* 🔔 **Taskbar Flash Notifications**
  Flashes the game client icon when AFK is detected.

* 🪟 **In‑Game Popup Alerts**
  Displays a visible warning window inside the game.

* ⏱ **Pre‑Logout Reminder**
  Sends a follow‑up alert approximately **5–10 minutes** before logout.

* 💬 **Optional Whisper Notifications**
  Configure a character to receive whisper alerts — useful when running multiple clients.

* 🎮 **Minimal & Lightweight**
  No automation, no gameplay interaction, fully compliant with Blizzard addon policies.

---

## 📦 Installation

1. Download or clone this repository.
2. Extract the folder into your WoW Classic AddOns directory:

```
World of Warcraft/_Retail;Classic_/Interface/AddOns/
```

3. Ensure the folder structure looks like:

```
AddOns/
  AFKFlash/
    AFKFlash.toc
    AFKFlash.lua
```

4. Launch the game and enable **AFKFlash** in the AddOns list.

---

## ⚙️ Usage

Use the slash command below to configure the addon:

```
/afkflash
```

Available functionality includes:

* Setting a whisper target for alerts
* Adjusting notification behavior
* Enabling or disabling visual alerts

---

## 🧠 How It Works

AFKFlash monitors the AFK state of your character and triggers notification events:

1. Detects when AFK status activates
2. Flashes the client icon and shows an in‑game popup
3. Sends a second reminder shortly before logout

No input automation or anti‑AFK actions are performed.

---

## ❗ Compliance Notice

Blizzard’s policies prohibit addons that simulate activity or prevent AFK automatically. AFKFlash is strictly a **notification system** and does not attempt to bypass game mechanics.

---

## 🐞 Issues & Contributions

Found a bug or have an idea?

* Open an Issue with clear reproduction steps
* Submit a Pull Request with improvements

---

## Credits
* Original Creator: **dressmachine**
