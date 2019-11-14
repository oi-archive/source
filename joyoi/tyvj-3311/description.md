# 

 
 # 题目描述 
<p>
　　灵兽在紫枫雪地刷新了，dfc迫不及待的跑了过去采集材料。dfc用的是100级才能用的人品采集器，每秒采集量随人品高低而改变，采集器的耐久损耗一开始为0，每采集一秒可以获得人品值di个的材料，并且耐久损耗增加1，当耐久损耗超过m时采集器就会爆掉，这是dfc所不愿见到的，另外每秒dfc可以找武器店老板修理，但每秒只能减少1的耐久损耗，并且dfc一定会等到耐久损耗为0是才会离开。灵兽离消失只有n秒了，dfc如何才能采集到更多的材料？<br><br><center><img src="/source/joyoi/tyvj-3311/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzMxMS9wcm9ibGVtc19pbWFnZXMvMjA0OC8xLmJtcA==.bmp"></img></center>　<br></p> 

 
 # 输入格式 
<p>
　　第一行，两个整数，代表N和M。接下来N行，每行一个整数，代表Di（保证dfc的人品值不会为负数）。<br></p> 

 
 # 输出格式 
<p>
　　一个整数k，代表dfc最多能采集的材料个数。<br></p> 

 
 # 提示 
<p>
　　30%  n <= 100, m <= 20<br>　　50%  n <= 1500, m <= 300<br>　　100%  n <= 10000, m <= 500<br><br></p> 
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
<tr><td>样例输入：
5 2
5
3
4
2
10
</td><td>样例输出：
9
</td></tr></table>
