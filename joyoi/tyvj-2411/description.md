# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2411/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjQxMS9wcm9ibGVtc19pbWFnZXMvMjgxNy8xNTQ0LmpwZw==.jpg"> <br>我们只考虑射向整点的光线，那么这样的光线一共有(s+1)*(s+1)条。这些光线经过一系列平板镜子的反射（如果没有镜子阻挡也是可能直接射穿的）之后最终会从立方镜子的某个面出来（上图已经将面编号，并给定坐标轴方向）。现在你的任务就是求每个面出来的光线条数以及这些光线的反射次数和。<br></p> 

 
 # 输入格式 
<p>
第一行s,为立方镜子的边长。(1<=s<=2^15)<br>第二行m,为镜子个数。（1<=m<=200000）<br>下接m行，每行四个数描述一面镜子<br>x,y,z,d表示在坐标(x,y,z)的点上有一面方向为d的镜子。（0<=x,y,z<=s，0<=d<=5，保证不会有两个镜子坐标相同）<br><br></p> 

 
 # 输出格式 
<p>
共6组，每组两行，按顺序分别输出从面0到面5的出射光线条数，以及这部分光线的总反射次数。<br><br></p> 

 
 # 提示 
<p>
注：我们认为每个平板镜子都是无限薄的，即如果有一束光线从一个镜子的侧面射入，它会方向不变的射出。<br>样例解释：<br>2号面射出去了一根光线：从(4,0,0)落下击中(4,1,0)处的镜子然后射出去。反射次数为1<br>3号面射出去了一根光线：从(1,0,0)落下击中(1,1,0)处的镜子然后射出去。反射次数为1<br>剩余的的36-2=34条光线没有经过任何反射直接从4号面射出。<br>(1,3,0)处的镜子与(4,4,0)处的镜子没被用到。<br><br></p> 
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
4
4 4 0 0
1 3 0 1
1 1 0 0
4 1 0 1

</td><td>0
0
0
0
1
1
1
1
34
0
0
0
</td></tr></table>
