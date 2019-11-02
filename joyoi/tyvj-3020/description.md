# 

 
 # 题目描述 
<p>
Bill在研究学校里的蚂蚁，他饲养了许多蚂蚁，分为若干蚁群。<br>每个蚁群都需要靠一棵苹果树养活。<br>Bill画出了N个蚁群和N颗苹果树的坐标地图。他知道，蚂蚁们来回于聚居地和苹果树之间时，使用某种化学物质来标记路线。路线不能彼此相交，否则蚂蚁们会感到困惑，可能走到错误的聚居地或苹果树，从引发蚁群之间的战争。<br>Bill希望每个蚁群连接到唯一一棵苹果树，并保证所有的n条路线互不相交。（路线必须是直线！）<br>本题保证这样的连接始终存在。<br>你的任务是写一个程序，找到这种连接方案。<br><center><img src="/source/joyoi/tyvj-3020/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzAyMC9wcm9ibGVtc19pbWFnZXMvMzYzNS8zNTY1XzEuZ2lm.gif"></img></center></p> 

 
 # 输入格式 
<p>
输入文件的第一行包含一个整数N(1≤N≤100)，表示有N个蚁群和N棵苹果树。接下来N行描述N个蚁群的聚居地，再接着N行描述N棵苹果树。每个蚁群和苹果树都由一对整数x和y描述（-10000 ≤ x, y ≤10000）。所有点都在同一平面上。所有蚁群和苹果树占据平面上的不同点。不会出现三点共线的情况。</p> 

 
 # 输出格式 
<p>
输出N行，每行一个整数。第i行上写的数字表示第i个（1到N）蚁群连向的苹果树的编号。</p> 
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
-42 58
44 86
7 28
99 34
-13 -59
-47 -44
86 74
68 -75
-68 60
99 -60
</td><td>4
2
1
5
3</td></tr></table>
