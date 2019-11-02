# 

 
 # 题目背景 
09年&nbsp;USACO&nbsp;11月月赛&nbsp;&nbsp;铜牌第一道 

 
 # 题目描述 
示出了一个数字三角形。&nbsp;请编一个程序计算从顶至底的某处的一条路<BR>径，使该路径所经过的数字的总和最大。<BR>　　每一步可沿左斜线向下或右斜线向下走；<BR>　　1&lt;三角形行数&lt;25；<BR>　　三角形中的数字为整数&lt;1000；<BR><BR> 

 
 # 输入格式 
第一行为N，表示有N行<BR>后面N行表示三角形每条路的路径权 

 
 # 输出格式 
路径所经过的数字的总和最大的答案 

 
 # 提示 
搜索80分，记忆化搜索AC 
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
7
3 8
8 1 0
2 7 4 4
4 5 2 6 5
</td><td>30</td></tr></table>
