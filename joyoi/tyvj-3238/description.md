# 

 
 # 题目描述 
<p>
距离查询（qu.pas/c/cpp）<br><br>【问题描述】<br><br>　 　 农民约翰的奶牛拒绝在跑他的马拉松，因为他选择的路径太长不适合奶牛们悠闲的生活方式。因此，他希望找到一个更合理的路径长度。农民约翰要查询一系列点对间的路径长度，请尽快回答农民约翰的询问！<br></p> 

 
 # 输入格式 
<p>
第一行包括两个整数N，M，N (2 <= N <= 40，000)表示农场数量，每个农场标记为1-N，M (1 <= M < 40，000)表示路径数量。<br>第二至M+1行，每行包括三个整数F1，F2，L和一个字符D，表示农场F1和F2之间的路径长度为L，D为'N'， 'E'， 'S'， 'W'中的一个，表示从F1到F2的方向。<br>第M+2行包括一个整数K，1 <= K <= 10，000<br>第M+3至M+K+2行，每行包括两个整数，表示要询问的两个农场。</p> 

 
 # 输出格式 
<p>
共K行，每行输出每个询问的路径长度。</p> 

 
 # 提示 
<p>
Farms 2 and 6 are 20+3+13=36 apart. </p> 
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
<tr><td>7 6
1 6 13 E
6 3 9 E
3 5 7 S
4 1 3 N
2 4 20 W
4 7 2 S
3
1 6
1 4
2 6


</td><td>13
3
36</td></tr></table>
