# 

 
 # 题目描述 
<p>
每天早上邮递员都要走过每条街道来递送邮件. 所有的道路都是单向的. 两个岔路口间最多有两条边并且方向不同. 岔路口从1 到 编号.<br>邮递员从Byteotian邮政总部出发并且最终回到总部, 他可以自由选择自己喜欢的线路.最近他的上司给了他新的任务. 他被分派了一些路径的片段- 即一些需要依次经过的岔路口序列. 邮递员要选择一条路径使得: <br>·	经过每条街道一次, <br>·	包含所有给定的路径片段, <br>·	从第一个路口出发并回到第一个路口. <br>很不行,很可能这样的路径不一定存在. 请你帮邮递员找出一条可行的路径. <br></p> 

 
 # 输入格式 
<p>
第一行两个整数 和 , , , 表示岔路口数目以及街道的数目. 接下来行每行两个数字, , , , 表示一条单向道路. 每一队 在数据中最多出现一次. 接下来一行一个整数, , 表示给定的路径片段数目. 接下来行用来描述这些路径片段. 每行开始一个整数 , , 并且一个序列 表示需要经过的路口总数以及这些路口的编号. 所有路径片段的总长不超过.<br></p> 

 
 # 输出格式 
<p>
第一行输出: <br>·	TAK - 如果存在一条满足条件的路径, <br>·	NIE – 如果路径不·	存在. <br></p> 

 
 # 提示 
<p>
<img border="0" src="/source/joyoi/tyvj-2394/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjM5NC9wcm9ibGVtc19pbWFnZXMvMjc5MC8xNTE1LmpwZw==.jpg"><br></p> 
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
<tr><td>6 10
1 5
1 3
4 1
6 4
3 6
3 4
4 3
5 6
6 2
2 1
4
3 1 5 6
3 3 4 3
4 4 3 6 4
3 5 6 2
</td><td>TAK</td></tr></table>
