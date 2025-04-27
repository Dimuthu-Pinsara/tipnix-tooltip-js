# Tipnix Tooltip

**Tipnix Tooltip** is a lightweight and developer-friendly JavaScript plugin for adding customizable tooltips to your web project.  
Quickly style tooltips using intuitive `tipnix-*` attributes without bloating your HTML with JavaScript code.

🔗 **Documentation**: [Tipnix Documentation Site](https://tipnix-documentation.vercel.app/)

---

## ✨ Features

- Easy initialization
- Attribute-based styling (`tipnix-*`)
- Fully customizable (background, text color, font size, etc.)
- Lightweight and fast
- No external dependencies

---

## 📦 Installation

(Coming soon to **npm**!)

For now, you can manually include it:

```html
<!-- Include Tipnix Tooltip from CDN -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Dimuthu-Pinsara/tipnix-tooltip-js@latest/tipnix-tooltip.css">
<script src="https://cdn.jsdelivr.net/gh/Dimuthu-Pinsara/tipnix-tooltip-js@latest/tipnix-tooltip.js"></script>
```

## 🚀 Getting Started

### 1. Initialize Tipnix Tooltip
Frist you need to add default color for this tooltip

```javascript
initTipNixTooltip({
    backgroundColor: '#000000',
  });
```
### 2. Add tooltip to your HTML

```html
<div class="tipnix" tipnix-text="Tipnix Tooltip Js">
      <span class="text">i</span>
  </div>
```
### 🛠️ Available Attributes

| Attribute        | Description                  |
| ---------------- | ----------------------------- |
| `tipnix-text`     | Tooltip content               |
| `tipnix-bg`       | Background color (HEX/RGB)    |
| `tipnix-text-color`    | Text color                    |
| `tipnix-font-size` | Font size (e.g., 14px, 1rem)   |
| `tipnix-padding`  | Tooltip inner padding         |

👉 See the [full documentation](https://tipnix-documentation.vercel.app/) for more options and examples.

### Upcoming
Tipnix Tooltip will soon be available as an **npm package**!

New features like:
- 🎞️ Animation control
- ⏳ Delay settings
- 📍 Smart positioning

are coming soon to enhance the user experience even more. Stay tuned for updates!

### Author

Created and Maintained by Dimuthu Pinsara
Follow for updates and new releases!
