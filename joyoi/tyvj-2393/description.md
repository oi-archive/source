# 

 
 # 题目描述 
<p>
Task: Frogs<br>一群青蛙正在摧毁Byteotia所有的庄稼. 一个叫Byteasar的农夫决定使用一种放在田里的奇特的"scarefrogs"来吓跑他们, 所有的青蛙在跳跃过程中都尽量使自己离他们越远越好, 即是让自己离最近的scarefrog越远越好. <br>Byteasar的田是块矩形的土地. 青蛙们跳跃的方向平行于坐标轴并且每次跳跃的距离为1. 一条跳跃路线的scarefrogs-距离为路径上所有点距离所有scarefrogs的最近距离. <br>Byteasar已经知道青蛙们的出发位置和目的地位置, 所以他在田里放置了若干个scarefrogs. 他请求你帮忙写一个程序找一条路径使得该路径的scarefrogs-距离最大. <br></p> 

 
 # 输入格式 
<p>
第一行包含两个整数: wx 和 wy 分别表示田地的宽和长( 2 <= wx, wy<=  1 000). 第二行包含四个整数: px, py, kx 和 ky 其中 (px, py) 为青蛙的起始位置, (kx, ky) 为目的地位置( 1 <= px, kx <= wx, 1<=  py, ky<=  wy). 第三行一个整数 n – 表示scarefrogs的总数( 1<=  n<=  wx . wy). 接下来n 行描述所有scarefrogs的坐标. 坐标用xi 和 yi 来描述第ith个 scarefrog的位置 ( 1 <= xi<=  wx, 1<=  yi<=  wy). 没有两个scarefrogs在同一个位置出现并且不会出现在(px, py) nor (kx, ky)上. <br></p> 

 
 # 输出格式 
<p>
一个整数代表目标路径scarefrog距离的平方. 如果青蛙不可避免遇到某些scarefrog那么答案为0. <br></p> 

 
 # 提示 
<p>
<img border="0" src="/source/joyoi/tyvj-2393/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjM5My9wcm9ibGVtc19pbWFnZXMvMjc4OS8xNTE0LmpwZw==.jpg"><br></p> 
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
1 1 5 5
2
3 3
4 2
</td><td>4
</td></tr></table>
