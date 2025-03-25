# Random Questions Generator

Link to site: [github pages question_randomizer](https://dkavaliou-by.github.io/question_randomizer/)

## Overview
This project is a simple single-page web application that generates random questions based on user preferences. The application allows users to:
- Generate a specified number of random questions (1-10)
- Filter questions by themes using a multi-select dropdown
- Upload custom question sets via a JSON file
- View and flip question cards to reveal answers

## Features
- **Two-panel layout**: Questions are displayed on the left, controls on the right
- **Number of questions selection**: A slider to control how many questions to generate
- **Theme filtering**: Multi-select dropdown to filter questions by theme
- **File upload**: Allows uploading a JSON file with custom questions
- **Interactive question cards**: Clicking a card flips it to reveal the answer
- **Responsive design**: Works on different screen sizes

## How to Use
1. Adjust the slider to set the number of questions to generate.
2. Select themes using the dropdown menu.
3. Click the "Generate Questions" button to display random questions.
4. Click on a question card to flip and see the answer.
5. Optionally, upload a JSON file with custom questions.

## JSON File Format
You can upload a JSON file containing a list of questions. Each question should follow this structure:
```json
[
  {
    "qNumber": 1,
    "question": "What is the capital of France?",
    "answer": "Paris",
    "theme": "Geography"
  },
  {
    "qNumber": 2,
    "question": "Who wrote 'Hamlet'?",
    "answer": "William Shakespeare",
    "theme": "Literature"
  }
]
```
### JSON Fields Explanation:
- `qNumber`: Unique identifier for the question.
- `question`: The text of the question.
- `answer`: The answer to the question.
- `theme`: Category or theme of the question.

## Installation and Setup
No installation is required. Simply open the `index.html` file in a browser.
The site is serving on github pages - [question_randomizer](https://dkavaliou-by.github.io/question_randomizer/)

## Technologies Used
- HTML
- CSS
- JavaScript (Vanilla, no frameworks)

## License
This project is open-source and can be modified and distributed freely.

