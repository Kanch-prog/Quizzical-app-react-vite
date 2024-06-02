# Quizzical - React Quiz Application

## Introduction
Quizzical is a React-based quiz application that fetches trivia questions from an external API and allows users to test their knowledge by answering them. It provides an interactive user interface and supports features like checking answers, scoring, and playing again.

## Technologies Used
- React
- React Hooks (useState, useEffect)
- Nanoid (for generating unique IDs)
- Fetch API (for fetching trivia questions)
- Tailwind CSS (for styling)

## Features
- **Start Quiz:** Click the "Start Quizzical" button to begin the quiz.
- **Answer Questions:** Answer trivia questions displayed on the screen.
- **Check Answers:** Verify your answers and see the score.
- **Play Again:** Restart the quiz to play again.

## Components
### 1. App Component (`App.js`)
- Main component managing the quiz functionality.
- Handles state for quiz status, questions, count, checked status, and score.
- Fetches trivia questions from an external API using the `useEffect` hook.
- Renders the Menu component if the quiz hasn't started, else renders the Question component.

### 2. Menu Component (`Menu.js`)
- Displays the start menu of the quiz.
- Contains the application title, description, and a start button.
- Invokes the `start` function passed from the parent component when the start button is clicked.

### 3. Question Component (`Question.js`)
- Displays a single trivia question along with answer options.
- Handles user interactions like selecting an answer and checking answers.
- Styles answer buttons based on correctness and user selection.

## Setup
1. Clone the repository.
2. Navigate to the project directory.
3. Install dependencies using `npm install`.
4. Run the application using `npm start`.

## Folder Structure
- **src/**
  - **components/**: Contains React components (App, Menu, Question).
  - **assets/**: Contains image files (blob.svg).
  - **App.js**: Main component.
  - **Menu.js**: Menu component.
  - **Question.js**: Question component.
  - **index.js**: Entry point of the application.
  - **tailwind.config.js**: Tailwind CSS configuration file.
  - **vite.config.js**: Vite configuration file.

## Credits
- This application was created by [Kanchana Karunarathna](https://github.com/Kanch-prog).

## License
This project is licensed under the [MIT License](LICENSE).
