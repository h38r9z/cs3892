java cIntroduction
“Snakes and Ladders”is a board game for two or more players taking turns rolling dice,the winner is the player who reaches the final square on the game board at the  earliest.For  more information see:https://en.wikipedia.org/wiki/Snakes        and        ladders.  You have been pro- vided some starter code which allows you to play “Snakes and Ladders”.The assignment is to finish the provided task mentioned next using what you have learned during the course using C Programming Language.

Tasks
In this section the tasks you need to perform for the assignment is listed.

Task 01 - Dice Rolling
1.  Change the code so that a player rolls two dice.
2. If a player rolls double sixes (6 on both dice), then they receive another turn and roll the dice again.
3. If the player is close to the finish (within 6 squares of finishing), then the player will only roll one dice.
Task 02 - Players
1.  Add functionality for at least a third player to join the game. You can add options to have more than three players.
2. If two or more players are in the same box, display on the board that all the players are on the same box.
Task 03 - Playing Grid
1.  The provided starter code already shows the positions of the players on the grid, augment the code to show the positions of the snakes and ladders on the grid also. If a player lands on a snake print "Oh no!  You have landed on a snake and fallen back from square X to square Y".  Similarly, if they land on a ladder then they will receive a message  "Hooray! You have landed on a ladder and climbed from square X up to square Y!".
2.  Make sure that each new game randomly generates new set of snakes and ladders  (new games don’t have the same snakes and ladders).
3.  Ask the user in the game menu to specify the size of the board they wish to use and create such a board (8x8, 10x10, 12x12).  The user will also provide the number of snakes and ladders they wish the board to have.
4.  Avoid snake and ladder conflicts.  Ensure that snakes and ladders do not cover the same squares (i.e. a square cannot have a ladder and a snake.).
(a)  The head of the snake should always take the player to a lower number to the tail of the snake.
(b)  The head and the tail of the snake should not be in the same row.
(c)  The bottom part of a ladder should always take the player to the top part of the ladder.
(d)  The top and the bottom part of a ladder should not be on the same row.
(e)  The box where the top part of a ladder is, should not contain a snake’shead.
(f)  The box where the tail part of the snake is, should not have a bottom part of a ladder. (Hint: Select different rows randomly first, and then select columns randomly.)

Player 1 is now at square 37.

Figure 1:A sample board from the starter code for"Snakes and Ladders"game.

Task 04 -Extra Functionality
1.You need to add an interesting,extra piece of functionality which will make your game unique.Here are some ideas which may be interesting (not necessarily you have to imple ment the below,you can think your own)
(a)Once a game ends,you can save the generated board on a file.
(b)Option to save a game on a file in the middle of a game,and later load it to continue the game.
(c)Keep a count which player wins in how many turns.
(d)Be  creative!<代 写program、C++
代做程序编程语言br>Don't limit yourself with the above ideas only!

Assessment
This section gives the submission requirements and a breakdown of the approximate marking criteria for the assignment.The final marking scheme may vary slightly but will be relatively similar.
Submission Format
The completed project should be submitted as a zip file and must contain the source files (.c or  h)associated  with  the  project.A   starter  code   has been provided with the  file name StartingCode.c,which you can download from csmoodle.
Marking Scheme
The marking scheme shown in Table 国is indicative only.This means that it may be changed at any time without notice.However,it will have approximately the same criteria.Criterion may
Table 1: Marking Scheme Guidelines

Item            Fail                                         Pass                                       Excellent
Design         Not using any functions at all, code is written as one big list of instructions.	Some   use   of   functions, but  large  functions  with unorganised,  or  repeated codes, or have other prob- lems.	Excellent   use   of   func- tions  to  break  the  prob- lem  down  into  manage- able and modular chunks.
Global
Variables	Almost  all  variables  are global.	There   are   only   a   few global   variables   in   the program.	There are no global vari- ables in the program.
Display        Board    does    not    show properly.	Board  shown,  but  there are  some  issues  with  the formatting and alignment.	Board is perfectly drawn, formatted   and   aligned, with the players displayed clearly.
Menu           No menu, or menu work-
ing correctly.	Menu works correctly, but has some problems,  or  if doesn’t coverall options.	Menu is well designed and easy to use for the players.
Task 01       None  of  the  three  sub- tasks  are  complete,  or  if none of them work.	Task 1.1 and Task 1.2 are successfully complete.	All of the tasks are com- plete.
Task 02       None of the two sub-tasks are complete, or if none of them work.	Task   2.1   is   successfully complete   with   at   least three players.	Task 2.1 and 2.2 are com- plete  with  at  least  three players
Task 03       If  none  of  the  sub-tasks are complete or they does not work correctly.	Task 3.1, 3.2, 3.3 are im- plemented.  Some of Task 3.4 works, but have prob- lems.	If  all  the  sub-tasks  are implemented      perfectly. Proper limit checking for inputs.

Task 04	There are no specifications here. try to implement something which is unique and differentiates your game from the others. You will be graded based on if your unique feature works as intended.

be removed and additional criterion may be added.  It can however be used as a guide to the level required for the different parts of the assignment.

Additional Considerations
Along with the criteria mentioned above, the following will also be considered when the grades will be calculated:
•  Names: Variables and functions should be named sensibly (if the purpose of the function or the variable is not understandable from the names, then it has not been named well).
•  Code Formatting: Code should be well formatted and indented correctly.
•  Comments: You code should be lightly (not too much text) but precisely documented.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
