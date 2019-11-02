# 

 
 # 题目描述 
<p>
Farmer John knows that an intellectually satisfied cow is a happy<br>cow who will give more milk. He has arranged a brainy activity for<br>cows in which they manipulate an M x N grid (1 <= M <= 15; 1 <= N<br><= 15) of square tiles, each of which is colored black on one side<br>and white on the other side.<br><br>As one would guess, when a single white tile is flipped, it changes<br>to black; when a single black tile is flipped, it changes to white.<br>The cows are rewarded when they flip the tiles so that each tile<br>has the white side face up. However, the cows have rather large<br>hooves and when they try to flip a certain tile, they also flip all<br>the adjacent tiles (tiles that share a full edge with the flipped<br>tile). Since the flips are tiring, the cows want to minimize the<br>number of flips they have to make.<br><br>Help the cows determine the minimum number of flips required, and<br>the locations to flip to achieve that minimum. If there are multiple<br>ways to achieve the task with the minimum amount of flips, return<br>the one with the least lexicographical ordering in the output when<br>considered as a string.  If the task is impossible, print one line<br>with the word "IMPOSSIBLE".<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: M and N<br><br>* Lines 2..M+1: Line i+1 describes the colors (left to right) of row i<br>        of the grid with N space-separated integers which are 1 for<br>        black and 0 for white<br><br></p> 

 
 # 输出格式 
<p>
* Lines 1..M: Each line contains N space-separated integers, each<br>        specifying how many times to flip that particular location.<br><br></p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>4 4
1 0 0 1
0 1 1 0
0 1 1 0
1 0 0 1


</td><td>
0 0 0 0
1 0 0 1
1 0 0 1
0 0 0 0

OUTPUT DETAILS:

After flipping at row 2 column 1, the board will look like:
0 0 0 1
1 0 1 0
1 1 1 0
1 0 0 1

After flipping at row 2 column 4, the board will look like:
0 0 0 0
1 0 0 1
1 1 1 1
1 0 0 1

After flipping at row 3 column 1, the board will look like:
0 0 0 0
0 0 0 1
0 0 1 1
0 0 0 1

After flipping at row 3 column 4, the board will look like:
0 0 0 0
0 0 0 0
0 0 0 0
0 0 0 0

Another solution might be:
0 1 1 0
0 0 0 0
0 0 0 0
0 1 1 0
but this solution is lexicographically higher than the solution above.</td></tr></table>
