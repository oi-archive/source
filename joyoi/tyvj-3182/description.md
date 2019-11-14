# 

 
 # 题目描述 
<p>
轮廓线<br>　　&#8226; 每一个建筑物用一个三元组表示(L, H, R), 表示左边界, 高度和右边界。<br>　　&#8226; 轮廓线用X, Y, X, Y…这样的交替式表示。<br>　　&#8226; 右图的轮廓线为: (1, 11, 3, 13, 9, 0, 12, 7, 16,3, 19, 18, 22, 3, 23, 13, 29, 0) 。<br>　　&#8226; 给N个建筑，求轮廓线。<br><br><br><center><img src="/source/joyoi/tyvj-3182/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzE4Mi9wcm9ibGVtc19pbWFnZXMvMTUwNC8xLmJtcA==.bmp"></img></center><br></p> 

 
 # 输入格式 
<p>
　　输入数据共 n+1 行。<br>　　第一行，一个整数n。（ n <= 10^4 ）<br>　　第 2 至 n+1 行，每行有3个整数：L、H、R，分别表示一个建筑物：左边界、高度、右边界，数据均小于 2^30 。<br></p> 

 
 # 输出格式 
<p>
　　输出数据一行，建筑物的轮廓线，表示为：x　y　x　y　x　y　…………<br>　　（注：整数与整数之间用一个空格间隔）</p> 

 
 # 提示 
<p>
　　数据范围： <br>　　　30%数据，n <= 10^2。 <br>　　　50%数据，n <= 10^3。 <br>　　　100%数据，n <= 10^4。<br><br><br>（注：本题数据贡献者：东莞中学初中部　肖遥、潘熙、袁嘉豪，验证：东莞中学　何汶铬）<br></p> 
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
<tr><td>8
1 11 5
2 6 8
3 13 9
12 7 16
15 3 26
19 18 22
23 13 29
24 5 28</td><td>1 11 3 13 9 0 12 7 16 3 19 18 22 3 23 13 29 0 </td></tr></table>
