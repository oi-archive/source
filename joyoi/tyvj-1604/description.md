# 

 
 # 题目描述 
有n个炸弹，有些炸弹牵了一根单向引线（也就是说引线只有在这一端能被炸弹点燃），只要引爆了这个炸弹，用引线连接的下一个炸弹也会爆炸。每个炸弹还有个得分，当这个炸弹被引爆后就能得到相应得分。<BR>现在要你引爆k个炸弹，使得分最大。<BR> 

 
 # 输入格式 
第1行两个整数n、k。<BR>接下来n行每行两个整数a[i]、b[i]。a[i]表示这个炸弹用引线连接的下一个炸弹，如果a[i]为0，则表示这个炸弹没连接引线。b[i]表示这个炸弹的得分。<BR> 

 
 # 输出格式 
仅一个数，表示最大得分。 

 
 # 提示 
1≤b[i]≤1000000<BR>对于30%的数据，n≤1000	k≤30<BR>对于60%的数据，n≤50000	k≤100<BR>对于100%的数据，n≤200000&nbsp;k≤500<BR> 
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
<tr><td>8 2
0 1
1 1
2 100
2 100
0 1
5 1
6 2
6 2
</td><td>202
</td></tr></table>
