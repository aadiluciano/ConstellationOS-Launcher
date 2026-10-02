# Constellation OS Launcher 🌌✨

A stunning, physics-driven, and fully customizable web dashboard/launcher built with modern web technologies and a gorgeous cosmic aesthetic. 

Constellation OS provides an interactive floating node interface that mimics a gravitational web of your favorite applications, services, and self-hosted tools.

---

## 🌟 Features

* **Physics-Driven Interface:** Nodes float, drift, and gently bounce off one another and screen boundaries with real-time collision physics.
* **Constellation Web Lines:** Dynamic connecting lines link nearby nodes together, creating an evolving starry network effect.
* **Dual Launch Modes:**
  * **Direct Tab Launch:** Opens apps instantly in a new browser tab.
  * **Embedded Header Modal (Sandbox):** Opens compatible web apps directly inside an integrated overlay window equipped with full-screen shortcuts and embedding safeguards.
* **Full Customization:**
  * Custom background support via image URLs or **local image file uploads**.
  * Custom app icons using URLs, **local file uploads (converted to base64 for persistence)**, or automatic domain favicon resolution.
  * Color-picker integration with automated theme extraction from logos.
* **Robust Fallbacks:** Automatic multi-tier fallback system (Custom Icon $\rightarrow$ Google Favicon $\rightarrow$ Styled Monogram Initial) ensuring your launcher always looks polished.
* **Persistent Storage:** All custom nodes, wallpapers, physics speed preferences, and launcher settings are saved locally in your browser via `localStorage`.
* **Zero Dependencies / Single File:** Written in vanilla HTML5, JavaScript, and Tailwind CSS (via CDN) for ultra-fast performance and effortless deployment.

---

## 🚀 Quick Start

1. Download or copy the `index.html` file from the repository.
2. Double-click the file to open it directly in any modern web browser (Chrome, Firefox, Safari, Edge).
3. Start using and customizing immediately—no build steps, Node.js installation, or server configuration required!

---

## 🛠️ How to Use

### Managing App Nodes
* **Launch an App:** Click or tap any floating node.
* **Edit or Delete:** Right-click (desktop) or long-press (mobile/touch) any node to open the context menu, where you can modify its settings or remove it.
* **Add a Node:** Click the **`➕`** button in the top dock to add a new custom web app, assign its theme color, choose a launch mode, and upload/link an icon.

### Personalizing the Launcher
* Click the **`⚙️`** settings gear icon in the top dock to:
  * Upload a local background image file or paste an image URL for your wallpaper.
  * Toggle the constellation web lines on or off.
  * Adjust the drift physics speed multiplier.
  * Reset default application presets if needed.
* Click the **`✨`** scatter button to re-initialize and randomize node positions.

---

## 💻 Tech Stack

* **HTML5 Canvas:** Powers the dynamic particle physics grid and connection lines.
* **Tailwind CSS:** Provides a sleek, modern UI design system.
* **Vanilla JavaScript (ES6+):** Handles node collision math, touch/pointer event handling, local storage persistence, and local file reader APIs.

---

## 📄 License

This project is open-source.
