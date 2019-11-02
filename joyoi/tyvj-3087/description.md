# 

 
 # 题目描述 
<p>
　　CE数码公司开发了一种名为自动涂色机（APM）的产品。它能用预定的颜色给一块由不同尺寸且互不覆盖的矩形构成的平板涂色。<br><br><center><img src="/source/joyoi/tyvj-3087/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzA4Ny9wcm9ibGVtc19pbWFnZXMvMTI0OC8xLmJtcA==.bmp"></img></center><br><br>　　为了涂色，APM需要使用一组刷子。每个刷子涂一种不同的颜色C。APM拿起一把有颜色C的刷子，并给所有颜色为C且符合下面限制的矩形涂色：<br>　　为了避免颜料渗漏使颜色混合，一个矩形只能在所有紧靠它上方的矩形涂色后，才能涂色。例如图中矩形F必须在C和D涂色后才能涂色。注意，每一个矩形必须立刻涂满，不能只涂一部分。<br>　　写一个程序求一个使APM拿起刷子次数最少的涂色方案。注意，如果一把刷子被拿起超过一次，则每一次都必须记入总数中。<br></p> 

 
 # 输入格式 
<p>
　　文件paint.in第一行为矩形的个数N。下面有N行描述了N个矩形。每个矩形有5个整数描述，左上角的y坐标和x坐标，右下角的y坐标和x坐标，以及预定颜色。<br>　　颜色号为1到20的整数。<br>　　平板的左上角坐标总是(0, 0)。<br>　　坐标的范围是0..99。<br>　　N小于16。<br></p> 

 
 # 输出格式 
<p>
　　输出至文件paint.out，文件中记录拿起刷子的最少次数。</p> 

 
 # 提示 
<p>
【问题分析】<br>　　指数型动态规划。<br>　　由于N小于16，故可以以一个N-bit的二进制数A作为状态，其中每个二进制位表示一个格子的涂色情况，二进制位0表示该格子未被涂色，二进制1表示该格子已被涂色。<br>　　用F[A]表示要得到状态A，最少需要改变多少次颜色。对于每个状态A，通过枚举涂色方案来推新的状态。<br></p> 
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
<tr><td>7						
0 0 2 2 1
0 2 1 6 2
2 0 4 2 1
1 2 4 4 2
1 4 3 6 1
4 0 6 4 1
3 4 6 6 2
</td><td>3</td></tr></table>
