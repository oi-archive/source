# 

 
 # 题目描述 
<p>
　　著名科学家卢斯为了检查学生对进位制的理解，他给出了如下的一张加法表，表中的字母代表数字。 例如：    <br><br><br><center><img src="/source/joyoi/tyvj-3107/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzEwNy9wcm9ibGVtc19pbWFnZXMvMTMwNi8xLmJtcA==.bmp"></img></center><br><br>　　根据这些规则可推导出：L=0，K=1，V=2，E=3<br>　　同时可以确定该表表示的是4进制加法<br><br>程序输入：<br> 　　n（n≤9）表示行数。<br>　　以下n行，每行包括n个字符串，每个字串间用空格隔开。（字串仅有一个为‘+’号，其它都由大写字母组成）<br><br>程序输出：<br>　　① 第一行，各个字母表示什么数，格式如：L=0，K=1，…… （注：实际输出时，用一个空格取代逗号“，”，字母顺序按第一行中，字母出现的先后顺序输出）。<br>　　② 第二行，加法运算是几进制的。<br>　　③ 若不可能组成加法表，则仅输出一行，应输出“ERROR！”<br><br>　　（注：实际输出格式见样例，用一个空格取代逗号“，”，字母顺序按第一行中，字母出现的先后顺序输出）<br></p> 

 
 # 输入格式 
<p>
</p> 

 
 # 输出格式 
<p>
</p> 
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
<tr><td>6
+ M L K N H
M L H M MK N
L H N L MM MK
K M L K N H
N MK MM N MH ML
H N MK H ML MM</td><td>M=1 L=2 K=0 N=4 H=3
5</td></tr></table>
