# QuickBars for Home Assistant • Home Assistant Blueprints (Scripts)

> **Requires QuickBars for Home Assistant v1.3+** (Android/Google TV)

This repo provides script blueprints to add useful automations and enhance the experience of the QuickBars TV app, directly from Home Assistant:

- **TV Notification** – rich banner (title/message), optional MDI icon, image, sound, action buttons, color/opacity, position, duration, target by App ID.
- **Camera PiP** – show a camera via entity/alias/RTSP, pick size/position, auto-hide, optional title, mute (RTSP), optional toast pop-up, and App ID targeting.
- **QuickBar Toggle** – open/close a configured QuickBar by alias, optionally targeting a specific TV App ID.

---

## 📖 Guide & Docs

- **Official setup & usage guide:** https://quickbars.app/guide  
  (Includes onboarding, permissions, persistent background connection, and tips.)

---

## ⬇️ Import

Click a button below, or paste the raw URL into **Settings → Automations & Scenes → Blueprints → Import Blueprint**.

**TV Notifications** 

[![Import](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FTrooped%2Fquickbars-blueprints%2Fblob%2Fmain%2Fnotification.yaml)

**Camera PiP**  

[![Import](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FTrooped%2Fquickbars-blueprints%2Fblob%2Fmain%2Fcamera.yaml)

**QuickBar Toggle**  

[![Import](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FTrooped%2Fquickbars-blueprints%2Fblob%2Fmain%2Fquickbar.yaml)

**Raw URLs (copy/paste):**

https://github.com/Trooped/quickbars-blueprints/blob/main/camera.yaml

https://github.com/Trooped/quickbars-blueprints/blob/main/notification.yaml

https://github.com/Trooped/quickbars-blueprints/blob/main/quickbar.yaml

> After importing, go to **Scripts**, click **Create from blueprint**, choose the QuickBars blueprint, and fill in the fields.  
> If scripts don’t show immediately, go to **Developer Tools → YAML → Reload Scripts**.

## ✅ Requirements

- **QuickBars TV app v1.3+** installed on the Android/Google TV.
- In the TV app: **Accessibility**, **Display over other apps**, and **Persistent background connection** enabled.
- A reachable Home Assistant URL (local IP or HTTPS remote).  
- For **Camera & Notification blueprints**: Home Assistant **2024.6+**.

---
