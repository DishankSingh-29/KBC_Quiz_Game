# Who Wants to Be a Millionaire - KBC Quiz Game

[![Python](https://img.shields.io/badge/Python-3.7%2B-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

A Python implementation of the popular game show "Who Wants to Be a Millionaire" using Tkinter for GUI, featuring lifelines, sound effects, and progressive difficulty levels.

![Screenshot 2025-03-16 163655](https://github.com/user-attachments/assets/e99cb6bf-1854-4375-8c55-8f1f465fc85d)

## Features ✨

- **Immersive GUI**: Built with Tkinter for a authentic game show experience
- **3 Lifelines**:
  - 50:50 - Eliminates two wrong answers
  - Audience Poll - Visual voting percentages
  - Phone-a-Friend - Text-to-speech assistance
- **Sound Effects**: Background music and audio cues
- **Progressive Difficulty**: 15 increasingly challenging questions
- **Win/Lose Screens**: Interactive end-game scenarios
- **Prize Tracking**: Visual progression through prize amounts

## Prerequisites 📋
- Python 3.6+
- Required libraries:
  ```bash
  pip install pygame pyttsx3

## File Structure 📁
```
Who-Wants-To-Be-A-Millionaire/
├── KBC/
│   ├── audiencePole.png
│   ├── calling.mp3
│   ├── center.png
│   ├── happy.png
│   ├── kbc.mp3
│   ├── Kbcwon.mp3
│   ├── lay.png
│   ├── phone.png
│   ├── phoneAFriend.png
│   ├── sad.png
│   └── 50-50.png
├── main.py
└── README.md
```

## How to Run 🚀
- Clone the repository:
   ```bash
  git clone https://github.com/DishankSingh-29/Who-Wants-To-Be-A-Millionaire.git

- Navigate to the project directory:
  ```bash
  cd Who-Wants-To-Be-A-Millionaire
  
- Run the game:
  ```bash
  python main.py
