# 

 
 # 题目描述 
数学是一门让人头疼的学科...特别是数列那一章...<BR>有一天,又是数学课,SMoDaR终于忍无可忍,于是乎,萌生了这样一个想法:如果一个数列只有一项就好了...所以,几经纠结之后,决定简化序列.<BR>简化序列的方法是这样的:对于相邻的两项,可以将它们合为一项,但是需要付出max(a[i],a[i+1])的代价,合并之后这两项也就成为了1项max{a[i],a[i+1]}.显然,如果这个序列有n项,那么通过n-1次合并操作之后就可以将序列合并成1项了.<BR>于是,SMoDaR想知道最少需要付出多少的代价.<BR> 

 
 # 输入格式 
第一行:一个数N<BR>以下N行每行一个数,第i+1行表示的为a[i]<BR> 

 
 # 输出格式 
一个数M,最小的总代价<BR><BR> 

 
 # 提示 
数据规模:<BR>30%的数据&nbsp;N&lt;=10&nbsp;a[i]&lt;=100<BR>50%的数据&nbsp;N&lt;=100&nbsp;a[i]&lt;=100<BR>70%的数据&nbsp;N&lt;=10000&nbsp;a[i]&lt;=10000<BR>80%的数据&nbsp;N&lt;=100000&nbsp;a[i]&lt;=10000<BR>100%的数据&nbsp;N&lt;=1000000&nbsp;a[i]&lt;=1000000000<BR> 
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
1
2
3
4
</td><td>9
</td></tr></table>
