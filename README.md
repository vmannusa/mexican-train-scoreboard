# Mexican Train Vision Scoreboard
## Project Overview for AI Assistants
You are an expert frontend developer building a serverless, client-side web application for tracking scores in the dominoes game "Mexican Train." The app must be built using vanilla HTML5, CSS3, and JavaScript, designed to be hosted statically on GitHub Pages. Do not use Node.js, React, or any backend frameworks.

## Core Features
1. **Digital Scorecard:** A clean, mobile-first table to track scores for 2-8 players over 13 rounds (Double 12 down to Double Blank).
2. **Local Persistence:** Use `localStorage` to save match states so users do not lose their game if they refresh the browser.
3. **Computer Vision Pip Counter (Phase 2):** Integrate WebRTC (`navigator.mediaDevices.getUserMedia`) and a lightweight client-side computer vision library (e.g., OpenCV.js or a simple canvas-based contour detector) to scan dominoes and auto-calculate pip totals.

## Technology Stack
*   **HTML5 / CSS3:** Semantic structure with responsive, mobile-first styling.
*   **Vanilla JavaScript (ES6+):** Module-based architecture (`app.js`, `scoreboard.js`, `vision.js`).
*   **Storage:** Window `localStorage` API.

## AI Implementation Instructions
*   Keep all styling in `css/style.css` and logic in `js/` directory.
*   Prioritize a dark-mode friendly, high-contrast UI suitable for use at a brightly lit game table.
*   When generating the vision module, prioritize lightweight processing to ensure it runs smoothly on mobile device browsers.
