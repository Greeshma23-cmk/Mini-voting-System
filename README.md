# Mini Voting System

This project is an Embedded C-based Mini Voting System developed for basic election/voting applications using button inputs and displays.  
It allows users to cast votes and displays the voting results in real time.

## Features
- Simple user interface using buttons.
- Vote counting for multiple candidates.
- Real-time display of voting results.
- Reset functionality for new voting sessions.

## Tools & Technologies Used
- Embedded C
- Microcontroller (example: STM32 / LPC2148 / any MCU)
- LCD Display / 7-Segment Display
- Push Button Modules

## Project Structure
- main.c - Main application code
- voting.c - Voting logic (vote casting and counting)
- display.c - Displaying votes and results
- button.c - Handling button inputs
- README.md - Project documentation

## How to Run
1. Flash the code into the microcontroller.
2. Connect push buttons for vote casting and LCD/Display module.
3. Press buttons to cast votes for candidates.
4. Display will show live vote count and final results.

## Future Improvements
- Add password-protected admin mode to reset votes.
- Implement a timer for auto-closing the voting session.
- Introduce wireless modules for remote voting.
- Display percentage results and winner announcement.
- 
## Author
Gollapalli Greeshma

## Project Link
- [GitHub Repository Link](https://github.com/Greeshma23-cmk/Mini-voting-System)

