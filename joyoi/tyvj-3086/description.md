# 

 
 # 题目描述 
<p>
　　现在要把m本有顺序的书分给k个人复制（抄写），每一个人的抄写速度都一样，一本书不允许给两个（或以上）的人抄写，分给每一个人的书，必须是连续的，比如不能把第一、第三、第四本书给同一个人抄写。<br>　　现在请你设计一种方案，使得复制时间最短。复制时间为抄写页数最多的人用去的时间。<br></p> 

 
 # 输入格式 
<p>
　　第一行两个整数m，k；（k≤m≤500）<br>　　第二行m个整数，第i个整数表示第i本书的页数。<br></p> 

 
 # 输出格式 
<p>
　　共k行，每行两个整数，第i行表示第i个人抄写的书的起始编号和终止编号。k行的起始编号应该从小到大排列，如果有多解，则尽可能让前面的人少抄写。</p> 

 
 # 提示 
<p>
<br><center><img src="/source/joyoi/tyvj-3086/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzA4Ni9wcm9ibGVtc19pbWFnZXMvMTI0Ni8xLmJtcA==.bmp"></img></center></p> 
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
<tr><td>9 3							
1 2 3 4 5 6 7 8 9				
								
</td><td>1 5
6 7
8 9
</td></tr></table>
