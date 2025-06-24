Quiz Game: True or False Challenge
A simple yet engaging True/False quiz game built with Python, featuring questions about computer science and programming. Test your knowledge and see how many you can get right!

Features
10 Computer Science Questions: Carefully selected true/false questions about programming, technology, and computer history.

Score Tracking: Keep track of your correct answers as you progress through the quiz.

Simple CLI Interface: Easy-to-use command-line interface for a seamless experience.

Object-Oriented Design: Clean and modular code structure using Python classes.

How to Run
Clone the Repository:

bash
git clone https://github.com/your-username/quiz-game.git
cd quiz-game
Run the Quiz (Python 3 required):

bash
python main.py
Play the Game:

Read each question carefully.

Type True or False (case-insensitive) to answer.

Your score updates after each question.

Example Output
text
Q.1: The Python programming language gets its name from the British comedy group "Monty Python." (True/False): true
You got it right!
The correct answer was: True
Your current score is: 1/1.

Q.2: Pointers were not used in the original C programming language; they were added later on in C++. (True/False): false
You got it right!
The correct answer was: False
Your current score is: 2/2.
...
File Structure
File	Description
main.py	Entry point - initializes and runs the quiz.
quiz_brain.py	Core quiz logic - handles questions, answers, and scoring.
question_model.py	Defines the Question class to structure each quiz question.
data.py	Contains the question data (10 true/false questions about computer science).
Customization
Want to add your own questions? Just edit data.py following this format:

python
question_data = [
    {
        "question": "Your question here",
        "correct_answer": "True or False",
        "incorrect_answers": ["False or True"]  # Opposite of correct_answer
    },
    # Add more questions as needed
]
Future Improvements
Add multiple-choice questions

Implement a difficulty selector

Add a timer for speed challenges

Create a GUI version (e.g., using Tkinter)

License
This project is open-source and available under the MIT License.

Enjoy the quiz! Feel free to contribute or fork this project for your own versions.