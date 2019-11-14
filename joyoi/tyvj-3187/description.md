# 

 
 # 题目描述 
<p>
我先来说几句：<br>====================================================================================================<br>　　下面大家即将见到的是一道经典的广度搜索（bfs）题，bfs算法的运行耗时主要集中在状态扩展和状态判重上，大部分情况下，状态判重的耗时是远大于状态扩展的（假设可能扩展的状态数量为n，则其运算量分别为：o(n)和o(n^2)），如果在bfs算法中使用hash表去判重，则可以极大的提高运行效率。因此，bfs+hash，会是解决相当多搜索题的杀手锏！<br>　　就下面例题而言，注意到每种状态构成了一个排列，我们可以给它分配一个编号，总共的状态数不会超过9！=362880种。（关于排列直接换算分配hash地址，可以见P1511理论基础知识，因此题状态数比较少，你可以使用简化的散列（hash）函数解决此题）。<br>====================================================================================================<br>　　问题来了，重排九宫：<br>　　将数字1~8按照人依次序排在3*3的方格阵列中，留下一个空位供数字方块移动，游戏的最终目标是通过合法移动将数字按行排好序。<br>输入举例：<br><br><img src="/source/joyoi/tyvj-3187/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzE4Ny9wcm9ibGVtc19pbWFnZXMvMTU0MS8xLmJtcA==.bmp"></img><br><br>目标：<br><br><img src="/source/joyoi/tyvj-3187/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzE4Ny9wcm9ibGVtc19pbWFnZXMvMTU0MS8yLmJtcA==.bmp"></img><br><br>输出达到目标状态的最少移动次数。</p> 

 
 # 输入格式 
<p>
　　3*3的输入方阵，格式见样例。</p> 

 
 # 输出格式 
<p>
　　一个整数，达到目标状态的最少移动次数。</p> 

 
 # 提示 
<p>
　　本题测试数据贡献者：东莞中学初中部　肖遥</p> 
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
<tr><td>1 2 3                         
4 0 6                          
7 5 8
</td><td>2</td></tr></table>
