# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;山火来了，Fox们遇到了前所未有的危机，他们需要马上撤离这个区域。但是居住在离山火区域较远的Fox仍然不知道危险降临。这个时候，前方的Fox要用叫声来提醒其他的Fox。Fox的视野为S米，叫声最远能传到D米之外。山上有p处着火的地点，当着火点在Fox的视野中时，Fox就会发出叫声（进入视野是指Fox与火点距离&lt;=S）。因为山风，声音传播的速度为v米/秒。那么如果要使所有的Fox都得到危险信号，至少需要多长时间？<BR>	假设着火点为一个整数坐标，着火点不会移动也不会扩大。Fox听到同伴叫声就会立刻把信号传递下去。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第1行两个整数n，p，表示Fox数量和着火点数量<BR>	第2行三个整数&nbsp;S，D，v<BR>	第3~p+2行，每行两整数x,y表示着火点坐标<BR>	接下来n行每行两个整数x,y表示Fox坐标 

 
 # 输出格式 
使所有Fox都得到信号所需的最短时间，答案为四舍五入之后的整数。题目保证所有Fox最终都会得到信号，不存在Fox哑嗓子或者被山火烧死的可能。 

 
 # 提示 
对于100%的数据&nbsp;n&lt;=2000<BR>			&nbsp;&nbsp;&nbsp;p&lt;=10<BR>			&nbsp;&nbsp;&nbsp;s,d,v&lt;=1000<BR>坐标绝对值小于等于10000来源：Delostik	开学欢乐赛 
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
<tr><td>2 1
2 2 1
0 0
0 2
0 4
</td><td>2
</td></tr></table>
