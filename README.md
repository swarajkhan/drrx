<div align="center">

# DrRx 🩺
**Your Clinical Companion**

*A lightweight, high-performance, single-file web application designed to help doctors seamlessly generate, preview, and download beautifully formatted, print-ready A4 prescriptions in seconds.*

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![html2pdf](https://img.shields.io/badge/html2pdf.js-FF5722?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

</div>

---

## ⚡ Core Architecture

DrRx is engineered with a **zero-dependency, single-file architecture** (`index.html`). By bypassing traditional build steps, node modules, or backend server requirements, DrRx remains highly portable, exceptionally fast, and completely secure—running 100% on the client-side.

---

## ✨ Key Features & UI Highlights

* **🎛️ Dynamic Data Binding:** Real-time client-side rendering structures for O/E vitals, dynamic patient metrics rows, interactive medication tables, and live-updating numbered lists for clinical notes and advices.
* **✍️ HTML5 Signature Engine:** Fully interactive HTML5 signature canvas module, allowing doctors to securely append authentic signatures directly into the document structure.
* **📱 Responsive Viewport Scaling:** Features a custom CSS aspect-ratio viewport transform scale engine. The A4 preview seamlessly shrinks to fit mobile viewports natively (eliminating horizontal scrolling) without compromising the high-fidelity 100% scale required for flawless print rendering.
* **🧠 Smart UX Enhancements:** Employs intelligent, localized `localStorage` and `sessionStorage` arrays to persist state tracking. Includes a smart dashboard that detects the time of day and issues dynamic, personalized greetings ("Good Morning, Dr. 🌅").
* **📄 Flawless PDF Compilation:** Integrated with `html2pdf.js` for perfect client-side vector compilation, transforming the live DOM structure into a razor-sharp, downloadable A4 PDF.

---

## 🎨 Visual Layout Options

DrRx ships with 5 distinct, professional A4 layout themes to suit varying clinical branding needs. Selection state is effortlessly maintained via `sessionStorage`.

| Template Name | Design Philosophy |
| :--- | :--- |
| **Template 1: Standard Comprehensive** | A traditional, highly structured two-column corporate-clinical aesthetic utilizing deep slate grays and refined typography. |
| **Template 2: Modern Teal** | A vibrant, contemporary layout utilizing soft teal accents, edge-to-edge structural blocks, and a clean modern grid. |
| **Template 3: Editorial Vibrant** | A visually striking, contrast-heavy layout leveraging indigo blocks and dynamic typography for a premium presentation. |
| **Template 4: Compact Clean** | A minimalist, hyper-efficient, space-saving design optimized for high-volume text scaling. |
| **Template 5: Executive Classic** | A highly traditional, serif-driven, elegant design reminiscent of premium letterpressed corporate stationery. |

---

## 🚀 Installation & Local Deployment

Running DrRx locally is as simple as it gets. Because it uses a pure client-side stack, no build compilation or database setup is necessary.

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/drrx.git
   cd drrx
   ```

2. **Run the Application**
   - **Method A (Easiest):** Simply double-click the `index.html` file in your file explorer to open it natively in your default web browser.
   - **Method B (VS Code):** Open the folder in Visual Studio Code, right-click `index.html`, and select **Open with Live Server**.

---

## 📂 Code Architecture Overview

The system is elegantly packaged into a pure, unified structural configuration.

```text
drrx/
│
├── index.html        # The entire application (HTML structure, Tailwind config, JS logic, and styles)
└── README.md         # Documentation
```

---

## ☁️ Git Deployment Flow (GitHub Pages)

Because DrRx requires no backend compilation, it is perfectly suited for free, instantaneous hosting via GitHub Pages. Use this quick reference loop to push updates live:

```bash
# 1. Stage all modified files
git add .

# 2. Commit your updates with a descriptive message
git commit -m "Update signature canvas scaling and add dynamic greetings"

# 3. Push to your main branch
git push origin main
```
*Note: Ensure GitHub Pages is enabled in your repository settings (pointing to the `main` branch root) to automatically deploy changes directly to your live URL.*

---

<div align="center">
  <b>Designed with ❤️ for modern healthcare professionals.</b>
</div>
