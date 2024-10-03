# **Sudoku Game**

#### _A web-based Sudoku game built with JavaScript, Bootstrap, and jQuery._

#### By Emmanuel Okpiaifo

## **Description**

The **Sudoku Game** is an interactive web-based puzzle game that allows players to solve randomly generated Sudoku puzzles. Players can select between **easy**, **medium**, and **hard** difficulty levels. The game provides a grid where players can input numbers to solve the puzzle, along with a "Check Puzzle" feature to validate their solution.

This game is built using **JavaScript**, **Bootstrap**, and **jQuery** to create a responsive, dynamic Sudoku puzzle that includes smooth animations and user feedback when checking the solution.

## **Setup/Installation Requirements**

1. Clone this repository to your local machine:
    ```bash
    git clone [repository-url]
    ```
2. Navigate to the project directory:
    ```bash
    cd sudoku-game
    ```
3. Install the necessary dependencies using npm:
    ```bash
    npm install
    ```
4. Start the development server:
    ```bash
    npm run start
    ```
5. Open your browser and play the game at:
    ```bash
    http://localhost:8080
    ```

## **Gameplay Rules**

### **Objective**
The objective of the game is to correctly fill the 9x9 Sudoku grid with numbers from 1 to 9 so that:
- Each row contains the numbers 1 to 9, without repetition.
- Each column contains the numbers 1 to 9, without repetition.
- Each 3x3 sub-grid contains the numbers 1 to 9, without repetition.

### **Game Features**
- **Difficulty Selection**: Players can select between **easy**, **medium**, and **hard** puzzles.
- **Sudoku Grid**: The 9x9 grid allows users to click cells and input numbers using the number buttons.
- **Timer**: The game timer starts when the puzzle is generated.
- **Check Puzzle**: Players can check their solution by clicking the "Check Puzzle" button. Correct cells are highlighted in green, and incorrect cells are highlighted in red.
- **Reset Button**: Resets the puzzle and allows players to try again with a new randomly generated puzzle.

## **Technologies Used**

- **JavaScript**
- **jQuery**
- **Bootstrap**
- **CSS**
- **HTML**
- **Webpack**

## **Known Bugs**

- None currently known. Please report any issues.

## **Support and Contact Details**

For questions, comments, or issues, please contact **emmaokpiaifo@gmail.com**.

## **License**

*This software is licensed under the MIT license.*
