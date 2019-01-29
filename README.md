# Tic-Tac-Toe
As a part of learning Javascript, i have created this project. Its a popular tic-tac-toe game and by observing how game works i have made this game unbeatable.

Algorithm
First turn is given to human('x') player then system('0') takes its turn.

Before taking any move, system always checks for two adjacent '0' on board and if it finds one it will mark '0' there. I call this 'system attacking strategy' to take over the game.

If attacking is not the case then system will check for two adjacent 'x' on board and in case if it finds such pair it will mark '0' there, i call this 'system defending strategy'.

And in rest cases, system will take some intelligent moves according to how user is playing.
