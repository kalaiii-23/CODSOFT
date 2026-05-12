# 🎯 Number Guessing Game

**Interactive Java Console-Based Number Prediction Game**

> Test your guessing skills by finding the randomly generated number within limited attempts.

---

## 📖 Overview

Number Guessing Game is a **console-based Java application** where players attempt to guess a randomly generated number within a fixed number of attempts across multiple rounds.

The game provides hints after each incorrect guess and calculates a final score based on performance.

The application helps demonstrate:

- 🎲 Random number generation
- 🔁 Looping concepts
- 🧠 Conditional logic
- 📥 User input handling
- 🏆 Score calculation system
- ☕ Core Java programming fundamentals

---

## 🗂️ Repository Structure

```plaintext
Numbergame/
├── Numbergame.java     # Main Java source file
└── README.md           # Project documentation
```

---

## 🚀 Quick Start

### Compile the program

```bash
javac Numbergame.java
```

### Run the program

```bash
java Numbergame
```

---

## 🎮 Game Rules

- The system generates a random number between **1 and 100**
- Player gets **5 attempts** per round
- Total **3 rounds**
- After every incorrect guess:

  - Too low → Try higher
  - Too high → Try lower

- Score is awarded based on remaining attempts:

| Attempt Used | Score Awarded |
|-------------|--------------|
| 1st Attempt | 5 Points |
| 2nd Attempt | 4 Points |
| 3rd Attempt | 3 Points |
| 4th Attempt | 2 Points |
| 5th Attempt | 1 Point |

---

## ⚙️ Features

- 🎲 Random number generation
- 🔄 Multiple rounds gameplay
- 📈 Dynamic scoring system
- 💡 Hint system (Too High / Too Low)
- 🏆 Final score display
- ☕ Beginner-friendly Java implementation

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Language | Java |
| Input Handling | Scanner |
| Randomization | Random Class |
| Execution | Console-based |

---

## 📝 How It Works

### **[ ROUND START ]**

A random number is generated between **1 and 100**

### **[ USER GUESS ]**

Player enters a guess

### **[ SYSTEM RESPONSE ]**

The system checks:

- Correct → Win round
- Too low → Prompt retry
- Too high → Prompt retry

### **[ SCORE UPDATE ]**

Points awarded based on attempts used

### **[ FINAL RESULT ]**

Displays total score after all rounds

---

## 🌟 Sample Output

```plaintext
Round 1
Enter your guess (between 1 and 100):
45

Too low! Try again.

Enter your guess:
78

Too high! Try again.

Enter your guess:
65

Congratulations! You guessed the number in 3 attempts.

Your final score is: 3
```
---

*Built with ❤️ using Java to make learning programming fun and interactive.*
