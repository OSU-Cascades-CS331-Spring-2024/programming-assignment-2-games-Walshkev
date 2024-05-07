[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/i3cjXgnP)
# othello-python
Starter Code for Othello AI Agent Programming Assignment

Originally created by Erich Kramer at OSU for Professor Rebecca Hutchinson.
Cleaned up by Rob Churchill.

How to play a game:

1. Run `python3 game_driver.py [player_type] [player_type]`.
2. Choose `human`, or `minimax` as the player types.
3. Follow the prompts to choose where to place stones.








Write up for AI project 2 
1.	Simulate four games between yourself and the minimax player on a 4x4 board, with the depth parameter set to 5, 3, 2, and 1, respectively.
a. What were the results of each game?

-	5 I lost everything total time : 0.003000020980834961
 
-	3 tie game total time : 0.004050254821777344
 
-	2 I won  the computer took a total of total time : total time : 0.003186464309692383
 
-	1 I won the computer took a total of 	
o	total time: 0.0027158260345458984 
 

b. Did the minimax player’s moves change when the depth was limited to smaller
and smaller values?

	The minimax definitely played better the larger the depth was to the point when the depth was set to 5 I only had 2 possible moves to choose from and they were both bad options. I think this helped with the time complexity of the higher depth because it does not have to check that many paths during recursion. Also, I think that the time is reduced in total because I am running it on a very fast computer. 

c. What was the average time per move for each of the games? Comment on why
there is or is not a difference.
2. Simulate two games between yourself and the minimax player on an 8x8 board, with the
depth parameter set to 5 and 2.


a. What were the results of each game?
2.	2.	 I won and the total time taken was total time : 0.026241302490234375 
 
I also prioritized corner plays which I did not program into a heuristic in the algorithm. 
The average time per turn for the AI was 0.00087471

Depth 5 –
  
Average time taken was 3.1569 the longest time taken was over 20 seconds the beginning and end the middle took forever i should have terminated it but i wanted to see it play out. 



b. Did the minimax player’s moves change when the depth changed?
Yes, even when I tried to prioritize the corners it would not allow me to work that way without giving up most of my tiles it would also restrict my movements more towards the end of the game more. 
c. What was the average time per move for each of the games? Comment on why
there is or is not a difference

The averages are 2 depth had 0.00087471 and the 5 depth had an average time of 3.1569 seconds. This make total sense because say there is 3 choices per tern the depth 2 would only have the recures over 9 leaf nodes where for the 5 depth is 243  leaves that it would have to go through since I am not doing alpha beta pruning. 



3^60  is  much much  more and that is what it would have to do for the entire game. 
