# Lab-04
Team 6 

clen790
dxu970
astu864

Update this README to include your team name and team members. Don't forget to record all your answers to lab 04 here.

1. String, Integer, Boolean
2.
3.
4. line 151 - if turn == 'player'
5. line 150 - end - while gameIsPlaying
6. line 121 move = chooseRandomMoveFromList(board, [1, 3, 7, 9]) possible moves of computer trying to take corners if they are free.
7.if letter == 'X':
  return ['X', 'O']
 else:
  return ['O', 'X']
  parameter is either x or o based on players input
  
8. def isWinner(bo, le):
  return ((bo[7] == le and bo[8] == le and bo[9] == le) or # across the top
 (bo[4] == le and bo[5] == le and bo[6] == le) or # across the middle
 (bo[1] == le and bo[2] == le and bo[3] == le) or # across the bottom
 (bo[7] == le and bo[4] == le and bo[1] == le) or # down the left side
 (bo[8] == le and bo[5] == le and bo[2] == le) or # down the middle
 (bo[9] == le and bo[6] == le and bo[3] == le) or # down the right side
 (bo[7] == le and bo[5] == le and bo[3] == le) or # diagonal
 (bo[9] == le and bo[5] == le and bo[1] == le)) # diagonal
 
9.dont think it will affect the code
10. Contains the last block of code to see if the game will restart at the end of a game, if the player wants to play again and the statement is true, the loop will continue. If the player doesn't wanna continue loop will break. 
