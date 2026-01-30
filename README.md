# CLI Study Timer (Pomodoro)
A simple command line based Pomodoro Study Timer built using Python.
This project helps maintain focus and productivity by following a 25 minute focus + 5 minute break cycle directly in terminal.

---

## Overview 
This is a lightweight CLI tool that displays a digital countdown timer in the terminal.
It continuously runs focus and break sessions until the user manually stops the program.

The project is intentionally kept simple and dependency-free so it can later be integrated into larger systems like Draco CLI.

----

## Features
- Digital Timer in MM:SS format
- Automatic Pomodoro cycle
-- 25 minutes Focus
-- 5 minutes break
- Clears terminal every second for live countdown
- Session counter
- Infinite loop until user exits
- Uses only Python standard library

---

## Tech Stack
- Python 3
- Built in modules only(time,os)

---

## How it Works
1. Starts a focus session 25 minutes
2. Displays a live digital timer
3. Automatically switches to break session 5 minutes
4. Repeats the cycle 
5. User can stop anytime using Ctrl + C

---

## How to Run
1. Clone the repository
2. Open terminal in the project directory
3. Run the program:
```bash
python study_timer.py
```

---

## File Structure
study_timer.py
README.md

---

## Customization
You can easily modify the timer duration by changing these values in the code:
FOCUS_TIME = 25*60
BREAK_TIME = 5*60

---

## Future Improvements
- Sound alerts on session completion
- User-defined focus and break time
- Session logging
- Integration with Draco CLI
- Pause/resume functionality

---

## Author
Aryan Sonsurkar
Computer Engineering Student
Learning Python,CLI tools,and automation