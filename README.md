# Who Wants to Be a Millionaire - KBC Quiz Game

[![Python](https://img.shields.io/badge/Python-3.7%2B-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)


## Visual Overview 🖼️

### Game Interface
![Screenshot 2025-03-16 163655](https://github.com/user-attachments/assets/e99cb6bf-1854-4375-8c55-8f1f465fc85d)
*Main game interface with question, lifelines, and prize money display*

### Lifeline Demonstration
| 50-50 Lifeline | Audience Poll | Phone a Friend |
|----------------|---------------|----------------|
| ![Screenshot 2025-03-16 190826](https://github.com/user-attachments/assets/90d143f3-be80-4e2b-b2d6-f1e4a74fb353)|![Screenshot 2025-03-16 190902](https://github.com/user-attachments/assets/71cc1281-db7e-4908-b9f9-74d1df93fd6c)|![Screenshot 2025-03-16 190941](https://github.com/user-attachments/assets/79644817-1814-42ab-8903-1dcc70dcadb8)|

### Win Loss Demonstration
| Win | Lose |
|----------------|---------------|
| ![Screenshot 2025-03-16 193102](https://github.com/user-attachments/assets/89c7be04-0b03-44e5-98a1-7d3e993130d9)|![Screenshot 2025-03-16 193006](https://github.com/user-attachments/assets/dbe3c661-f981-47f7-a2b7-2771f57bd01c)|

A Python implementation of the popular game show "Who Wants to Be a Millionaire" using Tkinter for GUI, featuring lifelines, sound effects, and progressive difficulty levels.

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
  python KBC_Game.py


## Game Structure 🕹️
- **GUI Setup**: Uses Tkinter for window management and widget creation

- **Questions & Answers**: 15 pre-defined Q/A pairs with multiple choices

- **Lifeline System**:

     - **50-50 -** Dynamically removes incorrect options

     - **Audience Poll -** Shows visual percentage bars

     - **Phone-a-Friend -** Text-to-speech reveals correct answer

- **Game Logic:**

  - Progressive question difficulty

  - Dynamic prize money updates

  - Answer validation system

- **Win/Lose Conditions:**

    - Full-screen victory screen for completing all questions

    - Game over screen for incorrect answers

    - Play again functionality

## Technologies Used 💻
- **tkinter**: GUI development

- **pygame.mixer**: Audio management

- **pyttsx3:** Text-to-speech for lifelines

- Progress bars for audience poll visualization

## License 📄
- This project is licensed under the **MIT** License.

## Note:
- Ensure all audio/images from the KBC/ folder are in the correct directory relative to the script. The game uses British pounds (£) as currency, but can be easily modified to other currencies.

## Contribution
- Contributions are welcome! Feel free to submit issues or pull requests.
