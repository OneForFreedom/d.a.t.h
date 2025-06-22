# DEFEND AGAINST THE HACKERS

## Overview

**DEFEND AGAINST THE HACKERS** is a fast-paced browser game that tests your typing speed and accuracy. Letters fall from the top of the screen, and your goal is to defend yourself by typing the corresponding letters before they reach the bottom. The game adjusts difficulty based on your typing speed and can be played either with random letters or from a custom uploaded `.txt` file.

---

## Features

- **Two Game Modes:**
  - **Random Mode:** Letters are randomly generated from A-Z.
  - **Custom Mode:** Upload a `.txt` file and play with letters from your own text.
  
- **Life Bar:** Losing letters costs life points. Gain life by hitting letters accurately.
- **Scoring System:** Points awarded based on timing and accuracy; penalties for misses or wrong key presses.
- **Dynamic Difficulty:** Game speed gradually increases as you progress.
- **Responsive Design:** Clean, minimalist interface with green-on-black “hacker” theme.

---

## How to Play

1. **Start Screen:**
   - Upload a `.txt` file if you want to play with custom letters.
   - Set your base words per minute (WPM) speed.
   - Choose between playing with random letters or your uploaded file.
   
2. **Gameplay:**
   - Letters will fall from the top of the screen.
   - Type the letter before it hits the bottom red zone.
   - Accurate hits increase your score and life; misses reduce life.
   
3. **Game Over:**
   - The game ends when your life bar reaches zero.
   - You can then return to the home screen to try again.

---


## Technical Details

- Letters spawn at intervals calculated based on the chosen WPM.
- The falling speed of letters increases progressively to raise difficulty.
- The life bar and score update dynamically based on player performance.
- Keyboard events listen for typed letters and handle hits or misses accordingly.
- Custom letters are sanitized to include only alphabetical characters and converted to uppercase.

---

## Limitations & Notes

- Only alphabetical characters A-Z are supported in gameplay.
- Custom text files should contain sufficient alphabetical content for best experience.
- The game relies on keyboard input and may not be accessible on touch-only devices.
