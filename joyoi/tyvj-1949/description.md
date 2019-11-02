# 

 
 # 题目描述 
外星人入侵地球。可怕的吃人外星人正在全国各地依次序建立它们的基地。<BR>全国共有N（1≤N≤10，000）座城市，城市编号1-N。城市之间有M（1≤M≤100，000）条双向道路相连。外星人计划建立A（0≤A≤N）个基地。<BR>你只有在距离当前所有外星人基地至少K（1≤K≤100）单位长度的城市才能得到安全。<BR>所以你必须赶快写一个程序决定走到哪里去。<BR> 

 
 # 输入格式 
第1行：4个整数N，M，A，K。<BR>接下来M行，每行3个整数T1，T2（1≤T1＜T2≤N）和D（1≤D≤100），表示城市T1与T2之间有一条长度为D的道路。两个城市之间最多有一条直连道路。<BR>接下来A行，每行1个整数Bi（1≤Bi≤N），表示外星人依次序建立的第i个基地所在的城市编号。<BR> 

 
 # 输出格式 
共A行，第i行1个整数，表示当外星人建立好第i个基地后，距离当前所有基地B1，B2，……Bi至少K长度的城市的数量。 
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
<tr><td>7 6 3 3
1 2 1
1 3 1
2 5 1
3 6 1
1 4 1
4 7 2
2 
1
4
</td><td>2
1
0
</td></tr></table>
