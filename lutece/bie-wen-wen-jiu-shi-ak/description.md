
# Content

初心洁：韬哥哥，韬哥哥，这牌起手九九怎么打哇

魂天欧：别问，问就是国士无双

初心洁：韬哥哥，韬哥哥，这道数学题怎么做哇

魂天欧：别问，问就是容斥+状压DP+NTT+矩阵快速幂

初心洁：(哇的一声哭了出来

由于魂天欧不屑于做初心洁的简单题，于是只有请你帮帮不会数学的初心洁了。

$f(i)=\sum_{x=1}^{p-1}\sum_{y=1}^{m}[(x+y)^i\equiv x^i \pmod p]$

$[(x+y)^i\equiv x^i \pmod p]=\begin{cases} 1,&(x+y)^i\equiv x^i \pmod p\\ 0,&(x+y)^i \not\equiv x^i \pmod p\end{cases}$

求$\sum_{i=1}^{p-1}if(i)$

# Standard Input

第一行一个整数T表示数据组数

接下来T行每行两个整数m和p

# Standard Output

T行每行一个整数表示答案对$10^9+7$取模后的结果

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>3
5 7
3 11
2 103</td><td>210
390
50388</td></tr></table>


# Constraints

$T \le 100,1 \le m \le p-1,p$为质数且$2 \le p \le 10^9+7$

# Note



# Source


