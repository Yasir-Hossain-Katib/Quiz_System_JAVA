# Java Quiz System (SQA)

This is a role-based software system for managing and participating in quizzes, built in Java. It provides two user roles: ***Admin*** and ***Student***. Admins can add questions to a quiz bank, while students can take a random 10-question quiz from the bank and receive their scores with feedback.

---

## Project Description

This software system is designed for managing and conducting MCQ-based quizzes. It allows admins to create and maintain a question bank (`quiz.json` file) and enables students to participate in quizzes by answering randomly selected questions from the bank. The system evaluates student performance and provides results with feedback based on the number of correct answers.

---

## Features

### Admin Role
- Login with admin credentials.
- Add, edit, and save multiple MCQs to a `quiz.json` file.
- Each question includes:
  - 4 options.
  - An answer key.
- Admin can add unlimited questions until choosing to quit.

### Student Role
- Login with student credentials.
- Take a quiz of 10 randomly selected questions from the quiz.json file.
- The system evaluates answers and provides feedback:
    - Score >= 8: "Excellent! You have got [marks] out of 10."
    - Score 5–7: "Good. You have got [marks] out of 10."
    - Score 3–4: "Very poor! You have got [marks] out of 10."
    - Score 0–2: "Very sorry, you are failed. You have got [marks] out of 10."
