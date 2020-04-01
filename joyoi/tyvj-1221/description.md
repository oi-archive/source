# 

 
 # 题目背景 
№.3<BR>Summer联盟战前兵力战略转移。 

 
 # 题目描述 
Summer的兵力分布在各个星球上，现在需要把他们全部转移到某个星球上。<BR>Summer一共拥有N个星球（1～N），你要把这N个星球上的兵力转到第M个星球上。本来每个星球之间都有星际轨道连接，但Guiolk监视了某些轨道，我们一但走上这些轨道，有可能受到他的攻击。为了安全，Summer不会走被监视的轨道。于是，只有L个星际轨道是被批准通过的。Summer的国防部想统计一下所需的最短路程（即每个星球到第M星球的最短路程总和，单位：M&nbsp;&nbsp;PS：'M'不是米）。<BR> 

 
 # 输入格式 
第一行有三个正整数，N，M，L（分别如题目描述）接下来L行，为被批准通行的轨道。每行有三个整数：a，b，c，表示第a个星球和第b个星球之间的轨道长cM（有重复）。 

 
 # 输出格式 
如果所有星球上的兵力能全部集中到第M个星球，则输出：&nbsp;最短路程和+“&nbsp;M(s)&nbsp;are&nbsp;needed.”如果某个星球的兵力不能到达第M个星球，则输出“Sth&nbsp;wrong.”。 

 
 # 提示 
对于30%的数据，1≤N≤20&nbsp;&nbsp;&nbsp;,&nbsp;&nbsp;&nbsp;L≤200<BR>对于80%的数据，1≤N≤600&nbsp;&nbsp;&nbsp;,&nbsp;&nbsp;&nbsp;L≤180000<BR>对于100%的数据，1≤N≤1000&nbsp;&nbsp;&nbsp;,&nbsp;&nbsp;&nbsp;1≤M≤N&nbsp;&nbsp;&nbsp;,&nbsp;&nbsp;&nbsp;L≤500000，&nbsp;&nbsp;&nbsp;1≤a,b≤N&nbsp;&nbsp;&nbsp;,&nbsp;&nbsp;&nbsp;0≤c≤10000。<BR>2010年广州市第二中学初二第二次测试第三题。 
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
<tr><td>【样例输入1】
5 3 6
1 2 1
1 3 3
2 3 1
4 1 5
4 5 2
5 1 2
【样例输入2】
5 3 4
1 2 1
1 3 3
2 3 1
5 1 2
</td><td>【样例输出1】
13 M(s) are needed.
【样例输出2】
Sth wrong.
</td></tr></table>
