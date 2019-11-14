# 

 
 # 题目描述 
<p>
城堡围墙（wall.pas/c/cpp)<br><br>【问题描述】<br>　　国王要在自己的城堡周围修建一圈围墙。但是国王并不打算把围墙修建得很漂亮，而是想尽量节省材料。同时还有一个要求，就是围墙离城堡不能少于一定的距离。<br><br><center><img src="/source/joyoi/tyvj-3248/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzI0OC9wcm9ibGVtc19pbWFnZXMvMTgwNi9wMS5naWY=.gif"></img></center><br>　　你作为国王的建筑设计师，要求找出符合条件的最节省材料的方案。并求出围墙的长度。这个任务并不简单，所幸的是，城堡是一个多边形，而且是建造在一片平地上的。测量师已经进行了精密的测量，他建立了一个直角坐标系，并把城堡每个顶点的坐标测出来了。你可以直接利用这些数据。<br></p> 

 
 # 输入格式 
<p>
　　第一行有两个整数N和L，中间用一个空格隔开。N（3≤N≤1000）表示城堡的顶点数，L（1≤L≤1000）表示围墙离城堡的最小距离。接下来的N行以顺时针的顺序给出了城堡顶点的坐标，第i+1行包括两个整数Xi和Yi，以空格隔开（-10000≤Xi，Yi≤10000）表示第i个顶点的坐标。所有顶点都是不同的，而且城堡的城墙不会交叉。<br></p> 

 
 # 输出格式 
<p>
　　输出文件只有一行，这一行只有一个整数，即围墙的最小长度。要求精确到个位。<br></p> 

 
 # 提示 
<p>
结果四舍五入即可<br></p> 
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
<tr><td>9 100
200 400
300 400
300 300
400 300
400 400
500 400
500 200
350 200
200 200
</td><td>1628</td></tr></table>
