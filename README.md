# AI
Key Features:
Game Modes: The code supports several game modes, including Computer vs. Computer, Defender vs. Computer, Attacker vs. Computer, and Computer vs. Attacker.
Game Broker: This feature enables automated moves between two computer players while playing the game using a game broker.
Unit activities include moving to neighboring cells, destroying themselves, fighting other units, and restoring allies.
Game Logic: To validate moves, determine winners, and keep track of game statistics, game logic is included in the code.
User Interface: For manual gameplay, it offers a straightforward text-based user interface that let players to enter their moves via the command line.

Game Flow:
Each player makes a move in turn.
The game verifies a move's authenticity and takes appropriate action.
Players have the option to repair their own units, assault rival units, or move units.
The game goes on until either one person prevails, or a predetermined maximum number of turns are taken.

Output:
The program creates a game trace file (gameTrace.txt) that contains a record of every move made by each player, the condition of the game board following each move, and the game's outcome.
