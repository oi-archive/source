# 

 
 # 题目描述 
<p>
在一个r行c列的网格地图中有一些高度不同的石柱，一些石柱上站着一些蜥蜴，你的任务是让尽量多的蜥蜴逃到边界外。 

 
 # 输入格式 
<p>
输入第一行为三个整数r，c，d，即地图的规模与最大跳跃距离。以下r行为石竹的初始状态，0表示没有石柱，1~3表示石柱的初始高度。以下r行为蜥蜴位置，“L”表示蜥蜴，“.”表示没有蜥蜴。 

 
 # 输出格式 
<p>
输出仅一行，包含一个整数，即无法逃离的蜥蜴总数的最小值。 

 
 # 提示 
<p>
100%的数据满足：1<=r, c<=20, 1<=d<=3
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
<tr><td>5 8 2
00000000
02000000
00321100
02000000
00000000
........
........
..LLLL..
........
........

</td><td>1
