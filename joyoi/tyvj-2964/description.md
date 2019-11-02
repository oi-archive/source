# 

 
 # 题目描述 
<p>
Advanced Cargo Movement（先进货物搬运）有限公司的卡车有多种类型。有的用于运送蔬菜，有的用于搬运家具或者砖块。公司用专门的编码标识各种类型的卡车。编码很简单，只是七个小写字母组成的字符串（每个位置的字母都有特别的含义，但这对于本问题并不重要）。公司的发展史上，基于最初只有一种类型的卡车发展出多种类型的卡车，而这些卡车类型又能演变出新的卡车类型。<br>现在，ACM公司资金雄厚，高层雇佣了历史学家来研究公司历史。历史学家的任务之一是找出公司的发展图谱，也就是各种卡车类型是从何演变而来的。他们将不同类型卡车之间的距离定义为其编码中同一位置不同字母的个数。假定所有卡车都只从一种类型的卡车演变而来（除了最初类型的卡车之外）。发展图谱的质量被定义为 <br><center><br><img src="/source/joyoi/tyvj-2964/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjk2NC9wcm9ibGVtc19pbWFnZXMvMzU0Ni8xMS5qcGc=.jpg"></img></center><br>公式的求和部分是任意类型的卡车对之间的距离之和，其中to是原来类型的卡车，td是根据to发展得到的卡车，d(to,td) 是它们之间的距离。<br>历史学家失败了，所以你得写一个程序帮帮他们。给你所有卡车类型的编码，你要求出发展图谱的最高质量。 <br></p> 

 
 # 输入格式 
<p>
输入包含多组数据，每组数据以一个表示卡车类型数目的整数N开头，2 <= N <= 2 000。接下来N行表示各种类型的卡车编码（一个七字母字符串）。假定所有编码都不重复。输入卡车类型数目为0时程序结束。 </p> 

 
 # 输出格式 
<p>
对于每组数据，你的程序必须输出“The highest possible quality is 1/Q”，其中 1/Q 是发展图谱的最高质量。 </p> 

 
 # 提示 
<p>
在莞中OJ提交通过后，请点击下面链接到POJ再提交一次：<br><a href="http://poj.org/problem?id=1789">http://poj.org/problem?id=1789</a></p> 
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
<tr><td>4
aaaaaaa
baaaaaa
abaaaaa
aabaaaa
0
</td><td>The highest possible quality is 1/3.</td></tr></table>
