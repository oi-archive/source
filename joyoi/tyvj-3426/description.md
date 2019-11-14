# 

 
 # 题目描述 
<p>
Humps（Humps.pas\c\cpp）<br><br>【题目描述】<br>　　在Humps岛上有n个村庄，村庄之间有一些双向的道路，这些道路都是田园小路。岛上的居民准备重新修建一部分道路，即将一部分小道修成大公路。但为了公平起见，必须使得每个村庄连接的道路都恰好有一半修成公路。<br>　　保证一定有解。<br></p> 

 
 # 输入格式 
<p>
　　输入文件Humps.in第一行为n(n≤30000)，m(m≤400000)，分别表示村庄数和道路数。<br>　　接下来m行每行两个数x, y(x <> y), 表示有一条道路连接村庄x和y。<br>　　保证每个村庄连接的道路数为偶数，且任意两个村庄之间最多有一条路。<br></p> 

 
 # 输出格式 
<p>
　　输出文件Humps.out每行两个数x, y表示把村庄x到村庄y之间的道路修成公路。</p> 
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
<tr><td>5 6
1 2
5 4
1 4
1 5
2 3
3 1
</td><td>
1 2
1 3
4 5
</td></tr></table>
