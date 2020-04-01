# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;一次舞会有n个男孩和n个女孩。每首曲子开始时，所有男孩和女孩恰好配成n对跳交谊舞。每个男孩都不会和同一个女孩跳两首（或更多）舞曲。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;有一些男孩女孩相互喜欢，而其他相互不喜欢（不会“单向喜欢”）。每个男孩最多只愿意和k个不喜欢的女孩跳舞，而每个女孩也最多只愿意和k个不喜欢的男孩跳舞。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;给出每对男孩女孩是否相互喜欢的信息，舞会最多能有几首舞曲？ 

 
 # 输入格式 
第一行包含两个整数n和k。以下n行每行包含n个字符，其中第i行第j个字符为'Y'当且仅当男孩i和女孩j相互喜欢。 

 
 # 输出格式 
仅一个数，即舞曲数目的最大值。 

 
 # 提示 
对于30%的数据，n&lt;=5，k&lt;=2；<BR>对于全部的数据，n&lt;=50，k&lt;=30；NOI2009重庆市代表队选拔赛第三题 
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
<tr><td>Input 1:
3 0
YYY
YYY
YYY

Input 2:
3 0
YYY
YYN
YNY

Input 3:
2 0
YN
YN

Input 4:
2 1
YN
YN</td><td>Output 1:
3

Output 2:
2

Output 3:
0

Output 4:
1</td></tr></table>
