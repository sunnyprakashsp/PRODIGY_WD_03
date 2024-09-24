![Screenshot 2024-09-24 182554](https://github.com/user-attachments/assets/cf012b27-7934-425f-aeaa-cb4220c95a31)
![Screenshot 2024-09-24 182639](https://github.com/user-attachments/assets/97250081-b62d-4bee-b194-6b3853c54d49)
![Screenshot 2024-09-24 183000](https://github.com/user-attachments/assets/5adaa35a-b90f-40ab-9d6d-e02f22694363)
![Screenshot 2024-09-24 183115](https://github.com/user-attachments/assets/657fd7ca-fef1-40e7-8305-ba987e3cc0e2)

##Tic-Tac-Toe Game

Project Description
This project is a simple implementation of the classic Tic-Tac-Toe game using HTML, CSS, and JavaScript. The game is played between two players (X and O) and runs entirely in the browser. The objective is to get three marks (either "X" or "O") in a row (horizontally, vertically, or diagonally).


Features
Two Player Mode: Alternating turns between two players.
Responsive UI: Designed to work well on desktops and mobile devices.
Winner Detection: Automatically detects when a player wins or if there’s a draw.
Reset Game: Includes an option to reset the game after completion.


Technologies Used
HTML: Provides the basic structure of the game.
CSS: Styles the game board and provides responsive design.
JavaScript: Handles the game logic, including player turns, winner detection, and resetting the game.

How to Play
The game is played on a 3x3 grid.
Player 1 is X, and Player 2 is O.
Players take turns placing their marks in empty squares.
The first player to align three of their marks (X or O) either horizontally, vertically, or diagonally wins.
If all nine squares are filled and no player has three marks in a row, the game ends in a draw.

Setup and Installation: 
Clone or download this repository to your local machine:

bash
Copy code: git clone https://github.com/sunnyprakashsp/tic-tac-toe.git

Navigate to the project directory:

bash
Copy code: cd tic-tac-toe

Open the index.html file in your browser to start the game:

bash
Copy code: open index.html

Project Structure
plaintext
Copy code
tic-tac-toe/
│
├── assets/
│   └── images/
│       └── (any images like X or O icons can go here)
├── css/
│   └── styles.css      # Contains all the styles for the game board
├── js/
│   └── script.js       # Contains the main game logic and functions
├── index.html          # Main file that includes the structure of the game
├── README.md           # Project documentation
└── LICENSE             # License information (optional)

File Breakdown
index.html: Defines the structure of the Tic-Tac-Toe grid and includes references to the CSS and JavaScript files.
styles.css: Contains the styles for the game, such as the grid layout, game colors, hover effects, and responsive design.
script.js: Implements the game logic, including player turns, win condition checks, draw detection, and game reset functionality.

Game Logic Overview (JavaScript)
Turn Switching:

A variable keeps track of whose turn it is (X or O).
This variable toggles between X and O after each move.
Win Checking:

After each move, the game checks if the current player has won by comparing their selected squares to predefined winning combinations.
Draw Condition:

If all squares are filled and no player has won, the game declares a draw.
Reset Functionality:

Players can reset the game to start a new round without reloading the page.

Future Improvements

Add a single-player mode where a player can play against the computer using a simple AI.

Add animations for winning sequences and more sophisticated UI interactions.

Implement score tracking across multiple games.

Allow players to choose their symbol (X or O) at the beginning of the game.

License
This project is licensed under the MIT License. Feel free to modify and distribute as needed.

Contact
For any questions or suggestions, feel free to contact me at sunny8jankr@gmail.com
