CS 400: Accelerated Fundamentals of Computing I
Assignment #1

Due date: Thursday, September 11th by 11:59 PM Central Time
Please Read Before You Begin
Save a copy of this notebook to your Google Drive so that your work will be saved. To do this, use the following command.
File -> Make a copy
 1 How Well Do You Follow Instructions
If you carefully follow all the directions below, you will change the words WHEN MUSIC COPYISTS MEET into a related, tongue-in-cheek phrase. Be sure to work carefully, step by step.


INSTRUCTIONS
YOUR SOLUTION
Print the words WHEN MUSIC COPYISTS MEET, without a space between the words.
WHENMUSICCOPYISTSMEET


Reverse the positions of the fourth consonant from the left and the fourth consonant from the right.
the fourth consonant from the left: M
the fourth consonant from the right: T
WHENMUSICCOPYISTSMEET
Result: WHENTUSICCOPYISMSMEET
Delete every I.
WHENTUSICCOPYISMSMEET
Result: WHENTUSCCOPYSMSMEET
Double the O.
Result: WHENTUSCCOOPYSMSMEET
Reverse the positions of the fourth letter from the left N and the fourth letter from the right M.
Result: WHEMTUSCCOOPYSMSNEET
Delete the sixth consonant C from the left.
Result: WHEMTUSCOOPYSMSNEET
Reverse the positions of the first consonant from the right T and the first vowel from the right E.
Result: WHEMTUSCOOPYSMSNETE
Move the fifth letter from the left T to the immediate left of the W.
Result: TWHEMUSCOOPYSMSNETE
Remove the first S from the left and change the first S from the right to an R.
Result: TWHEMUCOOPYSMRNETE
Reverse the positions of the P and the first M from the right.
TWHEMUCOOPYSMRNETE
result: TWHEMUCOOMYSPRNETE
Reverse the positions of the first M from the left and the Y.
TWHEMUCOOMYSPRNETE
Result: TWHEYUCOOMMSPRNETE
Reverse the positions of the N and the second E from the left.
TWHEYUCOOMMSPRNETE
Result: TWHEYUCOOMMSPRENTE
Delete the U.
Result: TWHEYCOOMMSPRENTE
Move the second vowel from the left to the immediate right of the N.
TWHEYCOOMMSPRENTE
Result: TWHEYCOMMSPRENOTE


Delete one M.
Result: TWHEYCOMSPRENOTE
Insert an A to the immediate left of the R. Delete the W.
Result: THEYCOMSPARENOTE
Move the S to the immediate right of the first E from the right.
THEYCOMSPARENOTE
Result: THEYCOMPARENOTES

Final Result: THEYCOMPARENOTES




Problem #2 is on the next page.

2 Sudoku Puzzle
Sudoku involves a 9 x 9 grid of 81 squares. Some of the grid squares already contain numbers. You cannot change the provided numbers.
Sudoku is a puzzle based on a small number of simple rules:
Every square has to contain a single number.
Only the numbers from 1 through 9 can be used.
Each 3x3 box can only contain each number from 1 to 9 once.
Each vertical column can only contain each number from 1 to 9 once.
Each horizontal row can only contain each number from 1 to 9 once.
Once the puzzle is solved, every row, column, and 3x3 box will contain every number from 1 to 9 exactly once. In other words, no number can be repeated in any 3x3 box, row, or column.
图略

Consider the following Sudoku puzzle to answer the questions in this section.

2.1 Step-by-step solution
Your solution must include step-by-step instructions on how you solved the puzzle. The puzzle can be solved by logical reasoning. There is no need to guess. 
For each step of your solution, you must include (a) the instruction (or step) number, (b) the cell that has been filled, (c) the number placed into the filled cell, and (d) a clear, concise, and logical justification for this step.



Step 1 has been completed for you. 

Step 
Filled Cell 
Number in Filled Cell 
Justification 
1
IE
9
The only options remaining in column E are 7 and 9. Since 7 appears in row I, cell IE must be 9.
2
AE
7
The only option remaining in column E is 7. 
3
GD
8
In the orange square at the bottom, only 2, 3 and 8 are missing. 3 can’t be in row H or row I because they already have 3 in them. So GD can only be in 3.
4
BB
9
In column B, 2, 7, and 9 are missing. So BB, CB and CE can be 2 or 7 or 9.
CB can’t be 9, because row C already has 9. So CB can only be 2 or 7.
Similarly, EB can’t be 9 because there is already a 9 in the orange square on the right side.
Therefore, CB and EB will take 2 and 7. BB can only be 9.


5
BD
1
In the orange square on the top, 1, 3 and 9 are missing. BD can’t be 3 because there is already a 3 in the column.
BD can’t be 9 either because there is a 9 in row B.
So BD can only be 1.
6
CF
3
Now, in the orange square on the top, 3 and 9 are missing. CF can’t be 9 because there is a 9 in row C. So CF can only be 3
7
AD
9
Now, in the orange square on the top, only 9 is missing.
8
CB
7
According to step 4’s explanation, CB can be either 2 or 7. But the top left blue square already has 2, so CB can only be 7.
9
EB
2
Now, column B’s only missing number is 2. So EB can only be 2.
10
FD
2
In the blue square in the middle, 2, 4, and 6 are missing, so DD, ED and FD should be 2 or 4 or 6. But DD and ED can’t be 2 since their rows already have 2. So FD is 2.
11
DD
6
Following the last step, ED and DD can be 4 or 6. DD can’t be 4 since there is a 4 in the same row. So DD is 6.
12
ED
4
Now column only has 4 missing, so ED is 4.
13
EA
6
In the orange square on the left, 5, 6, and 7 are missing. 6 can’t be in row F because row F already has a 6. So the only blank left is EA.
14
FF
9
In the blue square in the middle, 1, 7, and 9 are missing. FF can’t be 1 because there is a 1 in row F. FF can’t be 7 either because FA and FC will take 5 and 7. So FF can only be 9.
15
EI
9
In row E, 1, 7, and 9 are missing, so EF, EH and EI are 1, 7 or 9. EF and EH can’t be 9 because there is already 9 in their columns. So only EI can be 9.
16
EF
1
Now the blue square in the middle only has 1 and 7 missing. Let’s assume that EF is 1 and DF is 7. If it doens’t work, we come back to change the assumption.
17
DF
7
ibid.
18
EH
7
Now only 7 is missing in row E, so EH must be 7.
19
HF
2
Now the orange square at the bottom only has 2 and 8 missing. Let’s assume that HF is 2 and IF is 8. If it doens’t work, we come back to change the assumption.
20
If
8
ibid.
21
GH
8
Now in column H there is only 1 and 8 missing. GH can’t be 1 because there is already a 1 in the same row. So GH is 8.
22
HH
1
Now only 1 is missing in column H, so HH must be 1.
23
FB
5
In the orange square on the left side, only 5 and 7 are missing. FB can be 5 or 7. However, of of FC (5 or7) and GC (4 or 7) MUST be 7, so FB can only be 5. 
24
FC
7
Now only 7 is missing in row F.
25
GC
4
As explained above, GC can be 4 or 7. But since FC (in the same column) already take 7, GC can only be 4.
26
CC
5
Now in column C, 1, 5 and 8 are missing. CC can be 1 or 5 – it can’t be 8 since there’s an 8 in the same row. The remaining blanks in column C, HC and IC, can only be 1 or 8 – they can’t be 5 since in there is already a 5 in the orange square in the bottom left. So HC and IC will take 1 and 8 (though we don’t know how they pair), and CC is certainly 5.
27
HC
8
As explained in the last step, HC can be 1 or 8. But since there is a 1 in the same row, HC must be 8.
28
IC
1
Now the only number missing in this column is 1. So IC must be 1.
29
HA
7
In the bottom left orange square, 2, 7 and 9 are missing. in row H, 6 and 7 are missing. The intersection of these 2 sets of possibilities is 7, so HA is 7.
30
IA
2
In row I, there are only 2 and 5 missing. But in the bottom left square , there is already a 5. So IA can only be 2.
31
II
5
Now the only number missing in row I is 5, so II must be 5.
32
GA
9
Now the only number missing in the bottom left square is 9, so GA must be 9.
33
HI
6
Now the only number missing in row H is 6, so HI must be 6.
34
BA
3
Column A has 1, 3, and 4 missing; Row B has 3, 7 and 8 missing. The only overlap is 3.
35
AA
1
Now column A only has 1 and 4 missing. But row A already has 4, so AA can’t be 4.
36
CA
4
Now the only number missing in column A is 4.
37
AI
3
Row A has 3 and 6 missing, but AI can’t be 6 since there is a 6 in the same column.
38
AG
6
Now only 6 is missing in row A.
39
BG
7
Row B has 7 and 8 missing, and therei is already an 8 in column G, so BG is 7.
40
BI
8
Now row B only has 8 missing.
41
GG
2
Row G has 2 and 7 missing, but column G already has 7, so GG must be 2.
42
GI
7
Now row G only has 7 missing.
43
CG
1
Row C has 1 and 2 missing, and there is already a 2 in column G, so CG must be 1.


44
CI
2
Now only 2 is missing in column C


45
DG
5
Now only 5 is missing in column G


46
DI
1
Now only 1 is missing in column I





2.2 Final solution

Please show your final solution based on your step-by-step solution above.

图略


Problem #3 is on the next page.


3 Other starting cells

In Section 2.1, you provided step-by-step instructions on how to solve the Sudoku puzzle. Your solution started with cell Ie. Please list all other cells (if any) you could use for step 1 of your step-by-step solution. Your answer should be based on logic and not guessing. Justify your answer.

Solution. 

[Add your solution here. Be clear and thorough.]

BB must be 9.
Reason: Column B has 2, 7 and 9 missing, so BB, CB and EB will take these numbers – but we don’t know which blank matches which number. CB can’t be 9 because there is already a 9 in the same row. EB can’t be 9 either because there is a 9 in the orange square on the left side. As a result, BB must be 9.

4 Submitting Assignment #1
Note: You may submit your work multiple times. Only your final submission will be graded.
Below are the steps for submitting Assignment #1.
Go to File -> Download -> PDF (.pdf)
Go to Canvas and click on the Assignment #1 link.
Click the “Start Assignment” button.
Upload your Assignment #1 file (from Step 1) to Canvas.
Click the “Submit Assignment” button.


