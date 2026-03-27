# 🧱 Ultimate Stacking Cards Section for Shopify

A premium, high-performance **sticky scroll animation section** designed for modern Shopify OS 2.0 themes. Built with scalability, performance, and flexibility in mind.

---

## 🔥 Overview

The **Ultimate Stacking Cards Section** delivers a visually engaging scrolling experience where cards stack, scale, and transition smoothly — perfect for storytelling, product highlights, and landing pages.

Designed specifically for **Shopify theme developers and agencies** who want clean architecture without sacrificing performance.

---

## 🎯 Use Cases

* Product storytelling sections
* Feature comparison layouts
* Landing page interactions
* Portfolio / showcase sections
* SaaS-style scroll animations

---

## ✨ Core Features

* 💎 **Sticky Stack Animation Engine**
  Smooth stacking interaction using optimized scroll calculations.

* ⚡ **Performance First Architecture**

  * No external libraries
  * Minimal DOM reflows
  * 60fps animation optimized

* 🎨 **Advanced Theme Customization**
  Full control via Shopify Customizer (no code required).

* 📱 **Responsive by Design**
  Adaptive layout for mobile, tablet, and desktop.

* 🎥 **Dynamic Media Handling**
  Supports:

  * Images
  * Dual video layout
  * Mixed media blocks

* 🧩 **Scoped CSS System**
  Prevents style conflicts across sections using dynamic identifiers.

---

## 🧠 Architecture

### Scoped Styling System

Each instance generates isolated styles:

```css
.s-card-stack-inner-{{ section.id }} {
  --stack-gap: {{ section.settings.stack_gap }}px;
}
```

✔ Prevents cross-section conflicts
✔ Supports multiple instances on same page

---

### Animation Strategy

* Scroll-based transformation logic
* GPU-friendly `transform` usage
* Uses requestAnimationFrame for smoothness

---

### Liquid Logic

* Conditional rendering for media types
* Dynamic block-based structure
* Fully modular section schema

---

## 🛠️ Installation

### 1. Add Section File

* Go to **Shopify Admin → Online Store → Themes → Edit Code**
* Create new section:
  `stacking-cards.liquid`

---

### 2. Insert Code

* Copy code from repository
* Paste into the section file
* Save changes

---

### 3. Enable in Theme

* Open **Customize**
* Click **Add Section**
* Select **Ultimate Card Stack**

---

## ⚙️ Customization Options

| Setting         | Type   | Description                   |
| --------------- | ------ | ----------------------------- |
| Container Width | Number | Max width of layout           |
| Stack Gap       | Slider | Spacing between stacked cards |
| Typography      | Range  | Responsive font scaling       |
| Card Colors     | Color  | Per-card styling              |
| Media Type      | Block  | Image / Video                 |
| Border Radius   | Range  | Corner styling                |

---

## 🚀 Performance

| Metric             | Result          |
| ------------------ | --------------- |
| Dependencies       | 0               |
| Rendering Strategy | GPU Accelerated |
| Scroll Handling    | Optimized       |
| Lighthouse Ready   | ✅               |

---

## 🧪 Compatibility

* ✅ Shopify OS 2.0 Themes
* ✅ All modern browsers (Chrome, Safari, Edge)
* ⚠️ Limited fallback for very old browsers

---

## 🔒 Best Practices

* Use optimized images/videos
* Avoid excessive blocks for smoother scroll
* Test on mobile for spacing adjustments

---

## 📦 File Structure

```
sections/
  stacking-cards.liquid
```

---

## 📝 License

Licensed under the **MIT License** — free for personal and commercial use.

---

## 🤝 Contributing

Contributions, improvements, and suggestions are welcome!

1. Fork the repo
2. Create a feature branch
3. Submit a PR

---

## 💼 Support & Custom Work

Need customization or integration?

* Shopify custom sections
* Performance optimization
* UI/UX improvements

Feel free to open an issue or reach out.

---

## ⭐ Show Your Support