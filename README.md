# 📺 Display Auto-Configurator with xrandr

This project is a **dynamic display configuration utility** built around `xrandr` for X11 environments. It **automatically detects current and newly connected displays**, and **applies predefined or customizable settings** such as resolution, refresh rate, orientation, and more.

## 🔧 Features

- ✅ **Automatic detection** of connected and newly added displays  
- ⚙️ **Per-display configuration**: resolution, refresh rate, orientation, etc.  
- 📌 **App pinning** (optional): assign and stick specific apps to specific desktops or monitors  
- 🔁 **Hotplug support**: react to display plug/unplug events in real time  
- 🧠 Designed to be **modular and extensible**

## 💡 Use Case

This tool is ideal if you:

- Regularly switch between multiple display setups (e.g., laptop + external monitor)
- Want precise control over monitor behavior without manually invoking `xrandr`
- Need certain apps (like browsers, IDEs, or terminals) to always launch on a specific display or workspace

## 🖥️ Example

1. You plug in a new monitor.  
2. The script detects it automatically.  
3. It applies the desired resolution and refresh rate.  
4. Your terminal opens on the laptop display, your browser launches on the external monitor.

## 🚀 Getting Started

Coming soon: installation, setup, and configuration instructions.

## 📂 Structure

- `config/` — store per-display configuration (resolution, rate, layout, etc.)
- `scripts/` — detection and application logic
- `apps/` — rules for pinning or launching apps on specific displays/desktops

## 🛠 Dependencies

- `xrandr`
- `xprop`, `wmctrl` (for app pinning)
- `bash` or `python` (depending on implementation)
