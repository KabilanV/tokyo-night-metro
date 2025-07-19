# tokyo-night-metro
A beautiful, minimal PowerShell theme for Windows Terminal

Inspired by the aesthetics of a theme in **btop** by @aristocratos.

This theme applies Tokyo Night’s elegant dark tones and vibrant accents to PowerShell using Windows Terminal's color scheme system.

---

## 🎨 Preview

<img width="610" height="464" alt="image" src="https://github.com/user-attachments/assets/fd45876a-7009-48c0-94e4-e1568bab9bea" />

---

## 🚀 Installation

### 1. Open Windows Terminal 

- Press `Ctrl + ,` in Windows Terminal
- Click on the **“Open JSON file”** ⚙️button

### 2. Add the Color Scheme

- Inside the `"schemes"` array, paste the contents of tokyo-night-metro.json

### 3. Save & Restart Terminal

--- 

## ⚙️ If using Powerlevel10k (Optional)

To match the theme and ensure your **Powerlevel10k** prompt folder path text is clean and consistent, add the following lines to your `~/.p10k.zsh` file:

```zsh
# Set all directory path text colors to black
typeset -g POWERLEVEL9K_DIR_FOREGROUND=0
typeset -g POWERLEVEL9K_DIR_SHORTENED_FOREGROUND=0
typeset -g POWERLEVEL9K_DIR_ANCHOR_FOREGROUND=0
