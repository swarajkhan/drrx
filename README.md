<div align="center">

# DrRx 🩺

**Your Clinical Companion**

_A lightweight, high-performance, single-file web application designed to help doctors seamlessly generate, preview, and download beautifully formatted, print-ready A4 prescriptions in seconds._

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

- **🎛️ Dynamic Data Binding:** Real-time client-side rendering structures for O/E vitals, dynamic patient metrics rows, interactive medication tables, and live-updating numbered lists for clinical notes and advices.
- **✍️ HTML5 Signature Engine:** Fully interactive HTML5 signature canvas module, allowing doctors to securely append authentic signatures directly into the document structure.
- **📱 Responsive Viewport Scaling:** Features a custom CSS aspect-ratio viewport transform scale engine. The A4 preview seamlessly shrinks to fit mobile viewports natively (eliminating horizontal scrolling) without compromising the high-fidelity 100% scale required for flawless print rendering.
- **🧠 Smart UX Enhancements:** Employs intelligent, localized `localStorage` and `sessionStorage` arrays to persist state tracking. Includes a smart dashboard that detects the time of day and issues dynamic, personalized greetings ("Good Morning, Dr. 🌅").
- **📄 Flawless PDF Compilation:** Integrated with `html2pdf.js` for perfect client-side vector compilation, transforming the live DOM structure into a razor-sharp, downloadable A4 PDF.

---

## 🎨 Visual Layout Options

DrRx ships with 5 distinct, professional A4 layout themes to suit varying clinical branding needs. Selection state is effortlessly maintained via `sessionStorage`.

| Template Name                          | Design Philosophy                                                                                                           |
| :------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------- |
| **Template 1: Standard Comprehensive** | A traditional, highly structured two-column corporate-clinical aesthetic utilizing deep slate grays and refined typography. |
| **Template 2: Modern Teal**            | A vibrant, contemporary layout utilizing soft teal accents, edge-to-edge structural blocks, and a clean modern grid.        |
| **Template 3: Editorial Vibrant**      | A visually striking, contrast-heavy layout leveraging indigo blocks and dynamic typography for a premium presentation.      |
| **Template 4: Compact Clean**          | A minimalist, hyper-efficient, space-saving design optimized for high-volume text scaling.                                  |
| **Template 5: Executive Classic**      | A highly traditional, serif-driven, elegant design reminiscent of premium letterpressed corporate stationery.               |

---

<div align="center">
  <b>Designed with ❤️ for modern healthcare professionals.</b>
</div>
