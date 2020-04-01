# 

 
 # 题目描述 
<p>
传说中亚特兰蒂斯是拥有高度发达史前文明的古老国度。精灵王对亚特兰蒂斯怀有特别的感情。古希腊的一些文献中保留着对亚特兰蒂斯的零星描述，每一段描述都为我们呈现了亚特兰蒂斯的一角，或者称为“地图碎片”。但是不同文献描述亚特兰蒂斯的不同部分，精灵王很希望知道文献中呈现过的亚特兰蒂斯“地图碎片”的总面积是多少。</p> 

 
 # 输入格式 
<p>
输入包含多组数据。对于每组数据：<br>第1行：整数n（1≤n≤100），表示“地图碎片”的总数。<br>第2…n+1行：每一行描述一块“地图碎片”。“地图碎片”呈矩形，用四个数字描述：x1，y1，x2，y2 (0 <= x1 < x2 <= 100000; 0 <= y1 < y2 <= 100000，不一定是整数)。(x1, y1) 是矩形左上角坐标，(x2, y2)是矩形右下角坐标。<br>当 n = 0 时输入结束。这种情况不用处理。<br></p> 

 
 # 输出格式 
<p>
对于每组数据。<br>第1行：输出“Test case #k”，k表示是第几组数据。<br>第2行：输出“Total explored area: a”，其中a是“地图碎片”呈现的亚特兰蒂斯的面积总和。<br></p> 
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
<tr><td>2
10 10 20 20
15 15 25 25.5
0
</td><td>Test case #1
Total explored area: 180.00</td></tr></table>
