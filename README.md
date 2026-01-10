# 🚀 Cyber-Terminal Redirector

A sleek, dark-themed splash screen featuring a "spinning code wheel" animation. This page mimics a terminal environment, cycling through programming snippets before automatically redirecting the user to a destination URL.

## 🛠 Features

* **Dark Mode Aesthetic:** GitHub/Matrix-inspired color palette.
* **Dynamic Loader:** A CSS-animated spinning ring with randomized code snippets (e.g., `git push`, `void*`, `0x5F32`) appearing in the center.
* **Auto-Redirect:** Automatically sends users to `https://pph.name.ng` after a set delay.
* **Terminal Effects:** Includes a blinking command-line cursor and cycling status messages.
* **Responsive:** Works on mobile and desktop browsers.

## 🚀 Quick Start

1.  **Clone or Copy:** Copy the code from `index.html`.
2.  **Host:** Upload the file to your web server (GitHub Pages, Netlify, or your local hosting).
3.  **Go:** Navigate to the file in your browser, and it will handle the rest.

## ⚙️ Configuration

You can easily modify the behavior of the page by editing the variables in the `<script>` tag:

### Change Destination URL
Find this line and swap the URL:
```javascript
const destination = "[https://pph.name.ng](https://pph.name.ng)";
