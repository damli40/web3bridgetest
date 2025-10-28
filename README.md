Number Guesser — Web3Bridge Exam

A simple, polished number guessing game. Guess the secret number between 1 and 100 before your attempts run out.

How to Play

1. Pick a difficulty.
2. Enter a number from 1 to 100 and hit Guess.
3. Read the feedback:
4. Too high → try smaller.
5. Too low → try bigger.
6. Correct → you win!

Attempts left are shown at the top. Use Restart to play again. Reveal gives up the answer.

Features

1 Random secret number in 1–100
2 GUI with input, buttons, feedback, and guess history
3 Attempts limit with live counter
4 Win/Loss end state message
5 Restart without page reload
6 Difficulty levels (10/7/5/3 attempts)
7 Strong input validation and a11y
8 Subtle animations for better UX

Error Handling

Non-numbers, decimals, empty input, or values outside 1–100 are blocked with friendly messages.

Game state cannot break on bad input; controls disable when finished.

Dev & Tests (optional bonus)

Development is vanilla HTML/CSS/JS in a single file (index.html).

Optional unit tests: extract validateInput into /src/app.js and test with Vitest/Jest.

Git Workflow

Use feature branches (feat/…, fix/…, test/…)

Open PRs for each set of changes

Merge to main for releases

Tag releases if desired

Hosting

GitHub Pages: Settings → Pages → Branch: main, folder: /root

Or deploy via Vercel/Netlify
