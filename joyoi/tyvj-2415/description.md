# 

 
 # 题目描述 
<p>
有N堆石子，除了第一堆外，每堆石子个数都不少于前一堆的石子个数。两人轮流操作<br>每次操作可以从一堆石子中移走任意多石子，但是要保证操作后仍然满足初始时的条件<br>谁没有石子可移时输掉游戏。问先手是否必胜。<br></p> 

 
 # 输入格式 
<p>
第一行u表示数据组数。<br>对于每组数据，第一行N表示石子堆数，第二行N个数ai表示第i堆石子的个数(a1<=a2<=……<=an)。<br><br><br>1<=u<=10<br>1<=n<=1000<br>0<=ai<=10000<br><br></p> 

 
 # 输出格式 
<p>
u行，若先手必胜输出TAK，否则输出NIE。<br><br></p> 

 
 # 提示 
<p>
感谢MT大牛翻译.</p> 
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
<tr><td>2
2
2 2
3
1 2 4

</td><td>NIE
TAK</td></tr></table>
