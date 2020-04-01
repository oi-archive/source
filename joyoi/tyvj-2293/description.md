# 

 
 # 题目描述 
<p>
除法表达式有如下的形式:<br>X1/X2/X3.../Xk<br>其中Xi是正整数且Xi<=1000000000(1<=i<=k,K<=10000)<br>除法表达式应当按照从左到右的顺序求，例如表达式1/2/1/2的值为1/4.但可以在表达式中国入括号来改变计算顺序，例如(1/2)/(1/2)的值为1.现给出一个除法表达式E，求是告诉是否可以通过增加括号来使其为E',E'为整数</p> 

 
 # 输入格式 
<p>
先给出一个数字D，代表有D组数据.<br>每组数据先给出一个数字N，代表这组数据将有N个数。<br>接下来有N个数</p> 

 
 # 输出格式 
<p>
如果能使得表达式的值为一个整数，则输出YES.否则为NO</p> 
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
4
1
2
1
2
3
1
2
3</td><td>YES
NO</td></tr></table>
