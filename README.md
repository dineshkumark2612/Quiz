# 🧠 Java Quiz Project

A simple **console-based Quiz Application built using Core Java**.

The application displays a set of Java-related questions, accepts answers from the user through the console, and calculates the final score based on the user's answers.

## 📌 Project Overview

This project was created to practice **Core Java and Object-Oriented Programming concepts**.

The quiz contains multiple-choice questions related to Java data types. The user enters an answer for each question, and the application checks the answers and displays the final score.

## ✨ Features

* Displays multiple Java-related questions
* Displays four options for each question
* Accepts answers through the console
* Stores user selections
* Automatically checks the answers
* Calculates the final score
* Displays the user's score at the end

## 🛠️ Technologies Used

* **Java**
* **Core Java**
* **Object-Oriented Programming (OOP)**
* **Java Scanner**
* **Arrays**
* **IntelliJ IDEA**

## 📂 Project Structure

```text
Quiz_Project/
│
├── Questions.java
├── QuestionServices.java
├── Main.java
└── README.md
```

### `Questions.java`

The `Questions` class represents a single quiz question.

It contains:

* Question ID
* Question text
* Four options
* Correct answer

The class uses **private variables** with **getters and setters**, demonstrating the concept of **Encapsulation**.

### `QuestionServices.java`

The `QuestionServices` class manages the quiz.

It:

* Creates the quiz questions
* Displays questions and options
* Accepts user answers
* Stores user selections
* Checks the answers
* Calculates the score

### `Main.java`

The `Main` class contains the `main()` method and starts the quiz.

```java
QuestionServices questionService = new QuestionServices();

questionService.playQuiz();

questionService.printScore();
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project

Open the project using **IntelliJ IDEA** or another Java IDE.

### 3. Run `Main.java`

Run the `main()` method in:

```text
Main.java
```

### 4. Answer the questions

The program will display each question and its options.

Enter your answer in the console.

### 5. View your score

After answering all questions, the application will calculate and display your score.

Example:

```text
Question no. : 1
size of int
2
6
4
8
4

...

Your score is : 5
```

## 🧩 Java Concepts Used

This project demonstrates several important Core Java concepts:

### 1. Classes and Objects

The project contains classes such as:

```java
Questions
QuestionServices
Main
```

Objects are created using:

```java
QuestionServices questionService = new QuestionServices();
```

### 2. Encapsulation

The fields in `Questions` are declared as `private`:

```java
private int id;
private String question;
private String answer;
```

Access is provided through getters and setters.

### 3. Constructor

The `Questions` class uses a parameterized constructor:

```java
public Questions(int id, String question, String opt1,
                 String opt2, String opt3, String opt4,
                 String answer)
```

This allows a question object to be initialized with its required data.

### 4. Arrays

The application stores questions using an array:

```java
Questions[] questions = new Questions[5];
```

User answers are stored using:

```java
String[] selection = new String[5];
```

### 5. Enhanced For Loop

The application uses an enhanced `for` loop to iterate through questions:

```java
for (Questions q : questions) {
    // ...
}
```

### 6. Scanner

The `Scanner` class is used to receive input from the user:

```java
Scanner sc = new Scanner(System.in);
```

### 7. Conditional Statements

The application compares the user's answer with the correct answer:

```java
if (answer.equals(userAnswer)) {
    score++;
}
```

### 8. Methods

The application separates functionality into methods:

```java
playQuiz()
printScore()
```

This makes the code easier to organize and understand.

## 🎯 Current Quiz Topics

The current questions focus on **Java primitive data types**, including:

* `int`
* `double`
* `char`
* `long`
* `boolean`

## 🔮 Future Improvements

The project can be improved by adding:

* Randomized questions
* Randomized options
* More quiz questions
* Different difficulty levels
* Timer for each question
* Multiple quiz categories
* Score percentage
* Correct answer review
* User name and score history
* Leaderboard
* Graphical User Interface (GUI)
* Database integration
* Login and registration system

## 📚 Learning Purpose

This project was developed as a **Core Java practice project** to strengthen understanding of:

* OOP
* Encapsulation
* Constructors
* Arrays
* Methods
* Loops
* Conditional statements
* User input
* Object creation
* Basic application structure

## 👨‍💻 Author

**Your Name**

Java Developer | Core Java | OOP | JDBC | MySQL

---

⭐ If you find this project useful, feel free to star the repository!


