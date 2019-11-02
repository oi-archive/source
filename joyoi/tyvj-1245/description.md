# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;听说过取数游戏吗？这是一个很简单的游戏，给出N个数D1~Dn。第i次取数的得分是Dx*i（Dx为这次取的数），共取N次，取过的数不能再取；如果这次取得数和上次取的数相等，还能得到额外奖励分数P。取出数字的得分等于各次取数得分的总和。<BR>&nbsp;&nbsp;&nbsp;&nbsp;乌龟希望取数得分最大。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入的第一行是两个正整数N，P。空格隔开。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来N行，每行一个正整数Di。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出只有一行，由于最高得分可能很大，只要求输出最高得分除以1000的余数。 

 
 # 提示 
样例中最高得分为9186，除以1000余数为186。<BR>对于80%的数据，N≤1000。<BR>对于100%的数据，N≤30000，P＜2^30，Di≤2^30。<BR>EZ_lzh。第一次举办比赛，出得不好或有错，请多包涵。 
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
<tr><td>9 10
1
2
3
4
5
5
6
6
999
</td><td>186
</td></tr></table>
