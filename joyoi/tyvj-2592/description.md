# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2592/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjU5Mi9wcm9ibGVtc19pbWFnZXMvMzAzMS8xNzU4LmpwZw==.jpg"></p> 

 
 # 输入格式 
<p>
第一行包含一个正整数N，表示X国的城市个数.<br>第二行包含两个正整数L和U，表示政策要求的第一期重建方案中修建道路数的上下限<br>接下来的N-1行描述重建小组的原有方案，每行三个正整数Ai,Bi,Vi分别表示道路(Ai,Bi),其价值为Vi<br>其中城市由1..N进行标号</p> 

 
 # 输出格式 
<p>
输出最大平均估值，保留三位小数</p> 

 
 # 提示 
<p>
20%的数据,N<=5000<br>30%的数据,N<=100000,原有方案恰好为一条路径<br>100%的数据,N<=100000,1<=L<=U<=N-1,Vi<=1000000</p> 
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
<tr><td>4 
2 3 
1 2 1 
1 3 2 
1 4 3 </td><td>2.500</td></tr></table>
