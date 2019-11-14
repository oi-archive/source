# 

 
 # 题目背景 
<p>给定一个正整数序列a(1)，a(2)，...，a(n),(1&lt;=n&lt;=20)<br />
不改变序列中每个元素在序列中的位置，把它们相加，并用括号记每次加法所得的和，称为中间和。<br />
&nbsp;&nbsp;例如:<br />
&nbsp;&nbsp;给出序列是4，1，2，3。<br />
&nbsp;&nbsp;第一种添括号方法:<br />
&nbsp;((4+1)+(2+3))=((5)+(5))=(10)<br />
&nbsp;&nbsp;有三个中间和是5，5，10，它们之和为:5+5+10=20<br />
&nbsp;&nbsp;第二种添括号方法&nbsp;&nbsp;<br />
&nbsp;&nbsp;(4+((1+2)+3))=(4+((3)+3))=(4+(6))=(10)<br />
&nbsp;&nbsp;中间和是3，6，10，它们之和为19。</p> 

 
 # 题目描述 
<p>现在要添上n-1对括号，加法运算依括号顺序进行，得到n-1个中间和，求出使中间和之和最小的添括号方法。</p> 

 
 # 输入格式 
<p>共两行。<br />
第一行，为整数n。(1&lt;=n&lt;=20)<br />
第二行，为a(1),a(2),...,a(n)这n个正整数，每个数字不超过100。</p> 

 
 # 输出格式 
<p>输出3行。<br />
第一行，为添加括号的方法。<br />
第二行，为最终的中间和之和。<br />
第三行，为n-1个中间和，按照从里到外，从左到右的顺序输出。</p> 

 
 # 提示 
<p>在相同的情况下，括号<span style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI'; font-size: 12px; line-height: 20px;">尽可能向左加</span>MaoLaoda</p> 
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
4 1 2 3
</td><td>(4+((1+2)+3))
19
3 6 10
</td></tr></table>
