# Theo & Alisha Shakya-Santos' Ultimate Baby Reveal Game! 👶✨

Welcome to the official repository for **Theo & Alisha Shakya-Santos' Ultimate Baby Reveal Game** – a delightful, interactive, and highly animated online experience designed to share their joyous news with friends and family in a unique and memorable way!

This project is a single HTML file that bundles all the magic: a captivating puzzle, a grand gender reveal, and a heartwarming pregnancy journey slideshow, all wrapped in a playful and dynamic design.

---

## 🌟 Game Overview

Friends and family are invited to:
1.  **Get Started:** A welcoming intro screen (with an optional "rotate device" prompt for mobile users) sets the stage and explains the simple game mechanics.
2.  **Solve the Puzzle:** Click on three animated circular puzzle pieces in the correct sequence. Each piece is a vibrant color and features a unique emoji hint (🗣️, 👣, 🕯️) with an animated question mark. The puzzle area itself has a dynamic, abstract gradient background, ensuring no premature hints are given.
3.  **Follow Along:** A colorful and animated walkthrough panel guides players, highlighting the active step with a pulsing glow and marking completed steps with a satisfying checkmark animation.
4.  **Build Suspense:** Each correct click reveals a word ("IT'S", "A"). The final click unveils a "?" to build maximum anticipation before the grand announcement.
5.  **The Grand Reveal!**
    * The screen transitions to a spectacular reveal sequence.
    * The background features the "shelf scene" image (`https://i.imgur.com/EWm3Cjd.jpeg`) blended with a blue overlay that becomes more transparent after a few seconds, making the image clearer.
    * Animated text elements ("IT'S A BOY!", "Leander Ratna H Santos", "Our little Boy!") appear sequentially with playful zoom effects and vibrant, contrasting colors with strong shadows/glows.
    * The screen is filled with dynamic celebratory effects: an abundance of colorful confetti, starbursts, and floating balloons.
    * A majestic piano melody accompanies this reveal.
    * This screen lasts for 10 seconds before automatically transitioning to the slideshow.
6.  **Our Pregnancy Journey (Slideshow):**
    * A continuous, gentle Einaudi-style piano melody plays.
    * Personalized pregnancy photos are displayed with captions. Each image container initially appears smaller, then smoothly expands after 3 seconds to nearly fill the page width, framed by an animated gradient border.
    * **The Grand Finale Slide:**
        * The "shelf scene" image (`https://i.imgur.com/EWm3Cjd.jpeg`) is displayed.
        * It first pans and zooms into the "IT'S A BOY" detail on the letter board.
        * Then, this panned/zoomed view performs a gentle "settle zoom" to fill the entire viewport.
        * The main slideshow card fades out, and the fullscreen image is slightly dimmed.
        * The "Thank You" message, "Previous/Next" navigation, and "Play Game Again?" button appear, fixed at the bottom, overlaying the dimmed fullscreen image.
        * Animated stars, balloons, and flowers continue to float over the fullscreen image.
        * The game holds on this final, immersive view.

---

## 🛠️ Key Features & Technologies

* **Single HTML File:** Easy to share and host.
* **Mobile-First Responsive Design:** Optimized for a great experience on all devices, with specific attention to mobile usability. Includes a "rotate device" prompt.
* **Dynamic & Playful UI:**
    * Animated "bokeh" background throughout the game.
    * Animated gradient headings on all screens.
    * Playful fonts and color schemes (neutral pre-reveal, celebratory post-reveal).
* **Interactive SVG Puzzle:** Circular puzzle pieces with emoji hints and smooth animations.
* **Animated Walkthrough:** Dynamic highlighting and completion indicators.
* **Rich Animations:** CSS and JavaScript animations for UI elements, text reveals, puzzle interactions, and spectacular celebratory effects.
* **Immersive Sound Design:** Uses Tone.js for synthesized sound effects and melodies, including a continuous piano loop for the slideshow.
* **Personalization:** Designed for easy customization of names, images, and captions.
* **Modern Styling:** Leverages Tailwind CSS for utility classes, complemented by custom CSS for unique visual effects.
* **Robust JavaScript:** Includes an IIFE and initialization guard to prevent script conflicts.

---

## 🚀 How to Play & Share

1.  **Download:** Get the single `.html` file from this repository.
2.  **Host Online:** Upload this HTML file to any static web hosting service. Popular free options include:
    * [Netlify Drop](https://app.netlify.com/drop) (Drag & drop your file)
    * [GitHub Pages](https://pages.github.com/) (Host directly from a GitHub repository - ensure the file is named `index.html`)
    * [Vercel](https://vercel.com/)
    * [Tiiny.host](https://tiiny.host/) (Good for quick, temporary sharing)
3.  **Share the Link:** Once hosted, you'll receive a public URL (e.g., `https://your-chosen-name.netlify.app`). Share this link with your loved ones via email, text, or social media!

---

## 🎨 Customization (Brief Guide)

To personalize this game for your own reveal:

* **Names:** Search within the `<script>` tag for `Theo Santos & Alisha Shakya-Santos` and `Leander Ratna H Santos` and replace them with your names.
* **Slideshow Images & Captions:**
    * Locate the `slideshowData` array in the JavaScript.
    * Replace the `image` URLs with direct links to your hosted pregnancy photos.
    * Update the `caption` for each photo.
* **Final Reveal Message (if different):**
    * The variables `finalRevealMessageText` and `finalRevealSubMessageText` in the JavaScript can be modified if needed, though "IT'S A BOY!" (or "IT'S A GIRL!") is standard.
* **Colors & Fonts:** Advanced users can modify the CSS within the `<style>` tags to change color palettes, font families (ensure new fonts are linked via Google Fonts or similar), and animation styles.

---

## 📝 License

The creative content, design, and specific code arrangement of this "Ultimate Baby Reveal Game" (excluding third-party libraries listed below) are licensed under the **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License**.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a>

This means you are free to:
* **Share** — copy and redistribute the material in any medium or format for personal, non-commercial use.

Under the following terms:
* **Attribution (`BY`)** — You must give appropriate credit to **Theo Santos & Alisha Shakya-Santos** (e.g., "Original game concept and design by Theo Santos & Alisha Shakya-Santos, adapted by [Your Name if adapted for personal use, though ND means no distribution of derivatives]"), provide a link to the license, and indicate if changes were made (though changes are not for redistribution under ND).
* **NonCommercial (`NC`)** — You may not use the material for commercial purposes.
* **NoDerivatives (`ND`)** — If you remix, transform, or build upon the material, you may not distribute the modified material. You can modify it for your own personal use, but sharing of such modified versions is restricted by this license.

**Third-Party Libraries:**
This project utilizes the following open-source libraries, which are subject to their own licenses:
* **Tailwind CSS:** ([https://tailwindcss.com/](https://tailwindcss.com/)) - MIT License
* **Tone.js:** ([https://tonejs.github.io/](https://tonejs.github.io/)) - MIT License
* **Google Fonts:** (Fonts used are subject to their respective open licenses, typically SIL Open Font License or Apache License)

Please refer to their respective websites for full license details.

---

## 🙏 Acknowledgements

A heartfelt project created for Theo Santos & Alisha Shakya-Santos to celebrate and share their wonderful news in a uniquely memorable way!
�
