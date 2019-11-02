# 

 
 # 题目描述 
阿达马矩阵如下：<BR><BR>A0={1}&nbsp;&nbsp;&nbsp;A1={1&nbsp;1}&nbsp;A2={1&nbsp;1&nbsp;1&nbsp;1}<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{1&nbsp;0}&nbsp;&nbsp;&nbsp;&nbsp;{1&nbsp;0&nbsp;1&nbsp;0}<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{1&nbsp;1&nbsp;0&nbsp;0}<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{1&nbsp;0&nbsp;0&nbsp;1}<BR><BR>可见，Ak是一个&nbsp;2^k&nbsp;*&nbsp;2^k&nbsp;的矩阵。其中的规律自己去找{启示：把每一个矩阵分成四个&nbsp;2^(k-1)&nbsp;*&nbsp;2^(k-1)&nbsp;的小矩阵来看}。<BR><BR><BR>现在告诉你k的值，求第x行第y列的数字。 

 
 # 输入格式 
输入有三行，每行一个数，分别是k(1≤k≤20000),x,y(1≤x,y≤2^20000)。<BR> 

 
 # 输出格式 
输出有一个数，数值为0或1，表示第x行第y列的数字。<BR> 
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
2
</td><td>0
</td></tr></table>
