# Simon Says Game  
A memory-based game implemented on the STM32 Nucleo board

## Description  
Simon Says is a classic memory game that tests a player's ability to recall and reproduce a growing sequence of lights. In this project, I designed and built a hardware version of the game using an STM32 Nucleo board. The game uses four LEDs for visual output and four buttons for user interaction. As the game progresses, the player is required to mimic a randomly generated sequence of LED flashes, with each round adding a new step to the sequence. The objective is to successfully complete all 10 rounds without making a mistake.

This project was a fun way to blend game design with embedded systems. It challenged me to think critically about timing, input handling, user feedback, and the logic behind game progression.

## What I Learned  
Working on this project helped me gain a deeper understanding of embedded system fundamentals, particularly how to manage GPIO inputs/outputs and create responsive, real-time interactions between hardware and software. I also learned how to implement logic that feels natural to the user — like immediate feedback on button presses and clear visual cues. More broadly, it reinforced how satisfying it is to bring a simple idea to life through hardware.

## Tools & Technologies  
- STM32 Nucleo board   
- Embedded C  
- LEDs and buttons for user interaction

## Demo  
A short video demonstration of the game in action is included below.  
*(https://drive.google.com/file/d/1x99aBy6pEy-t-W9Vb2K3S51T2HtA30lC/view?usp=sharing)*

## Final Thoughts  
This project gave me the chance to explore both the technical and creative aspects of embedded systems. It was exciting to build something hands-on that’s interactive and fun to play. I'm looking forward to expanding on it in the future — maybe with difficulty levels, sound feedback, or even a display screen.
