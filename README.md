# DSA
Assignment 1 - SEM_III - &lt;DSA>
# Problem 1:
In the land of Matricia, the king encodes secret messages in patterns drawn on square 
grids. 
<br/>
He gives you: 
1. A square matrix of size N × N, filled with numbers from 1 to N×N in row-major 
order. <br/>
2. A character ch which can be one of the following: <br/>
○ Z → Draw letter Z <br/>
○ D → Draw letter D <br/>
○ A → Draw letter A <br/>
○ X → Draw letter X <br/><br/>
Your task is to: <br/>
● Construct the pattern using matrix elements (not just 0/1). <br/>
● Replace all non-pattern positions with 0. <br/>
● Print the resulting matrix. <br/>
● Print the sum of all numbers used in the pattern. <br/><br/>
Input Format <br/>
● First line: A character ch (Z, D, A, X). <br/>
● Second line: An integer N (3 ≤ N ≤ 20). <br/><br/>
Output Format <br/>
● The N × N matrix where only the chosen pattern positions keep their values, all 
others are 0. <br/>
● The sum of all values included in the pattern. <br/><br/>
Constraints <br/>
● 3 ≤ N ≤ 20 <br/>
● Pattern is guaranteed to be one of {Z, D, A, X}<br/><br/><br/>
# Problem 2:
In the land of Numberia, there was a great Royal Tournament. <br>
● Each team came to compete. <br>
● Every row in the scoreboard represented one team. <br>
● Each number in the row was the score of a player from that team. <br>
The King of Numberia wanted to reward the best-performing team. <br>
But he was too busy, so he asked you — the Royal Mathematician — to help. <br>
Your job: <br>
● Find the team whose total score is the highest (row with maximum sum). <br>
● Report the team’s index (row number) to the King. <br>
● If two or more teams tie with the same score, the earliest team in the scoreboard should be declared the winner. <br>
Only then will the King crown the winning team with the Golden Abacus Trophy. <br>

Input <br>
● First line contains two integers N (number of teams / rows) and M (number of players per team / columns). <br>
● Next N lines each contain M integers — the scoreboard matrix. <br>

Output <br>
● Print the index (0-based) of the team with the highest total score. <br>

Constraints <br>
● 1 ≤ N, M ≤ 100 <br>
● -10^5 ≤ Score ≤ 10^5 <br>

Input <br>
3 3 <br>
1 2 3 <br>
9 8 7 <br>
4 5 6 <br>

Output <br>
1 <br>
<br><br><br>

# Problem 3: 
In the Palace of Numberia, there is a square chessboard filled with numbers. <br>
● The main diagonal (from top-left to bottom-right) is called the Royal Path of Wisdom. <br>
● The secondary diagonal (from top-right to bottom-left) is called the Royal Path of Power. <br>
● The King wants to know the magical strength of both paths by calculating: <br>

The sum of the main diagonal and the sum of the secondary diagonal. <br>

Input <br>
● First line contains an integer N → size of the chessboard (matrix). <br>
● Next N lines contain N integers → the matrix elements. <br>

Output <br>
● Print two integers: <br>
1. Sum of the main diagonal <br>
2. Sum of the secondary diagonal <br>

Constraints <br>
● 1 ≤ N ≤ 100 <br>
● -10^5 ≤ Matrix[i][j] ≤ 10^5 <br>

Input <br>
3 3 <br>
1 2 3 <br>
4 5 6 <br>
7 8 9 <br>

Output <br>
15 15 <br>
<br><br><br>
# Problem 3: 
<br>
In the Kingdom of Numberia, the Royal Mathematician discovered a strange mirror. <br>
 When the matrix (scoreboard) is placed in front of this mirror: <br>
● Every row of the matrix gets reversed. <br>
● The first element becomes the last, <br>
● The last element becomes the first, <br>
● And so on… <br><br>
The King, being curious, wants you to perform this magical row reversal. <br>
Input <br>
● First line contains two integers N (rows) and M (columns). <br>
● Next N lines contain M integers each → the matrix. <br>
Output <br>
● Print the matrix after reversing each row. <br>
Constraints <br>
● 1 ≤ N, M ≤ 100 <br>
● -10^5 ≤ Matrix[i][j] ≤ 10^5 <br>
Input <br>
3 3 <br>
1 2 3 <br>
4 5 6 <br>
7 8 9 <br>
 
Output <br>
3 2 1 <br>
6 5 4 <br>
9 8 7<br>
