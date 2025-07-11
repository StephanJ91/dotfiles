# 🏠 Dotfiles Managed by chezmoi

These are my personal dotfiles, managed using [chezmoi](https://www.chezmoi.io), designed for a minimal yet powerful Linux setup with [Hyprland](https://github.com/hyprwm/Hyprland) as my window manager on an Arch-based system.

> ✨ Managed safely and reproducibly across systems using chezmoi

---

## 📦 Included Configs

- 🖥️ **Hyprland** – `~/.config/hypr/`
- 🧊 **Hyprpaper** – `~/.config/hyprpaper.conf`
- 🧾 **Waybar** – `~/.config/waybar/`
- 🔐 **ZSH / Oh-My-Zsh** – `~/.zshrc`, theme and plugins
- 📦 **Wofi** – `~/.config/wofi/`
- 🔔 **Hyprnotify** – `~/.config/hyprnotify/`
- 🌐 **Brave** – custom flags for Wayland
- 🐧 **System configs** – hostname, aliases, tmux, etc.

---

## 🚀 Getting Started (On New Machine)

```bash
# Install chezmoi
sudo pacman -S chezmoi

# Initialize with this repo
chezmoi init --apply yourusername
