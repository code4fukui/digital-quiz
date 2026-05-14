# digital-quiz

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple, single-page web application for taking multiple-choice quizzes. This application is built with vanilla JavaScript and features a Japanese-language user interface.

## Demo
https://code4fukui.github.io/digital-quiz/

## Features
- Fetches quiz questions and answers from a remote CSV file.
- Presents questions one by one in a multiple-choice format.
- Provides immediate feedback after each answer.
- Calculates and displays the final correct answer rate upon completion.
- Styled with a clean, neumorphic design.

## Usage
No installation or build process is required. Simply open `index.html` in a modern web browser to start the quiz.

## Data Source
The quiz content is sourced from the `ap-2021spring.csv` file within the [digital-quiz-data](https://github.com/code4fukui/digital-quiz-data/) repository.

## Dependencies
This project runs directly in the browser using the following external modules and stylesheets:

- **JavaScript Modules:**
  - [CSV.js](https://js.sabae.cc/CSV.js): For parsing CSV data.
  - [waitClick.js](https://js.sabae.cc/waitClick.js): For handling asynchronous click events.
  - [input-radio.js](https://code4fukui.github.io/input-radio/input-radio.js): A custom web component for radio button inputs.
- **Styling:**
  - [neomo.css](https://code4fukui.github.io/neomo.css/neomo.css): A lightweight CSS framework for neumorphic design.

## License
MIT License — see [LICENSE](LICENSE).