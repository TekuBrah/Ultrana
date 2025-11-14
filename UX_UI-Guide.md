<!-- ⚠️ Best viewed in VS Code Markdown Preview -->
<!-- In GitHub this file may look unformatted or misaligned -->

<div align="center" style="font-size:28px; font-weight:700; color:#4ec9b0;">
✨ Ultrana UX / UI Design Guide ✨
</div>

> ⚠️ **Important:**  
> This document is optimized for **VS Code Markdown Preview**.  
> For proper formatting, gradients, and embedded visuals, please **clone this repository** and open it in **VS Code** (`Ctrl + Shift + V`).

---

## 🎯 Project Overview

**Ultrana** is a decentralized perpetual exchange platform designed to deliver a clean, high-contrast interface for traders.  
The UX/UI is based on **clarity, hierarchy, and responsiveness**, focusing on visual trust and trading performance.

The design follows:
- **Dark aesthetic** to emphasize data and contrast.
- **Blue accent color** for interaction and brand consistency.
- **Clean typographic rhythm** with even spacing and consistent hierarchy.
- **Grid-based layout** for modular scalability across devices.

---

## 🧭 Section 1 — Landing Page Overview

![Dashboard Overview](public/Ultrana/Dashboard.JPG)

### 🔹 Visual Intent
The landing page introduces **Ultrana** with a strong brand identity and futuristic tone.  
Typography uses **strong weight contrast** between _“Ultrana”_ and _“Decentralized Perpetual Exchange”_ to guide focus.  

### 🔹 Key UX Points
- Primary CTA (`START TRADING`) is centered and uses brand blue.
- Background illustration conveys innovation and technical depth.
- Supporting metrics (volume, fees, open interest, users) establish credibility.

### 🔹 Design Guidelines
- Maintain **visual hierarchy** with bold text for headlines and light gray for supporting lines.  
- Keep CTA spacing generous (minimum 40px top/bottom).  
- Accent color: `#2979FF` for brand actions.  

---

## 🪙 Section 2 — Ecosystem Tokens

![Ecosystem Tokens](public/Ultrana/Ecosystem_Tokens.JPG)

### 🔹 Visual Intent
This section introduces Ultrana’s ecosystem tokens (**U2U**, **UTX**, **ULP**) in a consistent card layout.  
Each token card uses similar structure: icon, title, price, description, and actions.

### 🔹 Key UX Points
- Equal card dimensions maintain visual rhythm.  
- **Buttons** (“Buy” and “Read More”) have consistent color and radius.  
- Hover/focus states should emphasize interactivity (slight scale or glow).  

### 🔹 Design Guidelines
- Each card padding: `24px` minimum.  
- Font sizes:  
  - Token name: `18px` bold  
  - Description: `14px` light gray  
- Use shadow depth (`box-shadow: 0 0 12px rgba(0,0,0,0.4)`) for separation on dark backgrounds.

---

## 📈 Section 3 — Trading Interface

![Trading Interface](public/Ultrana/trading_graph.JPG)

### 🔹 Visual Intent
The trading view prioritizes information density with calm color hierarchy and clear modular zones.  

### 🔹 Key UX Points
- Split layout: chart left, controls right.  
- Secondary panels (positions, history) appear only when wallet connected.  
- Emphasize **instant feedback** with hover, loading, and active states.  

### 🔹 Design Guidelines
- Use consistent border radius (`6px`) and internal spacing (`16px`).  
- Maintain strong **grid alignment**: charts and input areas align at baseline.  
- Use smooth transitions (`200ms ease-in-out`) for input focus and button presses.

---

## 🎨 Global Design Principles

| Element | Recommendation |
|----------|----------------|
| **Typography** | Use Sans-serif (e.g. Inter / Poppins). Maintain clear weight hierarchy. |
| **Color Palette** | Primary `#2979FF`, Accent `#00C2FF`, Background `#0D1117`. |
| **Grid System** | 8px spacing rule for consistency. |
| **Motion** | Subtle transitions only; emphasize responsiveness, not distraction. |
| **Accessibility** | Minimum 4.5:1 contrast ratio for all text elements. |

---

## 🧠 Notes for Designers

- Always prototype in **macOS** or high-DPI environments to match color rendering accurately.  
- Review animations using **VS Code Live Preview** or Figma Mirror for consistency.  
- Follow design tokens defined in `/theme/tokens.json`.  
- Avoid introducing new accent colors without approval from the design lead.

---

<div align="center" style="margin-top:40px; font-size:18px;">
Made with ❤️ by the Ultrana Design Team  
<br>
<small>Open this file in VS Code for the complete UX/UI experience</small>
</div>
