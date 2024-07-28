NAME : PRIYANSHU MUNDA

COMPANY : CODETECH IT SOLUTION

ID : CT4CP3954

DOMAIN : C LANGUAGE TASK 

DURATION : JULT TO AUGUST 2024

MENTOR : MUZAMMIL AHMED





 OVERVIEW:


 
The program is an interactive iq test game implemented in c. It consists of multiple-choice questions and provides feedback based on the user's score. The program makes use of console input and output for interaction and navigation through menus.

KEY COMPONENTS
1.  HEADERS AND DEFINITIONS:
   - Includes standard headers like `stdio.h`, `conio.h`, `ctype.h`, and `stdlib.h`.
   - Includes a custom header `"gotoxy.h"` for setting cursor positions in the console.
   - Defines `ESC` as 27 (ASCII value for the Escape key).

2.  FUNCTION DECLARATIONS:
   - `void mainMenu();`
   - `void gamePlay();`
   - `void giveFeedback(int score);`

3.  MAIN FUNCTION:
   - Calls `mainMenu()` to display the main menu.

4. MAIN MENU FUNCTION (`mainmenu`):
   - Clears the screen and displays a welcome message and menu options.
   - Waits for user input and processes the choice:
     - 'S': Starts the game by calling `gamePlay()`.
     - 'Q' or ESC: Exits the program.
     - Any other key: Displays an error message and prompts the user to re-enter a valid option.

5.  GAME PLAY FUNCTION (`gamePlay`):
   - Initializes the questions, options, and correct answers.
   - Iterates through the questions, displaying them one by one.
   - Takes the user's answer and checks if it is correct.
   - Updates the score based on the user's answers.
   - After all questions are answered, displays the final score and calls `giveFeedback()` to display feedback based on the score.
   - Returns to the main menu after displaying the feedback.


6.  FEEDBACK FUNCTION (`giveFeedback`):
   - Takes the user's score as an argument.
   - Displays feedback based on the score:
     - 8-10: "EXCELLENT"
     - 5-7: "GOOD"
     - 1-4: "BAD"

 FEATURES
- **MAIN MENU**: Provides options to start the game or quit.
- **QUESTIONS AND OPTIONS**: Displays questions and multiple-choice options in a formatted manner.
- **ANSWER VALIDATION**: Ensures that the user inputs a valid answer (a, b, c, or d).
- ** TRACKING SCORE **: Keeps track of the user's score.
- **FEEDBACK**: Provides feedback based on the user's score after the quiz is completed.
- **USER INTERACTION**: Uses `getch()` for user input, allowing for single-character inputs without the need to press Enter.

### USAGE
- Compile the program using a C compiler, ensuring that `gotoxy.h` is included in the project.
- Run the compiled program.
- Navigate the menu using the specified keys.
- Answer the questions as they appear.
- Receive feedback based on your performance in the quiz.

### EXAMPLE USAGE
1. Start the program.
2. Press 'S' to start the game.
3. Answer the questions by pressing 'a', 'b', 'c', or 'd'.
4. After the last question, see your score and feedback.
5. Press any key to return to the main menu.
6. Quit the program by pressing 'Q' or ESC from the main menu.

This program is a simple yet effective demonstration of a console-based quiz game, utilizing basic C programming concepts such as arrays, loops, conditionals, and functions for modularity and readability



![Untitled-1-Red Street Play Theatre Presentation](https://github.com/user-attachments/assets/b47ac6e6-57b3-429b-a0bb-30b3e39c7c73)


