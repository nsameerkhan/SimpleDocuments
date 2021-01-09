## TIC-TAC-TOE GAME PROGRAM FLOW  
1.DISPLAY A WELCOME MESSAGE  
2.RANDOM PLAYERS SELECTION  
3.PRINT TIC-TAC-TOE GAME BOARD  
4.FILL THE INPUT IN THE BOARD  
5.CHECK FOR REPETITION PROCESS  
6.CHECK FOR STATES  
7.DISPLAY A RESULTS  
### 1. Display a welcome message

 * Write welcome message to the players  
 **WELCOME TO THE GAME![TIC-TAC-TOE]**    
 ### 2.Random players selection  
 * The tic-tac-toe is a two players game.   
 * I designed to player1->X and player2->O. 
 * choose randomly to select a players first,to play a game.  
 ### 3.Print tic-tac-toe game board  
 * I use one-dimensional array or two-dimensional array to print the board.  
 #### one-dimensional array board   

BEST | OF | LUCK
---------|----------|---------
 0 | 1 | 2
 3 | 4 | 5
 6 | 7 | 8  
 ### Uses of one-dimensional array  
 * It used to identifies a state easily(winning state,draw state,ending state)   
 * The comparison logic also well to perform.  
 ### two-dimensional array board  

BEST | OF | LUCK
---------|----------|---------
 (0,0) | (0,1) | (0,2)
 (1,0) | (1,1) | (1,2)
 (2,0) | (2,1) | (2,2)  
 ### Uses of two-dimensional array  
 * It is especially convenient for programming sketches that involve some sort of "grid" or"board".  
  * It is used to perform matrix structures.  
  ### 4.Fill inputs in the board  
  * Randomly choose player X start first, then the board contains 0-8 numbers to marker anyone numbers(one-dimensional array)  
  * The player O play alternatively to marker anyone's numbers,until filling  the board.  
  ### 5.Check for repetition  
  * The players are played alternatively, but no repeated numbers  give the game.  
  * Check conditions to filling the board numbers simultaneously.  
  * players give repeated values,get new input repeatedly.  
  ### 6.Check for states.  
  * The states are:  
  i.Winning state  
  ii.Draw state  
  iii.Ending state  
   ### i.Winning state  
  * The state is written the program for winning possibility condition.  
  * The players are played alternatively, to check a winning  condition alternatively.  
  ### ii.Draw state  
  * The state is written the program for draw possibility condition.  
  * The players are played alternatively, to check a draw condition alternatively.  
  ### iii.Ending state  
  * The state is written the program (0-8) numbers filled aboard then game over.  
  * The players are played alternatively,to check an ending condition alternatively.  
  ### 7.Display result  
  * Display the message for players winning message or draw message.  
  #### winning message  
  ### Player X win:
  ***CONGURATULATIONS! PLAYER X WON THE GAME*** 
  ### Player O win:
  ***CONGURATULATIONS! PLAYER O WON THE GAME***  
  ### MATCH DRAW:
  ***BETTER PLAY! MATCH DRAW***   
  FOR EXAMPLE:    
  (one-dimensional array)   
  **WELCOME TO THE GAME![TIC-TAC-TOE]**   
  **player1->X and player2->O**  
  **Randomly choose player X start first**    
    
BEST  | OF | LUCK
---------|----------|---------
 0 | 1 | 2
 3 | 4 | 5
 6 | 7 | 8  
   
    
     
* The board contains 0-8 numbers to marker anyone's numbers.  
Enter the number player X:8  
  NOTE:  
  * Check for repetition process  
  * check for states

BEST | OF | LUCK
---------|----------|---------
 0 | 1 | 2
 3 | 4 | 5
 6 | 7 | X      
   
* The board contains 0-8 numbers to marker anyone's numbers.  
Enter the number player O:4  
  NOTE:  
  * Check for repetition process  
  * check for states

BEST  | OF | LUCK
---------|----------|---------
 0 | 1 | 2
 3 | O | 5
 6 | 7 | X    
   
* The board contains 0-8 numbers to marker anyone's numbers.  
Enter the number player X:0  
  NOTE:  
  * Check for repetition process  
  * check for states
   

BEST  |OF |LUCK
---------|----------|---------
 X | 1 | 2
 3 | O | 5
 6 | 7 | X   

 * The board contains 0-8 numbers to marker anyone's numbers.  
Enter the number player O:2  
  NOTE:  
  * Check for repetition process  
  * check for states 
   

BEST  | OF | LUCK
---------|----------|---------
 X | 1 | O
 3 | O | 5
 6 | 7 | X    
   
* The board contains 0-8 numbers to marker anyone's numbers.  
Enter the number player X:6   
  NOTE:  
  * Check for repetition process  
  * check for states
   

BEST  | OF | LUCK
---------|----------|---------
 X | 1 | O
 3 | O | 5
 X | 7 | X   
   
* The board contains 0-8 numbers to marker anyone's numbers.  
Enter the number player O:7  
  NOTE:  
  * Check for repetition process  
  * check for states
   

BEST  | OF |LUCK
---------|----------|---------
 X | 1 | O
 3 | O | 5
 X | O | X    
   
* The board contains 0-8 numbers to marker anyone's numbers.  
Enter the number player X:3  
  NOTE:  
  * Check for repetition process  
  * check for states
   
BEST  | OF |LUCK
---------|----------|---------
 ~~X~~ | 1 | O
 ~~X~~ | O | 5
  ~~X~~| O | X   

***CONGURATULATIONS! PLAYER X WON THE GAME***  
    