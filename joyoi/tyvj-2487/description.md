# 

 
 # 题目描述 
<p>
Farmer John is on a boat seeking fabled treasure on one of the N<br>(1 <= N <= 100) islands conveniently labeled 1..N in the Cowribbean<br>Sea.<br><br>The treasure map tells him that he must travel through a certain<br>sequence A_1, A_2, ..., A_M of M (2 <= M <= 10,000) islands, starting<br>on island 1 and ending on island N before the treasure will appear<br>to him. He can visit these and other islands out of order and even<br>more than once, but his trip must include the A_i sequence in the<br>order specified by the map.<br><br>FJ wants to avoid pirates and knows the pirate-danger rating (0 <=<br>danger <= 100,000) between each pair of islands. The total danger<br>rating of his mission is the sum of the danger ratings of all the<br>paths he traverses.<br><br>Help Farmer John find the least dangerous route to the treasure<br>that satisfies the treasure map's requirement.<br><br>给出一个要访问的点的序列，但在实际走的时候，你可以经过某些中转点来进行访问. <br>再给出任两点之间的危险值，求你在走的过程中危值值的总和是多少. <br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: N and M<br><br>* Lines 2..M+1: Line i+1 describes the i_th island FJ must visit with<br>        a single integer: A_i<br><br>* Lines M+2..N+M+1: Line i+M+1 contains N space-separated integers<br>        that are the respective danger rating of the path between<br>        island i and islands 1, 2, ..., and N, respectively. The ith<br>        integer is always zero.<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: The minimum danger that Farmer John can encounter while<br>        obtaining the treasure.<br><br></p> 
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
<tr><td>3 4
1
2
1
3
0 5 1
5 0 2
1 2 0

INPUT DETAILS:

There are 3 islands and the treasure map requires Farmer John to
visit a sequence of 4 islands in order: island 1, island 2, island
1 again, and finally island 3. The danger ratings of the paths are
given: the paths (1, 2); (2, 3); (3, 1) and the reverse paths have
danger ratings of 5, 2, and 1, respectively.


</td><td>7

OUTPUT DETAILS:

He can get the treasure with a total danger of 7 by traveling in
the sequence of islands 1, 3, 2, 3, 1, and 3. The cow map's requirement
(1, 2, 1, and 3) is satisfied by this route. We avoid the path
between islands 1 and 2 because it has a large danger rating.</td></tr></table>
