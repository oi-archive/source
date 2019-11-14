# 

 
 # 题目描述 
<p>
在瑞典的达拉纳洲有一座高山。山上有一个小屋，里面住着一位牧羊女。每天清晨，隔壁的山头会传来一阵悠扬的长笛声，而牧羊女则会站在屋里用自己的歌声回应。<br>小屋的俯视图是一个有n个顶点的简单多边形，每一面墙可以反射声音，但是由于不可避免的能量损失，最多只能反射k次（k=0表示不能反射声音）。墙面非常光滑，因此声音的反射遵循反射角等于入射角，如图1。墙角不能反射声音，而每面墙的其他部分——即使离墙角很近——都可以反射声音。<br><img border="0" src="/source/joyoi/tyvj-3606/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzYwNi9wcm9ibGVtc19pbWFnZXMvMjQ1Ny8xMTU5XzEuanBn.jpg"><br>图1. 声音的反射<br><br>突然有一天，牧羊女问自己：在小屋的哪些地方能听到她的歌声？假设所有听众都在屋里靠墙而坐，那么歌声能到达的墙一共有多长？<br>图2的四幅示意图分别画出了初始情况和声音经过0、1、2次反射后到达的区域。灰色部分表示能听到歌声的部分，黑点表示牧羊女的位置。本题所求即灰色部分在多边形边界上的总长度。<br><img border="0" src="/source/joyoi/tyvj-3606/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzYwNi9wcm9ibGVtc19pbWFnZXMvMjQ1Ny8xMTU5XzIuanBn.jpg"><br>              (a) 初始情况                                 (b)声音发出后未经反射<br><img border="0" src="/source/joyoi/tyvj-3606/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzYwNi9wcm9ibGVtc19pbWFnZXMvMjQ1Ny8xMTU5XzMuanBn.jpg">  <br>              (c) 声音1次反射                                  (d) 声音2次反射<br>图2. 能听到歌声的区域<br><br></p> 

 
 # 输入格式 
<p>
第一行包含4个整数n，k，x，y分别表示小屋的墙角数、最多反射的次数以及牧羊女的坐标（牧羊女所在位置保证在屋内且至少离墙1个单位）。以下n行每行两个整数x, y，表示第i个墙角的坐标。墙角按照顺时针或逆时针排列。<br><br></p> 

 
 # 输出格式 
<p>
输出文件仅包含一个实数L，表示能听到歌声的墙的总长度。保留两位小数。<br><br></p> 

 
 # 提示 
<p>
【评分方法】<br>选手输出和参考输出差的绝对值不大于0.02时该测试点满分，相差超过0.02但不超过1时该测试点得50%的分数。在样例1中，答案为469.84和469.88都能拿满分，468.86和470.86都能拿50%的分数。<br><br>【约定】<br>3<=n<=50，0<=k<=5，所有坐标为绝对值不超过1000的整数<br>50%的数据满足k<=1<br></p> 
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
<tr><td>【样例输入1】
5 0 100 135
20 200
200 100
300 125
40 10
100 100


【样例输入2】
8 1 25 15
0 0
0 20
30 20
30 0
20 0
20 10
10 10
10 0

</td><td>【样例输出1】
469.86

【样例输出2】
106.67
</td></tr></table>
