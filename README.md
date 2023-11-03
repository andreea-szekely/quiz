# Terminal Quiz App 🧠

Welcome to the **Terminal Quiz App**, a Python project created with the purpose of enhancing my OOP knowledge.

## Project Details

### Learning Purpose

- Language: Python
- Technology: Python
- Focus Area: OOP (Object-Oriented Programming)

### Project Structure

The **Terminal Quiz App** consists of the following key components:

1. **data.txt** - A data file that stores the quiz questions as a list of dictionaries.
2. **question_model.py** - Defines the `Question` class, which represents a quiz question with attributes `text` and `answer`.
3. **quiz_brain.py** - Encapsulates the quiz functionality within the `QuizBrain` class. It includes methods like `still_has_questions` to check if there are any questions left and `next_question` to display the next question and check for the correct answer.
4. **quiz_main.py** - The main program file. After importing the required modules, it creates a `question_bank` list containing questions modeled by the `Question` class. The program initializes the `QuizBrain` object, passing the `question_bank`, and runs the quiz until there are no questions left.

## How It Works

The **Terminal Quiz App** presents the user with true or false questions from the provided dataset. The user answers by typing 'true' or 'false' within the command line. If the user's answer is correct, they earn 1 point. The quiz app progresses through all the questions, and at the end, it displays the user's final score.

## To-Do List (Work in Progress)

1. **Shuffle Questions**: Implement a question shuffling mechanism to enhance the randomness and unpredictability of questions.
2. **Trivia API**: Integrate a Trivia API to provide a broader and more diverse set of questions for an improved user experience.
3. **Simple-term-menu**: Implement the `simple-term-menu` library to create an interactive and user-friendly menu for the quiz, enhancing the user experience.

## How to Get Started

To get started with the **Terminal Quiz App**, follow these steps:

1. Make sure you have Python installed on your system.
2. Download the project files.
3. Run `quiz_main.py` to start the quiz.

Have fun testing your knowledge and challenging yourself with our Terminal Quiz App!

Happy quizzing! 📚
