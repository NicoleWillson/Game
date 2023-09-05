# Game
MIT tictactoe assignment

Features I'd like to implement: 

Lock the board on a win - possibly automatically reset it
Keep track of wins/losses for each player
Add a "coin" flip to see which player goes first

How would I implement them?

1. Simply check if there is a winner before allowing a turn to complete.

2. Keep a separate array of wins adding the player's "name" when they win and adding a reset button to set all the other variables back to the beginning states

3. Add a coin flip function that uses (Math.floor(Math.random) * 2) % 2 and set the player's turn to that value.
