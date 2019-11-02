# 

 
 # 题目描述 
<p>天文学家经常观察星象图。星象图中用平面上的点来表示一颗星星，每一颗星星都有一个笛卡尔坐标。设定星星的等级为其左下角星星的总数。天文学家们想知道星星等级的分布情况。<br />
&nbsp;</p>

<center><img alt="" src="data:image/png;base64,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" style="width: 289px; height: 148px;" /></center>

<p>比如上图，5号星星的等级为3（其左下角有编号为1、2、4的星星共三颗）。2号星星和4号星星的等级为1。在上图中只有一颗星星等级为0，两颗星星等级为1，一颗星星等级为2，一颗星星等级为3。<br />
给定一个星象图，请你写一个程序计算各个等级的星星数目。</p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<p>&nbsp;</p> 

 
 # 输入格式 
<p>输入的第一行包含星星的总数N&nbsp;(1&lt;=N&lt;=15000)。接下来N行，描述星星的坐标（X,Y）（X和Y用空格分开，0&lt;=X,Y&lt;=32000）。星象图中的每个点处最多只有一颗星星。所有星星按Y坐标升序排列。Y坐标相等的星星按X坐标升序排列。</p> 

 
 # 输出格式 
<p>输出包含N行，每行一个整数。第一行包含等级0的星星数目，第二行包含等级1的星星数目，依此类推，最后一行包含等级为N-1的星星数目。</p> 

 
 # 提示 
<p>①&nbsp;对于C/C++的程序员，这个问题的规模比较大，读数据的时候为了避免超时，推荐使用scanf()&nbsp;取代cin。<br />
②&nbsp;请将你的程序在&nbsp;<a href="http://poj.org/problem?id=2352">http://poj.org/problem?id=2352</a>&nbsp;上提交测试是否能通过！</p> 
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
<tr><td>5
1 1
5 1
7 1
3 3
5 5
</td><td>1
2
1
1
0</td></tr></table>
