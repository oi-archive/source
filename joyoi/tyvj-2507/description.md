# 

 
 # 题目描述 
<p>
The cows are having a picnic! Each of Farmer John's K (1 <= K <=<br>100) cows is grazing in one of N (1 <= N <= 1,000) pastures,<br>conveniently numbered 1...N. The pastures are connected by M (1 <=<br>M <= 10,000) one-way paths (no path connects a pasture to itself).<br><br>The cows want to gather in the same pasture for their picnic, but<br>(because of the one-way paths) some cows may only be able to get<br>to some pastures. Help the cows out by figuring out how many pastures<br>are reachable by all cows, and hence are possible picnic locations.<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Three space-separated integers, respectively: K, N, and M<br><br>* Lines 2..K+1: Line i+1 contains a single integer (1..N) which is the<br>        number of the pasture in which cow i is grazing.<br><br>* Lines K+2..M+K+1: Each line contains two space-separated integers,<br>        respectively A and B (both 1..N and A != B), representing a<br>        one-way path from pasture A to pasture B.<br><br>有一个n个点，m条边的有向图，还有k只奶牛。每个奶牛在一个点上，现在FJ想知道，有多少个点是这k个奶牛都可以到达的。</p> 

 
 # 输出格式 
<p>
* Line 1: The single integer that is the number of pastures that are<br>        reachable by all cows via the one-way paths.<br><br></p> 
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
<tr><td>2 4 4
2
3
1 2
1 4
2 3
3 4


INPUT DETAILS:

4<--3
^   ^
|   |
|   |
1-->2

The pastures are laid out as shown above, with cows in pastures 2 and 3.
</td><td>2

OUTPUT DETAILS:

The cows can meet in pastures 3 or 4.</td></tr></table>
