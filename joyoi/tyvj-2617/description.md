# 

 
 # 题目描述 
<p>
The cows have set up a telephone network, which for the purposes<br>of this problem can be considered to be an unrooted tree of unspecified<br>degree with N (1 <= N <= 100,000) vertices conveniently numbered<br>1..N. Each vertex represents a telephone switchboard, and each edge<br>represents a telephone wire between two switchboards. Edge i is<br>specified by two integers A_i and B_i the are the two vertices<br>joined by edge i (1 <= A_i <= N; 1 <= B_i <= N; A_i != B_i).<br><br>Some switchboards have only one telephone wire connecting them to<br>another switchboard; these are the leaves of the tree, each of which<br>is a telephone booth located in a cow field.<br><br>For two cows to communicate, their conversation passes along the<br>unique shortest path between the two vertices where the cows are<br>located. A switchboard can accomodate only up to K (1 <= K <= 10)<br>simultaneous conversations, and there can be at most one conversation<br>going through a given wire at any one time.<br><br>Given that there is a cow at each leaf of the tree, what is the<br>maximum number of pairs of cows that can simultaneously hold<br>conversations? A cow can, of course, participate in at most one<br>conversation.<br><br>Consider this six-node telephone tree with K=1:<br><br>       1   5          C1   C5<br>       |   |          ||   ||<br>       2---4   -->    |2---4|<br>       |   |          ||   ||<br>       3   6          C3   C6<br><br>There are four cows, located at vertices 1, 3, 5 and 6. If cow 1<br>talks to cow 3, and cow 5 talks to cow 6, then they do not exceed<br>the maximum number of conversations per switchboard, so for this<br>example the answer is 2 (for two pairs of cows talking simultaneously).<br><br><br>一颗无根树，所有的叶子节点上都有一只牛，牛和牛之间联系要在他们在树上的简单路径上铺电话线，每个点最多能容纳通过K根电线，求最多有多少对牛能相互联系。<br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space separated integers: N and K<br><br>* Lines 2..N: Line i+1 contains two space-separated integers: A_i and<br>        B_i<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: The number of pairs of cows that can simultaneously hold<br>        conversations<br></p> 
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
<tr><td>6 1
1 2
2 3
2 4
4 5
4 6

</td><td>2</td></tr></table>
