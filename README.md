# 🏞️ Dynamic Parallax Scrolling Website

A highly engaging and visually rich website that features a **parallax scrolling effect**. This project demonstrates mastery of the browser's `onscroll` event and dynamic manipulation of CSS properties to create a 3D depth illusion.

## ✨ Key Features
* **Real-time Parallax:** Elements like stars, the moon, and mountains move at different speeds relative to the scroll position, simulating depth.
* **Dynamic Styling:** The background gradient dynamically changes color as the user scrolls further down the page, enhancing the atmospheric effect.
* **JavaScript Scroll Logic:** All movement and styling changes are controlled by a core JavaScript function that calculates element positions based on `window.scrollY`.
* **CSS Blend Modes:** Utilizes CSS properties like `mix-blend-mode` (on the moon) for enhanced visual composition.

## 💻 Technologies Used
* **HTML5:** Provides the layered structure for the scene (header, main content, and image layers).
* **CSS3:** Advanced styling, including responsive layout, image positioning, and visual effects like gradients and blend modes.
* **JavaScript (Vanilla):** Implements all the core animation and interaction logic using the `onscroll` event listener and DOM manipulation.

## 🚀 Getting Started

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/JS-Parallax-Scroll-Effect.git](https://github.com/YourUsername/JS-Parallax-Scroll-Effect.git)
    ```
2.  **Launch:** Open the `index.html` file in your web browser. No server is required.

## 💡 Technical Note
The core logic is within the `onscroll` function in `main.js`, where the `scrollY` value is used as a multiplier to determine the `top` and `left` CSS values of the layered images.
