# 🏠 Homeland

---

## 📌 Project Description

This project is a static and responsive web page called **Homeland**, inspired by the theme _“De Pátria para Pátria”_ — a symbolic journey that connects people and cultures from different parts of the world.

The page includes:

- A **header** with the project logo.
- A **main section** with a title, subtitle, and main image.
- An **intro** section with a quote, the author’s name, and descriptive project text.
- Multiple **place** sections, each highlighting a country or location through images, text, and external links.
- Use of **BEM (Block Element Modifier)** methodology for all section class naming.
- A **footer** with credits and copyright information.

---

🛠️ **Technologies Used**

- **HTML5** → semantic page structure
- **CSS3** → styling, layout, and responsiveness
- **BEM Methodology** → organized, scalable, and readable class names
- **Google Fonts** → modern and optimized web typography
- **Favicon SVG** → custom site icon

---

✨ **Main Features**

- **Multiple Content Sections:**  
  Each `place` section tells a story about a specific location, using images and texts for immersion.
- **Responsive Design:**  
  Built mobile-first using relative units (`%`, `vw`, `clamp()`). Uses media queries to adjust typography, spacing, and layout at different breakpoints.
- **Scoped Custom Styles:**  
  Uses BEM modifiers (e.g. `.place__paragraph-text`, `.place__paragraph-text:nth-of-type(3)`) for precise individual section or element customization.
- **Accessibility:**  
  Semantic HTML structure, descriptive alt text for all images.
- **External References:**  
  Country/location links open in new tabs for extra context.
- **Organized Code:**  
  No selector repetition for base elements. Media-query styles and element variants are grouped for clarity.

---

🎨 **Layout and Responsiveness**

- **Mobile-first design** ensures usability on all devices.
- Use of **mini media queries** only for fine-tuning, with minimal overrides.
- Consistent and adaptive typography for every screen size.

---

🔧 **Planned Improvements**

- Add smooth scrolling and subtle animations.
- Improve accessibility (ARIA labels, focus states).
- Implement advanced media queries for tablets and ultra-wide screens.
- Add a theme switch (light/dark mode).
- Expand with more sections: photos and short descriptions from more regions.
