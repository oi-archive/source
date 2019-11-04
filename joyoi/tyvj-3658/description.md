# 

 
 # 题目描述 
<p>
一种新型的激光炸弹，可以摧毁一个边长为R的正方形内的所有的目标。现在地图上有n(N<=10000)个目标，用整数Xi,Yi(其值在[0,5000])表示目标在地图上的位置，每个目标都有一个价值。激光炸弹的投放是通过卫星定位的，但其有一个缺点，就是其爆破范围，即那个边长为R的正方形的边必须和x，y轴平行。若目标位于爆破正方形的边上，该目标将不会被摧毁。 0<Vi<100

 
 # 输入格式 
<p>
输入文件的第一行为正整数n和正整数R，接下来的n行每行有3个正整数，分别表示</p> 

 
 # 输出格式 
<p>
输出文件仅有一个正整数，表示一颗炸弹最多能炸掉地图上总价值为多少的目标（结果不会超过32767）。</p> 
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
<tr><td>2 1
0 0 1
1 1 1</td><td>
1</td></tr></table>