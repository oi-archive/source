# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2239/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjIzOS9wcm9ibGVtc19pbWFnZXMvMjYwMi8xMzExLmpwZw==.jpg"><br><br>其中:<br>Auv是与Aij相邻的像素(为了简化,认为(i-1,j),(i+1,j,(i,j-1),(i,j+1)为相邻元素);<br>Wij取值0或者1,表示Aij修改后取V0或者V1.<br>E的定义直观上的理解是,当修改了A之后,各像素上的值与原来的值相差了多少,以及相邻的像素对比程度的变化.为了图像的保真度,我们希望E的值越小越好.<br><br></p> 

 
 # 输入格式 
<p>
第一行二个整数N,M(1<=N,M<=35)<br>第二行二个整数V0,V1<br>接下来N行M列,对应矩阵元素Aij<br><br></p> 

 
 # 输出格式 
<p>
一个数E,表示最小可能的估价值<br></p> 
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
<tr><td>1 2
0 255
10 20

</td><td>30</td></tr></table>
