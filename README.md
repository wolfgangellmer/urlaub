This repository hosts fun quizzes for our family to play, organized by location.  
Each location has its own folder and quizzes, with images and other assets.

## Structure

- `quizzes/LOCATION/quizN.html`: Quizzes for each location.
- `templates/quiz_template.html`: Template for new quizzes.
- `scripts/generate_quiz.py`: Helper script for generating quizzes (optional).
- `quizzes/locations.json`: Metadata for locations and quizzes.

## How to add a new quiz

1. Copy the template from `templates/quiz_template.html`.
2. Paste it into the relevant location folder in `quizzes/`.
3. Rename it (e.g., `quiz2.html`) and fill in your questions.