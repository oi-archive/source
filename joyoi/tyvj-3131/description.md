# 

 
 # 题目描述 
<p>
　　Tom当上了镇长，春风得意。他的辖区内新开了一条高速公路，公路上有两个车站，坐标分别为A（xa，ya）、B（xb，yb），每天都有车辆从A站开往B站。公路附近有两个村庄（公路可能从村庄中穿过），村庄分布在如图所示的带状区域内，坐标为C（xc，yc），D（xd，yd），C、D两村每天都分别有m人要前往B站。 <br><br><center><img src="/source/joyoi/tyvj-3131/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzEzMS9wcm9ibGVtc19pbWFnZXMvMTQxNS8xLmJtcA==.bmp"></img></center>  <br>　　因为高速公路不可随意出入，所以需要在两车站之间的公路上合理地设置一些汽车停靠点，村民可步行至停靠点后进入高速公路，并免费乘车前往B站。每个村民每步行一千米（一个单位看作一千米）所得到的政府补贴为t元，政府维护一个停靠点所需花费为p元/年。于是，一个棘手的问题摆在了Tom面前：应如何设置这些停靠点，才能使政府的支出最小？ <br><br>　　给出一个年份year，请你帮Tom设计一个方案，使得镇政府从该年起的n年内总支出最小。 <br><br>　　注意，村民只能进入停靠点而不能直接进入车站，但允许在车站处设置停靠点。 <br></p> 

 
 # 输入格式 
<p>
　　第一行四个数： xa ya xb yb <br>　　第二行四个数： xc yc xd yd <br>　　第三行四个数： m n t p （0 < m <= 3000，0< n <= 10） <br>　　第四行： 年份 year （2000 <= year <= 30000 ） <br>　　以上数字，m，year，n为正整数，p，t为正实数，其余均为实数。 <br></p> 

 
 # 输出格式 
<p>
　　第一行 最小费用c（单位：元 ,精确到小数点后四位） </p> 
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
<tr><td>-5 0 5 0
-1 -1 1 1 
1 1 1 500
2001</td><td>1532.3759</td></tr></table>
