# Quizzle App

Quizzle is a quiz application built using Python's **Tkinter** library for the graphical interface. It fetches **True or False** questions from the [Open Trivia Database API](https://opentdb.com/api_config.php), providing a simple and fun way for users to test their knowledge.

## Features

- **10 True or False Questions**: Each quiz session consists of 10 randomly generated questions from the Open Trivia Database.
- **Real-time Scoring**: The score updates in real-time as you answer each question.
- **Visual Feedback**: Correct answers show a blue highlight, while incorrect answers display a red highlight.
- **Final Score Display**: After answering all 10 questions, the app presents the user's final score.

## Getting Started

### Prerequisites

- Python 3.x
- Install Tkinter if not already included (Tkinter usually comes pre-installed with Python on most systems)
- Install `requests` library to fetch data from the API

```bash
pip install requests
```

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yingliu1206/Quiz-App.git
   cd Quiz-App
   ```

2. **Running the Application**:
   ```bash
   python main.py
   ```

### Interface

* Correct Answer
<img width="340" alt="image" src="https://github.com/user-attachments/assets/c958739a-74c7-4b23-b617-f73de49778b0">

* Wrong Answer
<img width="340" alt="image" src="https://github.com/user-attachments/assets/460f6b92-28af-4094-a2c7-6c3f8243bb6e">

## Usage

1. Open the app to start the quiz.
2. Each question appears with "True" and "False" options.
3. Select an answer to see if you're correct:
   - **Correct Answer**: Background changes to green, and your score increases.
   - **Incorrect Answer**: Background changes to red.
4. After 10 questions, your final score is displayed.

## Technologies Used

- **Tkinter**: For the GUI.
- **Open Trivia Database API**: Fetches random True/False questions.
- **Python**: Core programming language for app logic.

## Acknowledgments
- [100 Days of Code: The Complete Python Pro Bootcamp - Udemy](https://www.udemy.com/course/100-days-of-code) for the inspiration and guidance.
