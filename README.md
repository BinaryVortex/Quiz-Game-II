# Neon Quiz — Quiz-Game-II

A small, stylish neon-themed quiz web app built with plain HTML, CSS and JavaScript.

![Neon Quiz Screenshot](./Screenshot%202026-04-27%20at%2013.08.15.png)

Overview

Neon Quiz ("Quiz-Game-II") is a single-page quiz application with a sci-fi / Matrix-inspired UI. It features animated backgrounds and particle effects, question progress tracking, and immediate feedback on answers.

Live preview

- Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari) to run the game locally.

Features

- Clean single-file implementation (HTML + embedded CSS & JavaScript)
- Animated neon UI with particles, gradient text and smooth transitions
- Multiple-choice questions with correct/wrong feedback
- Progress bar and score summary at the end
- Responsive layout for tablets and phones

How to play

1. Open `index.html` in your browser.
2. Read the question and click an option.
3. Click the "Execute" button to confirm your answer.
4. The UI will highlight correct and incorrect answers, then advance to the next question.
5. At the end you will see your score and a short status message.

Customization

- Questions are stored in `index.html` inside the `quizData` array. Edit that array to change questions, options, or correct answers.
- Styling and animations are all in the page's `<style>` block — feel free to tweak colors, fonts (Orbitron is loaded from Google Fonts), and animations.

Development notes

- No build tools or dependencies required — the project runs as static files.
- To add more questions, increase the `quizData` array and the UI will automatically update the total questions count.
- The progress bar width is computed from the current question index; if you change the navigation timing or flow, you may want to update `updateProgressBar()`.

Credits

- Written by BinaryVortex
- Font: Orbitron (Google Fonts)

License

This repository does not include an explicit license. If you want to allow reuse, consider adding an open-source license (e.g., MIT) in a `LICENSE` file.
