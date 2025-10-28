#  Number Guesser — Web3Bridge Exam

A simple and interactive number-guessing game built with **vanilla JavaScript**.  
Try to guess the secret number between **1 and 100** before your attempts run out.

---

##  How to Play

1. Select a **difficulty level** (Easy, Medium, Hard, or Insane).
2. Enter a number between **1 and 100** and click **Guess**.
3. The game will tell you if your guess is:
   - **Too high** → try a smaller number  
   - **Too low** → try a bigger number  
   - **Correct** → you win!
4. Watch your **remaining attempts** at the top.
5. Click **Restart** to start a new round or **Reveal** to show the secret number.

---

## Features

- Random secret number between 1 and 100  
- Difficulty levels (Easy, Medium, Hard, Insane)  
- Instant feedback (too high, too low, correct)  
- Restart and Reveal buttons  
- Guess history tracking  
- Input validation and error handling  
- Clean, modern UI with subtle animations  

---


---

## ⚙️ Git Workflow

Follow standard Git best practices:

```bash
# Create a new feature branch
git checkout -b feat/add-ui

# Make your changes and commit
git add .
git commit -m "feat: add difficulty selector"

# Push to GitHub
git push -u origin feat/add-ui

