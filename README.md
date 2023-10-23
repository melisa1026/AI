# AI
Key Features: <br>
Game Modes: The code supports several game modes, including Computer vs. Computer (AI attacker vs AI defender), Attacker vs Defender (both human players), Attacker vs. Computer (human attacker vs AI defender), and Computer vs. Defender (AI attacker vs human defender). <br>
Game Broker: This feature enables automated moves between two computer players while playing the game using a game broker. <br>
Unit activities include moving to neighboring cells, destroying themselves, fighting other units, and restoring allies. <br>
Game Logic: To validate moves, determine winners, and keep track of game statistics, game logic is included in the code. <br>
User Interface: For manual gameplay, it offers a straightforward text-based user interface that let players to enter their moves via the command line. <br>
<br>
Game Flow: <br>
Each player makes a move in turn. <br>
The game verifies a move's authenticity and takes appropriate action. <br>
Players have the option to repair their own units, assault rival units, or move units. <br>
The game goes on until either an AI unit from either the attacker or defender's side is destroyed (whoever's AI is alive wins), or the maximum number of turns is reached which would make the defender the winner. <br>
<br>
Output: <br>
The program creates a game trace file (gameTrace.txt) that contains a record of every move made by each player, the condition of the game board following each move, and the game's outcome along with some statisitcs if one of the player's is the computer. <br>
<br>
To run the code: <br>
Please open the AI folder in your chosen python ide. <br> 
Then, input the maximum amount of time you would like and then input the maximum number of turns you want. <br>
Then, input "on" if you want the alpha-beta to be on or "off" if you want the alpha-beta to be off. <br>
Then, input the play mode you want to play in so either "H-H", "H-AI", "AI-H", "AI-AI". <br>
Then, after that if you have chosen a playmode that is not H-H, then input the heuristic you want so either "e0", "e1", or "e2" and after that input the maximum depth you want (an integer). <br>
If you have chosen a mode that involves a human playing then follow the below steps on how to play: <br>
To perform an action, input the source coordinate of the unit you want to perform the action on followed by a comma followed by the destination coordinate of your action. <br>
For example, if you want to move a unit to an empty destination write: C4,C3 or c4,c3. This is the same format you can follow to attack or repair another unit. <br>
If you want to self-destruct a unit, write: c4,c4
