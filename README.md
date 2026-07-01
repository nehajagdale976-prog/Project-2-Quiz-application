# Project-2-Quiz-application
Developed a Quiz Application to provide an interactive learning experience through topic-based quizzes. The application includes features like question navigation, score tracking, and result analysis using a simple and responsive interface.
questions = {
    "What is the capital of India?": "Delhi",
    "2 + 2 = ?": "4",
    "Python is a ?": "Programming Language"
}

score = 0

for question, answer in questions.items():
    user_answer = input(question + " ")
    if user_answer.lower() == answer.lower():
        score += 1
        print("Correct!")
    else:
        print("Wrong!")

print("Final Score:", score)

OUTPUT:
What is the capital of India? DELHI
Correct!
2 + 2 = ? 4
Correct!
Python is a ? PROGRAMMING LANGUAGE
Correct!
Final Score: 3
Colab paid products - Cancel contracts here
