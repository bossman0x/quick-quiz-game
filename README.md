# Quick Quiz Game

A timed multiple-choice quiz game built with HTML, CSS, and JavaScript.
10 questions, 15 seconds each, live scoring, and a results screen.

## How to use
Just open `quiz-game.html` in any browser — no install needed.

## Customize the questions
At the top of the `<script>` section in `quiz-game.html`, there's a `QUESTIONS` array. Edit it to swap in your own school-specific questions:

```js
const QUESTIONS = [
  { q:"Your question here?", options:["A","B","C","D"], correct:0 },
  // correct: index of the right answer (0 = first option, 1 = second, etc.)
];
