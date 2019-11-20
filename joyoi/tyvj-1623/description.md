# 

 
 # 题目描述 
假设有N个数写成一行，这行上面一行有N-1个数，第i数是第一行第i个数和第i+1个数的和。依次类推，最上面一行为第N行，有一个数。例如，4个数2,1,2,4形成如下结构：<BR>	&nbsp;&nbsp;&nbsp;15<BR>	&nbsp;&nbsp;6&nbsp;9<BR>	&nbsp;3&nbsp;3&nbsp;6<BR>	2&nbsp;1&nbsp;2&nbsp;4<BR>我们称这种结构为NumberPyramid。两个NumberPyramid相同当且仅当对应位置上的数相同。<BR>给出两个整数baseLength和top。计算出有多少个不同的仅包含正整数的NumberPyramid，使得NumberPyramid的最高的数为top，第一行有baseLength个数。由于答案可能过大，只需要输出模1,000,000,009的余数即可。<BR> 

 
 # 输入格式 
第一行两个整数baseLength，top。 

 
 # 输出格式 
一个整数，题目所求答案。 

 
 # 提示 
对于30%的数据，top&lt;=20，baseLength&lt;=5。<BR>对于100%的数据，2&lt;=baseLength&lt;=1,000,000，1&lt;=top&lt;=1,000,000。<BR> 
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
<tr><td>//样例输入1
3 5
//样例输入2
5 16</td><td>样例输出1
2
样例输出2
1</td></tr></table>
