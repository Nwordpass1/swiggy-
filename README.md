Multiplayer Card Game
This is a multiplayer card game designed to be played with up to 4 players. The game has a deck of 52 cards with different types of cards such as number cards and action cards.

Game Rules
Each player starts with a hand of 5 cards. Players take turns playing cards from their hand, following a set of rules that define what cards can be played when. A player can only play a card if it matches either the suit or the rank of the top card on the discard pile. If a player cannot play a card, they must draw a card from the draw pile. If the draw pile is empty, the game ends in a draw and no player is declared a winner. The game ends when one player runs out of cards who is declared the winner.

Bonus Rules
Aces, Kings, Queens, and Jacks are action cards. When one of these is played, the following actions occur:
Ace (A): Skip the next player in turn.
King (K): Reverse the sequence of who plays next.
Queen (Q): +2.
Jack (J): +4.
Note: Actions are not stackable, i.e., if Q is played by player 1, then player two draws two cards and cannot play a Q from his hand on that turn even if available.
Technologies Used
This game was implemented using Node.js, and the following packages were used:
readline-sync: for reading input from the command line.
colors: for adding colors to the console output.
How to Play
Clone the repository from GitHub.
Install Node.js on your machine if it is not already installed.
Open a command prompt in the root directory of the project.
Run the command npm install to install the required packages.
Run the command npm start to start the game.
Testing
The game has been thoroughly tested using Jest, a JavaScript testing framework. The test files can be found in the __tests__ directory. To run the tests, run the command npm test in the root directory of the project.
