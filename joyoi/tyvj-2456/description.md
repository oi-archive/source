# 

 
 # 题目描述 
<p>
Bessie is leading the cows in an attempt to escape! To do this, the<br>cows are sending secret binary messages to each other.<br><br>Ever the clever counterspy, Farmer John has intercepted the first<br>b_i (1 <= b_i <= 10,000) bits of each of M (1 <= M <= 50,000) of<br>these secret binary messages.<br><br>He has compiled a list of N (1 <= N <= 50,000) partial codewords<br>that he thinks the cows are using. Sadly, he only knows the first<br>c_j (1 <= c_j <= 10,000) bits of codeword j.<br><br>For each codeword j, he wants to know how many of the intercepted<br>messages match that codeword (i.e., for codeword j, how many times<br>does a message and the codeword have the same initial bits).  Your<br>job is to compute this number.<br><br>The total number of bits in the input (i.e., the sum of the b_i and<br>the c_j) will not exceed 500,000.<br><br>给定了N个模板串和M个匹配串，定义一个匹配串和一个模板串相互匹配的条件是它们的<br>最长前缀的长度等于两者中较短者的长度。要求找出每一匹配串与多少个模板串相匹配。</p> 

 
 # 输入格式 
<p>
* Line 1: Two integers: M and N<br><br>* Lines 2..M+1: Line i+1 describes intercepted code i with an integer<br>        b_i followed by b_i space-separated 0's and 1's<br><br>* Lines M+2..M+N+1: Line M+j+1 describes codeword j with an integer<br>        c_j followed by c_j space-separated 0's and 1's<br><br></p> 

 
 # 输出格式 
<p>
* Lines 1..N: Line j: The number of messages that the jth codeword<br>        could match.<br></p> 

 
 # 提示 
<p>
0 matches only 010: 1 match<br>1 matches 1, 100, and 110: 3 matches<br>01 matches only 010: 1 match<br>01001 matches 010: 1 match<br>11 matches 1 and 110: 2 matches<br></p> 
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
<tr><td>4 5
3 0 1 0
1 1
3 1 0 0
3 1 1 0
1 0
1 1
2 0 1
5 0 1 0 0 1
2 1 1

INPUT DETAILS:

Four messages; five codewords.
The intercepted messages start with 010, 1, 100, and 110.
The possible codewords start with 0, 1, 01, 01001, and 11.


</td><td>1
3
1
1
2
</td></tr></table>
