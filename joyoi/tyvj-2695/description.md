# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2695/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjY5NS9wcm9ibGVtc19pbWFnZXMvMzE4NC8xOTE4LmpwZw==.jpg"> </p> 

 
 # 输入格式 
<p>
第一行包括一个整数 n，表示每队的选手数。 <br>第二行到第n + 1 行每行包含n 个实数，整体为一个&#56411; × &#56411;的矩阵，表示A 队<br>对B 队的胜率。其中第 i + 1 行的第 j个数表示选手 Ai对选手Bj时的胜率。 <br>第n+2 行为空行。 <br>第n + 3 行到第2n + 2 行每行包含n 个实数，同样为一个&#56411; × &#56411;的矩阵，表示<br>A队对C 队的胜率。其中第i + n + 2 行的第 j个数表示选手Ai对选手 Cj时的胜<br>率。 <br>第2n + 3 行为空行。 <br>第2n + 4 行到第3n + 3 行每行包含n 个实数，整体为一个&#56411; × &#56411;的矩阵，表<br>示B 队对 C队的胜率。其中第i + 2n + 3 行的第 j个数表示选手 Bi对选手Cj时的<br>胜率。 </p> 

 
 # 输出格式 
<p>
仅包含一个实数，保留 6 位小数，表示 A 队获得冠军的概<br>率。 </p> 

 
 # 提示 
<p>
 <br>30%的数据中，n ≤ 4。 <br>40%的数据中，n ≤ 5。 <br>100%的数据中，n ≤ 7。 <br>对于10%的数据有三个胜率矩阵中，每个矩阵的元素都相同，但不同矩阵的<br>数字可能不同。 <br> </p> 
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
<tr><td>3 
1.0 0.0 0.5 
0.5 1.0 1.0 
0.5 0.5 0.5 

0.5 0.5 1.0 
0.5 0.0 0.5 
0.5 0.5 0.5 
 
0.5 0.0 1.0 
0.5 0.5 0.5 
0.5 0.5 0.5  </td><td>0.273438 </td></tr></table>
