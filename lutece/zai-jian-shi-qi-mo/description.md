
# Content

当年的beap也是个风骚少年。想当年，他写过作文，阅过英语，精通物理，称霸生物，做过实验，更算过排列组合。

但如今，= =、 额，往事不堪回首。

又是一年期末，看着数学考卷上的题目，beap悲痛欲绝，泪如雨下，经过激烈的思想斗争，他果断掏出手机向你求助。

聪明又善良的你，一定能帮他走出困境。

给定正整数$n,m\_1,m\_2$，且满足$n \leq m\_1,m\_2$。

设$res=\sum[C(m\_1,k)\times C(m\_2,n-k)]$ 其中$k=0\sim n$

现在，需要你计算$res\ mod\ 1000000007$的值。

其中$C(m\_1,k)$表示组合数，例如$C(4,2)=6$, $C(5,2)=10$。

# Standard Input

多组测试数据。

对于每组测试数据，有三个正整数$n,m\_1,m\_2$ ($0 < n \leq m\_1,m\_2 \leq 10000$)。

# Standard Output

对于每组测试数据，输出$res\ mod\ 1000000007$的值。

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
<tr><td>1 1 1
2 3 4
3 3 4</td><td>2
21
35</td></tr></table>


# Constraints



# Note

样例二:

$res=C(3,0)\times C(4,2)+C(3,1)\times C(4,1)+ C(3,2)\times C(4,0)$

$=1\times 6+3\times 4+3\times 1$

$=21$

# Source


