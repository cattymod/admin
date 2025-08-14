# 🐾 CattyAdmin Panel

**CattyAdmin Panel** is a lightweight, open-source admin tool for Scratch projects.  
It uses **Scratch cloud variables** to let approved admins send commands such as:

- **Shutdown** — Disable your Scratch project remotely.
- **Shutdown Notice (Alert)** — Send a warning message before shutdown.
- **Remove Changes** — Undo changes or reset variables.

No servers required — works entirely locally via Scratch cloud variables.

---

## ⚠️ Important Notice
CattyAdmin **does NOT work for New Scratchers**.  
It will **not** be able to send or receive requests unless your Scratch account has full cloud variable access.

---

## 📥 Download

[⬇️ Download the CattyAdmin Panel Sprite](https://github.com/cattymod/admin/raw/refs/heads/main/Admin.sprite3)

---

## 📦 Installation & Setup

1. **Download** the CattyAdmin Panel sprite from the link above.
2. **Upload** the sprite into your Scratch project.
3. **Add Admins**: The sprite comes with a built-in script that controls who can use admin commands.  
   Example script format:

---
   
   **Add (Noahscratch493) to [Admins v]**
   
   **Add (username2) to [Admins v]**
   
   **Add (username3) to [Admins v]**

---
Replace `(username)` with the exact Scratch username you want to grant admin access.

---

## 💡 How It Works

CattyAdmin listens for cloud variable updates from approved admin accounts.
When an approved admin sends a command, the sprite executes the corresponding action inside your Scratch project.

---

## 📜 License

CattyAdmin Panel is released under the [MIT License](LICENSE).
You are free to use, modify, and share it — attribution appreciated!

---

🐾 **Made with love by The CattyMod Team**
