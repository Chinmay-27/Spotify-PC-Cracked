# Spotify-PC-Cracked

# 🎨 Spotify Customization Toolkit (with Spicetify)

This repository documents and simplifies the setup of [Spicetify CLI](https://github.com/spicetify/cli) and [Spicetify Marketplace](https://github.com/spicetify/marketplace) for customizing the Spotify **Windows desktop application**.

> ⚠️ **Disclaimer**  
> This project is for **educational and personal customization purposes only**. It does not support piracy or any activity violating Spotify’s [Terms of Use](https://www.spotify.com/legal/end-user-agreement/). Use responsibly.

---

## 📦 What Is Spicetify?

**Spicetify** is a command-line tool that enables advanced customization of the Spotify client, including themes, extensions, and UI tweaks. You can personalize the appearance and behavior of the app using safe, non-intrusive methods.

---

## 🛠️ Prerequisites

- Windows 10/11
- Spotify Desktop App (from [spotify.com](https://www.spotify.com) — **not the Microsoft Store version**)
- PowerShell

---

## 🚀 Installation Commands

Run these in an **elevated PowerShell (Admin)** terminal:

```powershell
iwr -useb https://raw.githubusercontent.com/spicetify/cli/main/install.ps1 | iex
iwr -useb https://raw.githubusercontent.com/spicetify/marketplace/main/resources/install.ps1 | iex
```

This will install:
- `Spicetify CLI`: the customization engine
- `Spicetify Marketplace`: a graphical interface for managing themes/extensions

---

## 🌈 Example Customizations

Once installed, you can:
- Apply themes (Dark, Onepunch, Fluent, etc.)
- Add extensions (ad muting, lyrics, UI enhancements)
- Backup and restore default Spotify config

To apply changes:
```powershell
spicetify backup apply
```

---

## 🔄 Updating Spicetify

```powershell
spicetify upgrade
spicetify marketplace upgrade
```

---

## 📚 Educational Focus

This repo is for:
- Exploring how PowerShell interacts with third-party tools
- Learning how command-line tools enhance UI personalization
- Understanding customization in a sandboxed, reversible way

---

## 📎 Useful Links

- [Spicetify CLI GitHub](https://github.com/spicetify/cli)
- [Spicetify Marketplace GitHub](https://github.com/spicetify/marketplace)
- [r/Spicetify on Reddit](https://www.reddit.com/r/spicetify/)

---

## 📄 License

This repository contains no original binaries or proprietary code. It wraps open-source tools under their respective licenses. See the `LICENSE` file for more info.
