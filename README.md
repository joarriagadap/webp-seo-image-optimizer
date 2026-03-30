[README.md](https://github.com/user-attachments/files/26336286/README.md)
# 🖼️ WebP SEO Image Optimizer

> **Convert, compress and rename product images to WebP with automatic SEO-friendly filenames.**  
> 100% browser-based — no server, no upload, no account required. Free forever.

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Available-5b6bff?style=for-the-badge)](https://joarriagadap.github.io/webp-seo-image-optimizer)
[![License: MIT](https://img.shields.io/badge/License-MIT-00e5b4?style=for-the-badge)](LICENSE)
[![No Backend](https://img.shields.io/badge/Backend-None_Required-ff6b6b?style=for-the-badge)](#)
[![WebP](https://img.shields.io/badge/Output-WebP-5b6bff?style=for-the-badge)](#)

---

## 🔍 What is this?

**WebP SEO Image Optimizer** is a free, open-source browser tool that helps e-commerce stores, optical shops, and online retailers:

- ✅ Convert product images (JPG, PNG, GIF, BMP, AVIF) to **WebP format**
- ✅ Automatically generate **SEO-friendly filenames** from product info
- ✅ Control **compression quality** for the best size/quality balance
- ✅ **Batch process** multiple images with drag & drop
- ✅ Download converted images individually or all at once

**No installation. No signup. No data leaves your browser.**

---

## 🚀 Live Demo

👉 **[Try it now → joarriagadap.github.io/webp-seo-image-optimizer](https://joarriagadap.github.io/webp-seo-image-optimizer)**

---

## ✨ Features

| Feature | Description |
|---|---|
| 🏷️ Auto SEO Slug | Generates filenames like `lentes-rayban-wayfarer-negro-uv400.webp` automatically |
| 📦 Product Fields | Name, SKU, category, keywords — all combined into one SEO filename |
| ⚙️ Compression Control | Slider from 10–100% with smart recommendations (75–85% for e-commerce) |
| 🗂️ Drag & Drop | Drop multiple images at once for batch processing |
| 📥 Bulk Download | Download all converted images with one click |
| 🔒 100% Private | All processing happens in your browser — no image is ever uploaded |
| 📱 Responsive | Works on desktop and mobile |

---

## 💡 Why SEO-friendly image names?

Most e-commerce stores upload images named `IMG_001.jpg` or `foto.png`. This is a **missed SEO opportunity**.

Google's image search reads filenames as ranking signals. A descriptive filename tells Google exactly what the image shows:

```
❌ IMG_001.jpg
✅ lentes-rayban-wayfarer-negro-uv400-polarizado.webp
```

Combined with **WebP format**, which is up to **90% lighter than JPG**, you get:

- 📈 Better Google Image Search ranking
- ⚡ Faster page load speed
- 🏆 Better Core Web Vitals scores
- 🛒 Higher conversion rates (faster sites sell more)

---

## 🧩 How It Works

1. **Enter product info** — name, SKU, category, keywords
2. **Preview the SEO filename** generated in real time
3. **Set compression** — recommended 75–85% for e-commerce
4. **Drop your images** — JPG, PNG, GIF, BMP, AVIF supported
5. **Click Convert** — images are processed in your browser
6. **Download** — individually or all at once as WebP

---

## 📁 File Naming Logic

The tool builds filenames following this SEO structure:

```
{category}-{product-name}-{keywords}-{sku}.webp
```

**Example inputs:**
- Product: `Lentes Ray-Ban Wayfarer`
- Category: `lentes-sol`
- Keywords: `negro, uv400, polarizado, hombre`
- SKU: `RB-2140-901`

**Output filename:**
```
lentes-sol-lentes-ray-ban-wayfarer-negro-uv400-polarizado-hombre-rb-2140-901.webp
```

For multiple images, a sequential suffix is added automatically:
```
lentes-sol-lentes-ray-ban-wayfarer-negro-uv400-01.webp
lentes-sol-lentes-ray-ban-wayfarer-negro-uv400-02.webp
```

---

## 🖥️ Use Locally

No build step required. Just open the HTML file:

```bash
git clone https://github.com/joarriagadap/webp-seo-image-optimizer.git
cd webp-seo-image-optimizer
open index.html
```

Or serve it locally:

```bash
npx serve .
# → http://localhost:3000
```

---

## 🌐 Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Save — your tool will be live at `https://joarriagadap.github.io/webp-seo-image-optimizer`

---

## 🛒 Perfect For

- 👓 **Optical stores** — lenses, frames, sunglasses catalogs
- 👟 **Fashion e-commerce** — shoes, clothing, accessories
- 🛋️ **Home & furniture** — product catalog optimization
- 📸 **Photographers** — batch rename and convert client deliverables
- 🧑‍💻 **Web developers** — automate image optimization for client projects

---

## 🔑 SEO Tips for Product Images

> These tips are built into the tool's UI, but here's a quick reference:

- **Use descriptive names** — `lentes-oakley-holbrook-azul-polarizado.webp` beats `photo1.jpg` every time
- **Include brand + model + color + material** — each keyword helps Google understand the image
- **WebP format** reduces file size up to 90% vs JPG with no visible quality loss
- **Lighter images = faster pages = better ranking** — Google's Core Web Vitals reward fast-loading sites
- **Aim for 75–85% quality** — the sweet spot for e-commerce between visual quality and file size

---

## 🧰 Tech Stack

- **Vanilla JavaScript** — zero dependencies
- **Canvas API** — native browser image processing and WebP conversion
- **HTML5 File API** — drag & drop and file reading
- **CSS Custom Properties** — theming and design system
- **Google Fonts** — Syne + DM Mono + DM Sans

No frameworks. No npm. No build tools. Just one HTML file.

---

## 📄 License

MIT License — free to use, modify and distribute. See [LICENSE](LICENSE) for details.

---

## 🙌 Contributing

Pull requests are welcome! If you have ideas for new features:

1. Fork the repo
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit your changes
4. Open a Pull Request

---

## ⭐ Support

If this tool saved you time, **give it a star** ⭐ — it helps others find it!

Have a bug or feature request? [Open an issue](https://github.com/joarriagadap/webp-seo-image-optimizer/issues).

---

<p align="center">
  Made with ☕ for e-commerce teams who care about SEO
</p>
