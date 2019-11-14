# 

 
 # 题目描述 
<p>
某个房子的屋顶如下图所示…。 <br><br><img border="0" src="/source/joyoi/tyvj-2347/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjM0Ny9wcm9ibGVtc19pbWFnZXMvMjcyNy8xNDUxLmpwZw==.jpg"><br><br> <br><br>在单位时间单位长度降雨量为1单位的时候，每条“屋顶”，都有一个单位时间落下的水量（就是单位时间从屋顶较低的那一侧落下去的水量），现在希望对于每个屋顶，算出它的落水量。 </p> 

 
 # 输入格式 
<p>
第一行一个数N（1<=N<=20000），表示屋顶的个数。 <br>接来下N行，每行4个整数，X0,Y0,X1,Y1,描述一个屋顶（坐标范围[-1000000,1000000]，保证屋顶一定是斜的，屋顶不会有任何公共点）。 <br><br></p> 

 
 # 输出格式 
<p>
一共N行，每行一个数，表示第I个屋顶的落水量。 <br></p> 
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
<tr><td>6
13 7 15 6
3 8 7 7
1 7 5 6
5 5 9 3 
6 3 8 2
9 6 12 8

</td><td>2
4
2
11
0
3
</td></tr></table>
