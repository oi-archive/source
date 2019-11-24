# 

 
 # 题目描述 
<p>
Alas!  A set of D (1 <= D <= 15) diseases (numbered 1..D) is running through<br>the farm.  Farmer John would like to milk as many of his N (1 <= N <= 1,000)<br>cows as possible.  If the milked cows carry more than K (1 <= K <= D)<br>different diseases among them, then the milk will be too contaminated and<br>will have to be discarded in its entirety.  Please help determine the<br>largest number of cows FJ can milk without having to discard the milk.<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Three space-separated integers: N, D, and K<br><br>* Lines 2..N+1: Line i+1 describes the diseases of cow i with a list<br>        of 1 or more space-separated integers. The first integer, d_i,<br>        is the count of cow i's diseases; the next d_i integers<br>        enumerate the actual diseases. Of course, the list is empty if<br>        d_i is 0.<br><br>有N头牛,它们可能患有D种病,现在从这些牛中选出若干头来,但选出来的牛患病的集合中不过超过K种病.</p> 

 
 # 输出格式 
<p>
* Line 1: M, the maximum number of cows which can be milked.<br></p> 
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
<tr><td>6 3 2
0---------第一头牛患0种病
1 1------第二头牛患一种病,为第一种病.
1 2
1 3
2 2 1
2 2 1
</td><td>5

OUTPUT DETAILS:

If FJ milks cows 1, 2, 3, 5, and 6, then the milk will have only two
diseases (#1 and #2), which is no greater than K (2). 
</td></tr></table>
