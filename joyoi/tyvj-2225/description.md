# 

 
 # 题目描述 
<p>
恢复<br>　　小修是个几何迷。她有一天画了一个正n边形，并且将n个顶点用1,2,…,n这n个连续自然数随手编了一下号。然后她又画了一些不相交的对角线。如下图：<br><br><center><img src="/source/joyoi/tyvj-2225/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjIyNS9wcm9ibGVtc19pbWFnZXMvMTA5My8xLmJtcA==.bmp"></img></center>　<br>　　她把所有的边和对角线都写在一张纸上。对上图，她写了：(1,3), (3,2), (2,4), (4,5), (5,1), (1,4), (3,4)。<br>过了几个星期，她无意中发现了这张写着字的纸，可是怎么也找不着那个几何图形了。她很想把n边形的编号复原，可是试了一天也没弄出来。你能帮助她吗？<br><br></p> 

 
 # 输入格式 
<p>
　　第一行n( n <= 50 )。<br>　　下面的若干行每行两个数a, b。表示纸上写着(a,b)。<br><br></p> 

 
 # 输出格式 
<p>
　　仅一行，按顺序依次输出顶点的编号。对于上面的例子，你的输出应该是1　3　 2　4　5。<br>　　1　5　4　2　3也是符合题目要求的。两者区别只是逆时针和顺时针而已。<br>　　但是你的输出只能是1　3　2　4　5！也就是说你必须把两个符合要求的输出比较大小（先比较第一位；第一位相等就比较第二位；第二位相等……以此类推），你的输出应该是较小者！（这是为了评测的方便）<br><br></p> 
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
<tr><td>Resume.in
5
1 3
3 2
2 4
4 5
5 1
1 4
3 4

</td><td>Resume.out
1 3 2 4 5
</td></tr></table>
