# 

 
 # 题目描述 
<p>
The cows have run out of hay, a horrible event that must be remedied<br>immediately. Bessie intends to visit the other farms to survey their<br>hay situation. There are N (2 <= N <= 2,000) farms (numbered 1..N);<br>Bessie starts at Farm 1.  She'll traverse some or all of the M (1<br><= M <= 10,000) two-way roads whose length does not exceed 1,000,000,000<br>that connect the farms. Some farms may be multiply connected with<br>different length roads. All farms are connected one way or another<br>to Farm 1.<br><br>Bessie is trying to decide how large a waterskin she will need.  She knows<br>that she needs one ounce of water for each unit of length of a road. Since<br>she can get more water at each farm, she's only concerned about the length<br>of the longest road. Of course, she plans her route between farms such that<br>she minimizes the amount of water she must carry.<br><br>Help Bessie know the largest amount of water she will ever have to<br>carry: what is the length of longest road she'll have to travel<br>between any two farms, presuming she chooses routes that minimize<br>that number? This means, of course, that she might backtrack over<br>a road in order to minimize the length of the longest road she'll have<br>to traverse.<br><br><br>给出一个图,求最小生成树,要求最长边最短.<br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers, N and M.<br><br>* Lines 2..1+M: Line i+1 contains three space-separated integers, A_i,<br>        B_i, and L_i, describing a road from A_i to B_i of length L_i.<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: A single integer that is the length of the longest road<br>        required to be traversed.<br><br></p> 
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
<tr><td>3 3
1 2 23
2 3 1000
1 3 43
</td><td>43

OUTPUT DETAILS:

In order to reach farm 2, Bessie travels along a road of length 23.
To reach farm 3, Bessie travels along a road of length 43.  With
capacity 43, she can travel along these roads provided that she
refills her tank to maximum capacity before she starts down a road.</td></tr></table>
