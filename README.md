# Bollywood Song Quiz

Summary
- A self-contained, single-file HTML web application that presents a Bollywood-themed song quiz.
- Users answer multiple-choice questions with a per-question timer, can use a hint to eliminate one wrong option, and see a final score with a summary.

Key Features
- Fully client-side, no dependencies or external assets required.
- 10 Bollywood-themed questions with a per-question 20-second timer.
- Hint feature to remove one incorrect answer (one-time use per quiz).
- Auto-advance on time-out and on answer selection; progress bar and live score updates.
- Responsive and visually appealing UI with modern styling and subtle animations.
- Restart/Play Again flow and a simple “How to Play” helper.

Setup Instructions
- Save as index.html.
- Open index.html in any modern web browser (Chrome, Firefox, Edge, Safari).

Usage Instructions
1. Open the HTML file in a browser.
2. Click “Start Quiz” to begin. Each question has a 20-second timer.
3. Click an answer to score. The correct answer will be highlighted in green; the wrong answer in red if chosen.
4. Use the “Hint” button to eliminate one incorrect option (usable once per quiz).
5. Click “Next” to proceed to the next question. When all questions are answered, you’ll see your results.
6. Click “Play Again” to restart with a shuffled question order.

Technical Details
- HTML: Provides three main screens (Start, Quiz, Result) within a single HTML file, structured with semantic sections and ARIA attributes for accessibility.
- CSS: Included in a <style> tag. Uses a Bollywood-inspired color palette with glassy card design, gradient accents, and responsive layout.
- JavaScript: All quiz logic is in a single <script> tag. Includes:
  - A questionsPool array containing 10 Bollywood-themed questions.
  - Question shuffling, per-question timer, score tracking, and UI rendering.
  - Hint feature that removes one incorrect option.
  - Auto-timer timeout behavior and end-of-quiz handling.

Deployment Info
- This app is ready for deployment on GitHub Pages or any static hosting service.
- To deploy on GitHub Pages:
  - Create a repository (e.g., Bollywood-Quiz).
  - Commit the index.html file to the repository.
  - Enable GitHub Pages from the repository settings (set source to main/master branch or /docs if using a docs folder).
  - Access the app at https://<your-username>.github.io/Bollywood-Quiz/

License
- MIT

Generated Date
- 2025-10-23