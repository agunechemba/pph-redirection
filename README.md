# ⚡ PPH Quick Redirector

A minimalist, high-performance loading page designed for a seamless user transition. It features a modern dark-themed UI and a smooth CSS-only spinner, optimized to redirect users in exactly 1 second.

## 🚀 Overview

This project serves as a lightweight "bridge" or "splash screen" for the **PPH** web ecosystem. It ensures that users have a visual cue that a page is loading before they are automatically moved to the destination.

## ✨ Features

* **Fast Redirection:** Set to a crisp 1-second (1000ms) delay.
* **Ultra-Lightweight:** Zero external dependencies or heavy images.
* **Modern Dark Mode:** Uses a `#121212` background and system-native typography for a premium feel.
* **Smooth Animation:** High-speed (0.6s) CSS spinner for a responsive look.

## 🛠️ Installation

1.  **Download** the `index.html` file.
2.  **Upload** it to your web server or hosting platform (GitHub Pages, Netlify, Vercel, etc.).
3.  Ensure the file is named `index.html` so it acts as the primary entry point.

## ⚙️ Configuration

If you need to change the destination or the timing, edit the `<script>` section at the bottom of the file:

```javascript
// To change the destination URL:
window.location.href = "[https://pph.name.ng](https://pph.name.ng)";

// To change the speed (in milliseconds):
}, 1000); // 1000ms = 1 second
