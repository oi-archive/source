# 

 
 # 题目描述 
<p>
【题目描述】<br>　　你有一个长为 N 宽为 2 的墙壁，给你两种砖头：一个长 2 宽 1，另一个是 L 型覆盖3个单元的砖头。如下图： <br>  <br><center><img src="/source/joyoi/tyvj-3297/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzI5Ny9wcm9ibGVtc19pbWFnZXMvMjAyNy8xLmJtcA==.bmp"></img></center><br>　　砖头可以旋转，两种砖头可以无限制提供。你的任务是计算用这两种来覆盖 N*2的墙壁的覆盖方法。例如一个2*3的墙可以有5种覆盖方法，如下： <br>  <br><center><img src="/source/joyoi/tyvj-3297/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzI5Ny9wcm9ibGVtc19pbWFnZXMvMjAyNy8yLmJtcA==.bmp"></img></center><br>　　注意可以使用两种砖头混合起来覆盖。如2*4 的墙可以这样覆盖： <br>  <br><center><img src="/source/joyoi/tyvj-3297/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzI5Ny9wcm9ibGVtc19pbWFnZXMvMjAyNy8zLmJtcA==.bmp"></img></center><br>　　给定 N，要求计算 2*N 的墙壁的覆盖方法。由于结果很大，所以只要求输出最后4位。例如2*13的覆盖方法为13465，只需输出3465即可。如果答案少于4位，就直接输出就可以，不用加0，如N=3时输出5。 <br></p> 

 
 # 输入格式 
<p>
　　一个整数N(1≤N≤1000000)，表示墙壁的长。 <br></p> 

 
 # 输出格式 
<p>
　　输出覆盖方法的最后4位，如果不足4 位就输出整个答案。 <br></p> 
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
<tr><td>【样例输入】 
13 
</td><td>【样例输出】 
3465</td></tr></table>
