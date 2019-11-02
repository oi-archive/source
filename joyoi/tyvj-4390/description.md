# 

 
 # 题目背景 
<p>kblack和subconscious是好朋友。</p>

<p>植树节就要到了，subconscious和kblack打算一起种树。</p> 

 
 # 题目描述 
<p>为了方便起见，我们用二维坐标来表示每棵树的位置，并定义两点间距离为曼哈顿距离，（两点(x1,y1)和(x2,y2)的曼哈顿距离为|x1-x2|+|y1-y2|）。</p>

<p>种树就必然要浇水，为了方便起见，subconscious决定铺设一系列管道来运送水。同时，他必须选择一个点安置水泵（可以放在有树的点），那么管道的铺设量就等于每棵树到达水泵的距离之和。需要注意的是，水泵到每棵树的管道是独立的，也就是说，如果一个节点上有多棵树，从水泵到该点的距离需要被计算多次。subconscious想知道，把水泵设置在哪里，才能使每个点到水泵的距离和最小。</p>

<p>subconscious仍在制定计划，所以他可以添加、删除树木，并进行多次询问。对于每个询问，你只需要输出最小距离和即可。</p>

<p>Subconscious要拯救世界（雾），就把这个问题丢给了kblack。kblack当然能秒杀这个问题啦，但由于他还要忙着把妹（大雾），就把这个问题丢给了你，请你解决这个问题。作为报酬，他能让你在tyvj的3月月赛中多得100分。</p>

<p>本题中坐标均为整数。</p> 

 
 # 输入格式 
<p align="left">输入文件第一行为一个非负整数n，表示初始有n棵树。</p>

<p align="left">第2行到第n+1行描述初始的树，每行有2个非负整数x，y，表示该树的坐标为(x,y)。</p>

<p align="left">接下来一行为一个数T，表示接下来将发生T个事件。</p>

<p align="left">接下来的T行，每行有3个非负整数op，x，y。op表示该事件的类型，op=0表示询问，此时x，y均为0；如果op=1，表示在坐标(x,y)上添加一棵树；如果op=2，表示在坐标(x,y)上删除一棵树，输入数据保证该坐标上至少有一棵树，需要注意的是，如果该坐标上有多棵树，那么仅删除一棵树。</p> 

 
 # 输出格式 
<p>对于每个op=0的询问各输出一行，每行一个整数，表示当前的最小距离和。</p> 

 
 # 提示 
<p align="left">【输入输出样例说明】</p>

<p align="left">三次询问，都能将水泵设置在(1,4)上取得最小值。</p>

<p align="left">【数据说明】</p>

<p align="left">对于10%的数据，n&le;200，T=1，x,y&le;100；</p>

<p align="left">对于30%的数据，T=1；</p>

<p align="left">对于40%的数据，T&le;100；</p>

<p align="left">对于另外30%的数据，0&le;op&le;1；</p>

<p align="left">对于100%的数据，0&le;n&le;50,000，0&le;x,y&le;10,000，0&le;T&le;50,000，0&le;op&le;2。</p> 
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
<tr><td>3
1 4
2 3
0 7
7
0 0 0
1 4 4
0 0 0
2 2 3
1 0 7
1 1 0
0 0 0
</td><td>6
9
15
</td></tr></table>
