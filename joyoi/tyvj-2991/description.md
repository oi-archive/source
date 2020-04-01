# 

 
 # 题目描述 
<p>
给出一个长方体的箱子，还有在箱子里面的N个长方体的盒子，箱子和盒子的各个边都是平行于某个三维坐标轴。现在要求你找出其中最大的立方体空间，输出它的长度。<br>首先这个空间必须位于箱子里面，而且不能与其它的盒子占的空间冲突。这个空间也必须是各边平行于某个坐标轴。如下图所示。<br><br><br><center><img src="/source/joyoi/tyvj-2991/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjk5MS9wcm9ibGVtc19pbWFnZXMvMzYwMC90LmJtcA==.bmp"></img></center></p> 

 
 # 输入格式 
<p>
测试文件含有多组数据。测试文件的第一行是数据个数T。接下来是T组数据。<br>每组数据的第一行是4个整数N,L,W,H。分别表示盒子的个数和箱子的长宽高（分别对应X,Y,Z轴）。<br>然后N行，每行有6个整数xi yi zi Xi Yi Zi描述了第i个盒子，(xi, yi, zi)表示盒子的后左下角（坐标值最小的那个角），Xi Yi Zi则表示前右上角（坐标值最大的那个角）。所有结出的盒子都在箱子里面而且不会相互相交。<br></p> 

 
 # 输出格式 
<p>
对于每组数据输出一行”Case X: Y”（不带引号，冒号后面有空格），其中X是测试数据编号（从1开始）。Y 是最大立方体空间的边长。如果箱子中没有空余的空间，那么Y就是0。</p> 

 
 # 提示 
<p>
<br><left><img src="/source/joyoi/tyvj-2991/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjk5MS9wcm9ibGVtc19pbWFnZXMvMzYwMC90Mi5ibXA=.bmp"></img></left></p> 
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
<tr><td>1
2 10 15 8
0 0 0 4 11 3
0 11 0 4 15 8
</td><td>Case 1: 6</td></tr></table>
