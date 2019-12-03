# 

 
 # 题目描述 
JR有很多双筷子。确切的说应该是很多根，因为筷子的长度不一，很难判断出哪两根是一双的。JR家里来了K个客人，JR留下他们吃晚饭。加上JR，JR的girl&nbsp;friend和JR的朋友内涵，共K+3个人。每人需要用一双筷子。JR只好清理了一下筷子，共N根，长度为T1,T2,T3,……,TN.现在他想用这些筷子组合成K+3双，使每双的筷子长度差的平方和最小。 

 
 # 输入格式 
输入文件共有两行，第一行为两个用空格隔开的整数，表示N,K(1≤N≤100,&nbsp;0&lt;K&lt;50)，第二行共有N个用空格隔开的整数，为Ti.每个整数为1～50之间的数。 

 
 # 输出格式 
输出文件仅一行。如果凑不齐K+3双，输出-1，否则输出长度差平方和的最小值。 

 
 # 提示 
第一双&nbsp;1&nbsp;1<BR>第二双&nbsp;2&nbsp;3<BR>第三双&nbsp;3&nbsp;3<BR>第四双&nbsp;4&nbsp;6<BR>(1-1)^2+(2-3)^2+(3-3)^2+(4-6)^2=5<BR> 
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
<tr><td>10 1
1 1 2 3 3 3 4 6 10 20</td><td>5</td></tr></table>
