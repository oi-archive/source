# 

 
 # 题目背景 
<p>由于不知道外星人是敌是友，S国决定围住飞碟。</p> 

 
 # 题目描述 
<p>已知该飞碟是一个不规则的多面体结构，为了简单起见，我们用三维格点来描述它。专家们只被能在连续的格点（有一个面相邻）上布置封锁武器。现给定该飞碟的三维&ldquo;地图&rdquo;，请求出最少需要多少封锁武器才能封锁该飞碟。下面给定一个2维的封锁方案（3维画不出来，实在抱歉）。<br />
<img align="middle" border="0" src="/source/joyoi/tyvj-1508/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTUwOC9odHRwOi8vdHl2ai5jcHd6LmNuL1Byb2JsZW1JbWcvcDE1MDgtMS5naWY=.gif" /><br />
<img align="middle" border="0" src="/source/joyoi/tyvj-1508/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTUwOC9odHRwOi8vdHl2ai5jcHd6LmNuL1Byb2JsZW1JbWcvcDE1MDgtMi5naWY=.gif" /><br />
<br />
上图中黑色为飞碟，红色为包围方案。白色为空格。二维的相邻退化成了有一条公共边，而三维相邻则是有一个公共面。可见一个&ldquo;地图&rdquo;有多种最优包围方案，即方案数不唯一。所以只要求最小的包围代价。</p> 

 
 # 输入格式 
<p>第一行：一个数N，表示地图为一个N*N*N的正方体；<br />
接下来N个矩阵，从上到下描绘每一个面：<br />
每一个矩阵中有N行N列0或者1。<br />
其中0表示该节点不是飞碟的一部分，1表示是该飞碟的一部分</p> 

 
 # 输出格式 
<p>仅一行：表示最少的武器数量。</p> 

 
 # 提示 
<p>数据范围:<br />
100%&nbsp;&nbsp;&nbsp;N&lt;=20<br />
保证所有的1是联通的一块，并且星球边界一定不与地图边界重合，即总是有的可包围的！Skywalker_Q</p> 
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
 0 0 0 0 0
 0 0 0 0 0
 0 0 0 0 0
 0 0 0 0 0
 0 0 0 0 0

 0 0 0 0 0
 0 0 1 0 0
 0 0 1 0 0
 0 0 0 0 0
 0 0 0 0 0

 0 0 0 0 0
 0 0 1 0 0
 0 1 1 0 0
 0 1 0 0 0
 0 0 0 0 0

 0 0 0 0 0
 0 0 1 0 0
 0 1 1 1 0
 0 0 0 0 0
 0 0 0 0 0

 0 0 0 0 0
 0 0 0 0 0
 0 0 0 0 0
 0 0 0 0 0
 0 0 0 0 0

</td><td>80
</td></tr></table>
