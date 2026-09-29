# Quiz App

> **Original version:** this README and some fixes were added in 2026. To see the project exactly as it was first built, browse commit [`f06cdb0`](https://github.com/dianapaula19/quiz-app/tree/f06cdb01d4b014eca30188f1963fdce5c9a5a977) (2020-08-06).

An Android app with two quizzes: a **Marvel trivia quiz** with animated GIF questions and a
**basic French test**. Answers are highlighted as right or wrong, and the final score comes
with a message that depends on how well you did.

My third project for the *Google Developer Challenge Scholarship* (Android Basics, Udacity,
January 2018).

- Java, custom fonts and drawable borders for right/wrong answers
- Radio buttons, checkboxes and free-text answers across the two quizzes

## Screenshots

<p>
  <img src="docs/main.png" width="19%" alt="Pick a quiz">
  <img src="docs/marvel.png" width="19%" alt="Marvel trivia quiz">
  <img src="docs/marvel_questions.png" width="19%" alt="Marvel quiz questions">
  <img src="docs/french.png" width="19%" alt="Basic French test">
  <img src="docs/french_questions.png" width="19%" alt="French test questions">
</p>
<p>
  <img src="docs/marvel_answered_1.png" width="19%" alt="A right answer, with its GIF">
  <img src="docs/marvel_answered_2.png" width="19%" alt="A wrong answer, with the right one marked in green">
</p>

Rendered in 2026 from the app's own layouts with [Paparazzi](https://github.com/cashapp/paparazzi).
After each Marvel answer the app marks it right or wrong and plays a GIF of Tom Holland answering
the same question (shown here as a single frame).

Open the project in Android Studio and run it on an emulator or a phone.
