# 

 
 # 题目背景 
APIO2010 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;你有一支由&nbsp;n&nbsp;名预备役士兵组成的部队，士兵从1到n编号，要将他们拆分成若干特别行动队调入战场。出于默契的考虑，同一支特别行动队中队员的编号应该连续，即为形如(i,&nbsp;i&nbsp;+&nbsp;1,&nbsp;…,&nbsp;i&nbsp;+&nbsp;k)的序列。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;编号为&nbsp;i&nbsp;的士兵的初始战斗力为&nbsp;xi&nbsp;，一支特别行动队的初始战斗力&nbsp;x为队内士兵初始战斗力之和，即&nbsp;x&nbsp;=&nbsp;xi&nbsp;+&nbsp;xi+1&nbsp;+&nbsp;…&nbsp;+&nbsp;xi+k。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;通过长期的观察，你总结出一支特别行动队的初始战斗力&nbsp;x将按如下经验公式修正为x'：x'&nbsp;=&nbsp;ax^2&nbsp;+&nbsp;bx&nbsp;+&nbsp;c，其中&nbsp;a,&nbsp;b,&nbsp;c是已知的系数（a&nbsp;&lt;&nbsp;0）。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;作为部队统帅，现在你要为这支部队进行编队，使得所有特别行动队修正后战斗力之和最大。试求出这个最大和。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;例如，&nbsp;你有4名士兵，&nbsp;x1&nbsp;=&nbsp;2,&nbsp;x2&nbsp;=&nbsp;2,&nbsp;x3&nbsp;=&nbsp;3,&nbsp;x4&nbsp;=&nbsp;4。经验公式中的参数为&nbsp;a&nbsp;=&nbsp;–1,&nbsp;b&nbsp;=&nbsp;10,&nbsp;c&nbsp;=&nbsp;–20。此时，最佳方案是将士兵组成&nbsp;3个特别行动队：第一队包含士兵1和士兵2，第二队包含士兵3，第三队包含士兵&nbsp;4。特别行动队的初始战斗力分别为4,&nbsp;3,&nbsp;4，修正后的战斗力分别为&nbsp;4,&nbsp;1,&nbsp;4。修正后的战斗力和为&nbsp;9，没有其它<BR>方案能使修正后的战斗力和更大。&nbsp; 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;输入由三行组成。第一行包含一个整数&nbsp;n，表示士兵的总数。第二行包含三个整数&nbsp;a,&nbsp;&nbsp;b,&nbsp;&nbsp;c，经验公式中各项的系数。第三行包含&nbsp;n&nbsp;个用空格分隔的整数&nbsp;x1,&nbsp;x2,&nbsp;…,&nbsp;xn，分别表示编号为1,&nbsp;2,&nbsp;…,&nbsp;n的士兵的初始战斗力。 

 
 # 输出格式 
输出一个整数，表示所有特别行动队修正后战斗力之和的最大值。<BR> 

 
 # 提示 
【数据范围】&nbsp;<BR>20%的数据中，n&nbsp;≤&nbsp;1000；&nbsp;<BR>50%的数据中，n&nbsp;≤&nbsp;10,000；&nbsp;<BR>100%的数据中，1&nbsp;&nbsp;≤&nbsp;&nbsp;n&nbsp;&nbsp;≤&nbsp;&nbsp;1,000,000，–5&nbsp;&nbsp;≤&nbsp;&nbsp;a&nbsp;&nbsp;≤&nbsp;&nbsp;–1，|b|&nbsp;&nbsp;≤&nbsp;&nbsp;10,000,000，|c|&nbsp;&nbsp;≤&nbsp;<BR>10,000,000，1&nbsp;≤&nbsp;xi&nbsp;≤&nbsp;100。&nbsp; 
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
-1 10 -20
2 2 3 4 </td><td>9 
</td></tr></table>
