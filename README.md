# 📦 termux-starship-preset
A minimal prompt preset for Starship in Termux. Focus: simple, fast, and clean.

## ✨ Preview

![Preview](./view/preview.jpg)

---

## ❕️ Prerequisites
- A [__Nerd Font__](https://www.nerdfonts.com/font-downloads) installed and enabled in your terminal

## ⚙️ Installation
- `apt update && apt upgrade -y`
- `apt install git starship -y`
- `git clone https://github.com/ZeltNamizake/termux-starship-preset`
- `ce termux-starship-preset && chmod +x set`
- `./set`

## 🚀 Usage
```plaintext
Usage:
  ./set <preset>        # change presets
  ./set <bash|zsh>      # change default shell
Preset:
 - monoline     - pzhline (zsh)
 - miniline
 - customline
 - ghline
Shell (current):
 - zsh
 - bash  [active]
Example:
 - ./set pzhline
 - ./set zsh
```

---

## Notes
- optimized for right-side layout (best on zsh)
- bash support: partial display
