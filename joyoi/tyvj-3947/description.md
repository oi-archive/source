# 

 
 # 题目背景 
<p>wyx&nbsp;noi&nbsp;Ag&nbsp;退役，回家种地。</p> 

 
 # 题目描述 
<p>wyx想找一个最好的位置来建新农场，这样他每天可以少走些路。&nbsp;wyx所在的区域，有&nbsp;N&nbsp;个城镇(1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;10,000)。&nbsp;城镇之间，有&nbsp;M(1&nbsp;&lt;=&nbsp;M&nbsp;&lt;=&nbsp;50,000)条双向路相连。&nbsp;所有城镇都可以借助一些路相互连接。&nbsp;wyx&nbsp;需要你的帮助来选择最合适建新农场的城镇。&nbsp;K(1&nbsp;&lt;=&nbsp;K&nbsp;&lt;=&nbsp;5)个城镇中有超市，wyx&nbsp;每天都会去这些超市。&nbsp;他计划每天从新农场出发，访问包含超市的&nbsp;K&nbsp;个城镇，然后返回新农场。&nbsp;wyx&nbsp;可以按照任意的顺序访问这些超市。&nbsp;wyx&nbsp;只会在&nbsp;N-K&nbsp;个城镇中，选择一个城镇来建新农场。因为其他城镇的房价，比较低一&nbsp;些。&nbsp;如果他把农场建在最优的位置，而且尽可能明智的选择行走路线。&nbsp;请帮&nbsp;wyx&nbsp;计算，他每天需要行走的路线长度。</p> 

 
 # 输入格式 
<p>第&nbsp;1&nbsp;行：三个空格隔开的整数，N，M&nbsp;和&nbsp;K。</p>

<p>第&nbsp;2..1+K&nbsp;行：第&nbsp;i+1&nbsp;行包含一个整数，范围&nbsp;1..N，表示包含第&nbsp;i&nbsp;个超市的城镇。&nbsp;每个超市在不同城镇。</p>

<p>第&nbsp;2+K..1+K+M&nbsp;行：每行包含三个空格隔开的整数，i，j(1&nbsp;&lt;=&nbsp;i，j&nbsp;&lt;=&nbsp;N)，和&nbsp;L(1&nbsp;&lt;=&nbsp;L&nbsp;&lt;=&nbsp;1000)，&nbsp;表示城镇&nbsp;i&nbsp;和城镇&nbsp;j&nbsp;之间存在一条长度为&nbsp;L&nbsp;的路。</p> 

 
 # 输出格式 
<p>如果他把农场建在最优的位置，wyx每天需要行走的最短路线长度。</p> 

 
 # 提示 
<p>在&nbsp;5&nbsp;号城镇建立农场。他每天的行走路线为&nbsp;5-1-2-3-2-1-5，路线长度为&nbsp;12</p>

<p>&nbsp;</p>

<p>30%的数据，N&lt;=100，M&lt;=1000</p>

<p>50%的数据，N&lt;=1000，M&lt;=5000</p>

<p>100%的数据范围如题中所示</p>

<p>&nbsp;</p> 
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
<tr><td>5 6 3
1
2
3
1 2 1
1 5 2
3 2 3
3 4 5
4 2 7
4 5 10
</td><td>12
</td></tr></table>
