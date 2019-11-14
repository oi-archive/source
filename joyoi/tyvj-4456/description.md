# 

 
 # 题目背景 
<h3>来源</h3>

<p>Vijos&nbsp;1524</p>

<h3>版权</h3>

<p>版权归Vijos所有。若Tyvj在无意中侵犯了您的权利或利益，请联系管理员删题，以避免不必要的纠纷。让我们一起创造一个美好的OI训练环境！</p> 

 
 # 题目描述 
<p>由于yxy小朋友做了一些不该做的事，他被jzp关进了一个迷宫里。由于jzp最近比较忙，疏忽大意了一些，yxy可以在迷宫中任意走动。整个迷宫可以被看作是一个无向图。迷宫中有一些结点有传送点，可以让他逃离这个迷宫。jzp发明了一种机器人，可以监视迷宫中的道路，被监视的道路yxy不能通过，我们简单的认为监视一条道路的代价即为这条道路的长度。现在jzp正在忙，请你编一个程序算出使yxy无法逃离迷宫的最小监控总代价。(yxy一开始在1号结点)</p> 

 
 # 输入格式 
<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">第1行：两个自然数n和e，分别表示迷宫的节点数和边数。</p>

<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">第2至e+1行：每行三个自然数a、b和w，表示a和b之间有一条道路，长度为w。</p>

<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">第e+2行：一个自然数m，表示有传送点结点的个数。</p>

<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">第e+3行：m个自然数，表示有传送点的结点。</p> 

 
 # 输出格式 
<p><span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">一个自然数，表示最小监视总代价。</span></p> 

 
 # 提示 
<h3>数据范围和约定</h3>

<p><span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">n&lt;100,e&lt;300,m&lt;n</span><br style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;" />
<span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">1&lt;=a,b&lt;=n</span><br style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;" />
<span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">w&lt;=maxint</span></p> 
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
<tr><td>5 5
1 2 1
1 3 2
2 5 3
2 3 3
3 4 2
2
4 5</td><td>3</td></tr></table>
