# 

 
 # 题目描述 
阿达马矩阵如下：<BR><BR>A0={1}&nbsp;&nbsp;&nbsp;A1={1&nbsp;1}&nbsp;A2={1&nbsp;1&nbsp;1&nbsp;1}<BR>　　{1&nbsp;0}　　{1&nbsp;0&nbsp;1&nbsp;0}<BR>　　&nbsp;{1&nbsp;1&nbsp;0&nbsp;0}<BR>　　&nbsp;{1&nbsp;0&nbsp;0&nbsp;1}<BR><BR>可见，Ak是一个&nbsp;2^k&nbsp;*&nbsp;2^k&nbsp;的矩阵。其中的规律自己去找{启示：把每一个矩阵分成四个&nbsp;2^(k-1)&nbsp;*&nbsp;2^(k-1)&nbsp;的小矩阵来看}。<BR><BR><BR>现在告诉你k的值，求出这个矩阵中有多少个0。<BR> 

 
 # 输入格式 
一个自然数k(k≤20000)。<BR> 

 
 # 输出格式 
一个数，即矩阵中k的个数。<BR> 
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
</td><td>6
</td></tr></table>
