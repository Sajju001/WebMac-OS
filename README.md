# 🖥️ WebMac OS

**A desktop experience, inside your browser.**

WebMac OS is a modern, interactive **browser-based desktop operating system simulator** inspired by the clean and premium design language of modern desktop operating systems.

It recreates the feeling of using a desktop OS directly inside a web browser, with draggable application windows, a Dock, menu bar, virtual filesystem, Terminal, Notes, Calculator, Settings, notifications, themes, wallpapers, and more.

> **Note:** WebMac OS is an independent web-based simulator and is not affiliated with or endorsed by Apple.

## ✨ Features

* 🖥️ Full-screen desktop environment
* 🚀 Boot & lock screen experience
* 🪟 Draggable and resizable application windows
* 🔴 Minimize, maximize & close controls
* 🧭 macOS-inspired top menu bar
* 🚀 Interactive Dock with hover effects
* 📁 Virtual File Manager
* 📝 Functional Notes app
* 🧮 Calculator
* 💻 Simulated Terminal
* 🌐 Built-in simulated browser
* 🖼️ Gallery
* ⚙️ System Settings
* 🎨 Custom wallpapers & themes
* 🔍 Spotlight-style global search
* 🔔 Notification Center
* 🎛️ Control Center
* 🖱️ Desktop right-click menu
* ⌨️ Keyboard shortcuts
* 💾 Persistent settings with LocalStorage
* 🗄️ IndexedDB support for larger local data
* 📱 Responsive desktop experience
* ✨ Smooth window and UI animations
* 🥚 Hidden Easter eggs

## 🧩 Included Applications

### 📁 Files

A virtual file management system where users can:

* Create folders
* Create text files
* Rename items
* Delete items
* Move items to Trash
* Switch between grid and list views
* Search files

### 📝 Notes

A lightweight local note-taking application with:

* Create notes
* Edit notes
* Delete notes
* Search
* Auto-save
* Persistent storage

### 🧮 Calculator

A fully functional calculator supporting:

* Addition
* Subtraction
* Multiplication
* Division
* Percentage
* Decimal calculations
* Keyboard input
* Calculation history

### 💻 Terminal

A simulated command-line interface with commands such as:

```text
help
clear
date
time
whoami
pwd
ls
cd
mkdir
touch
echo
about
system
neofetch
history
```

The Terminal is completely simulated and does not execute real operating-system commands.

### ⚙️ Settings

Customize the WebMac environment with:

* Light / Dark / Auto theme
* Wallpapers
* Dock settings
* Desktop icon settings
* Sound
* Animations
* Notifications
* Boot animation

## ⌨️ Keyboard Shortcuts

| Shortcut       | Action             |
| -------------- | ------------------ |
| `Ctrl + Space` | Global Search      |
| `Ctrl + N`     | New Item           |
| `Ctrl + W`     | Close Window       |
| `Ctrl + M`     | Minimize Window    |
| `Escape`       | Close Menu / Modal |

Additional shortcuts may be supported within individual applications.

## 💾 Data Persistence

WebMac OS is designed to work without a backend.

Browser storage is used to preserve the user's environment, including:

* Theme
* Wallpaper
* Desktop icon positions
* Window positions
* Window sizes
* Dock preferences
* Notes
* Virtual filesystem
* Application settings

**LocalStorage** is used for lightweight settings and configuration, while **IndexedDB** can be used for larger browser-stored data such as images.

Data remains available after refreshing or reopening the website, subject to browser storage policies.

## 🛠️ Technologies

* HTML5
* CSS3
* JavaScript
* LocalStorage API
* IndexedDB
* CSS Backdrop Filter
* CSS Animations
* DOM APIs
* Browser APIs

No backend or database is required.

## 📂 Project Structure

```text
webmac/
│
├── index.html
│
├── css/
│   ├── main.css
│   ├── desktop.css
│   ├── windows.css
│   └── apps.css
│
├── js/
│   ├── app.js
│   ├── window-manager.js
│   ├── desktop.js
│   ├── dock.js
│   ├── menu-bar.js
│   ├── storage.js
│   ├── filesystem.js
│   ├── notifications.js
│   │
│   └── apps/
│       ├── finder.js
│       ├── notes.js
│       ├── calculator.js
│       ├── terminal.js
│       ├── browser.js
│       ├── gallery.js
│       └── settings.js
│
└── README.md
```

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/sajju001/webmac-os.git
```

Open the project:

```bash
cd webmac-os
```

Then open `index.html` in a modern browser.

No package installation or backend configuration is required for the frontend version.

## 🌐 Deployment

WebMac OS can be deployed on:

* GitHub Pages
* Netlify
* Vercel
* Cloudflare Pages
* Firebase Hosting

Because the project is primarily frontend-based, it can run directly in a modern web browser.

## 📱 Responsive Experience

WebMac OS is designed for:

* 💻 Desktop
* 💻 Laptop
* 📱 Mobile
* 📲 Tablet

On smaller screens, application windows automatically adapt to the available viewport.

## 🔐 Privacy & Security

WebMac OS is designed as a browser simulator.

It does not function as a real operating system and does not execute arbitrary system commands.

The simulated Terminal cannot access the user's real computer terminal.

Virtual files are managed inside the browser environment.

User data is stored locally where supported.

## 🎯 Project Goals

The main goals of WebMac OS are to:

* Experiment with advanced frontend development
* Explore desktop-style UI/UX in the browser
* Build an interactive web experience
* Demonstrate JavaScript application architecture
* Explore browser storage APIs
* Create a unique portfolio/vibe-coding project

## 🔮 Future Improvements

Potential future features:

* 👤 Multiple virtual user profiles
* 📦 Virtual App Store
* 🎵 Music Player
* 📅 Calendar
* 📧 Mail simulator
* 🗂️ Advanced file operations
* 🖥️ Multiple desktop spaces
* 🔐 Password-protected virtual accounts
* 🌐 More simulated web applications
* 🎮 Built-in mini games
* 🧩 Extension/plugin system
* 🖱️ Advanced touch gestures

## ⚠️ Disclaimer

WebMac OS is an independent browser-based project created for educational, experimental, and entertainment purposes.

It is **not a real operating system** and is **not affiliated with, sponsored by, or endorsed by Apple Inc.**

Apple and macOS are trademarks of Apple Inc.

## 📄 License

This project is available for personal, educational, and portfolio use.

---

### 🖥️ WebMac OS

**A complete desktop experience — running inside your browser.**
