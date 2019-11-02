# 

 
 # 题目描述 
<p>
<br>The farm has many hills upon which Farmer John would like to place<br>guards to ensure the safety of his valuable milk-cows.<br><br>He wonders how many guards he will need if he wishes to put one on<br>top of each hill. He has a map supplied as a matrix of integers;<br>the matrix has N (1 < N <= 700) rows and M (1 < M <= 700) columns.<br>Each member of the matrix is an altitude H_ij (0 <= H_ij <= 10,000).<br>Help him determine the number of hilltops on the map.<br><br>A hilltop is one or more adjacent matrix elements of the same value<br>surrounded exclusively by either the edge of the map or elements<br>with a lower (smaller) altitude. Two different elements are adjacent<br>if the magnitude of difference in their X coordinates is no greater<br>than 1 and the magnitude of differences in their Y coordinates is<br>also no greater than 1.<br><br><br>问有多少个山顶,每个点是八连通的.</p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: N and M<br><br>* Lines 2..N+1: Line i+1 describes row i of the matrix with M<br>        space-separated integers: H_ij<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: A single integer that specifies the number of hilltops<br><br></p> 
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
<tr><td>8 7
4 3 2 2 1 0 1
3 3 3 2 1 0 1
2 2 2 2 1 0 0
2 1 1 1 1 0 0
1 1 0 0 0 1 0
0 0 0 1 1 1 0
0 1 2 2 1 1 0
0 1 1 1 2 1 0

</td><td>3

OUTPUT DETAILS:

There are three peaks: The one with height 4 on the left top, one of
the points with height 2 at the bottom part, and one of the points with
height 1 on the right top corner.</td></tr></table>
