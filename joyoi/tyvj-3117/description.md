# 

 
 # 题目描述 
<p>
【问题描述】(flower.cpp/c/pas)<br>花匠栋栋种了一排花，每株花都有自己的高度。花儿越长越大，也越来越挤。栋栋决定把这排中的一部分花移走，将剩下的留在原地，使得剩下的花能有空间长大，同时，栋栋希望剩下的花排列得比较别致。<br>具体而言，栋栋的花的高度可以看成一列整数h1 ,h2 , … ,hn。设当一部分花被移走后，剩下的花的高度依次为g1,g2, … ,gm ，则栋栋希望下面两个条件中至少有一个满足：<br><p align=center><img src="/source/joyoi/tyvj-3117/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzExNy9wcm9ibGVtc19pbWFnZXMvMTM3MC9wMS5naWY=.gif"></img></p></p> 

 
 # 输入格式 
<p>
输入文件为 flower.in。<br>输入的第一行包含一个整数n，表示开始时花的株数。<br>第二行包含&#119899;个整数，依次为h1 ,h2, … , hn，表示每株花的高度。<br></p> 

 
 # 输出格式 
<p>
输出文件为 flower.out。<br>输出一行，包含一个整数m，表示最多能留在原地的花的株数。<br></p> 

 
 # 提示 
<p>
【输入输出样例说明】<br>有多种方法可以正好保留 3 株花，例如，留下第 1、4、5 株，高度分别为 5、1、2，满足条件 B。<br><br><br>【数据范围】<br>对于 20%的数据，n ≤ 10；<br>对于 30%的数据，n ≤ 25；<br>对于 70%的数据，n ≤ 1000，0 ≤ hi ≤ 1000；<br>对于 100%的数据，1 ≤ n ≤ 100,000，0 ≤ hi ≤ 1,000,000，所有的hi 随机生成，所有随机数服从某区间内的均匀分布。<br><br></p> 
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
<tr><td>5
53212
</td><td>3</td></tr></table>
