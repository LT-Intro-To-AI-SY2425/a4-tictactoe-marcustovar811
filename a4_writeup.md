# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?

The most difficult part of tic-tac-toe was making sure the method that checked all the possible ways that somebody could win functioned properly. I wasn't used to some of the python ways that could be implemented to solve the problem. I was struggling to make sure it worked diagonally. 

2. Explain how you would add a computer player to the game.

To add a computer player to the game, you could have a method that has a randomizer that works from 0 to 8 and if it isn't occupied by a player's mark then it could be replaced with the player's opposite mark. This could be called after the player makes a move. 

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.

You might be able to add a database that has the best tic tac toe moves based off the first move. Then, you could have the computer check the database and have it go from there based off the player's first move. If the player's first move is on a specific spot, then the computer could check the best move to go from there would be. 