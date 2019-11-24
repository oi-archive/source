# 

 
 # 题目描述 
一元&nbsp;n&nbsp;次多项式可用如下的表达式表示：<BR>&nbsp;&nbsp;f(x)=an*x^n+an-1*x^n-1+...+a1*x+a0,an&lt;&gt;0<BR>其中，ai*a^x&nbsp;称为i次项，ai称为i次项的系数。给出一个一元多项式各项的次数和系<BR>数，请按照如下规定的格式要求输出该多项式：<BR>1.&nbsp;多项式中自变量为x，从左到右按照次数递减顺序给出多项式。<BR>2.&nbsp;多项式中只包含系数不为0&nbsp;的项。<BR>3.&nbsp;如果多项式n&nbsp;次项系数为正，则多项式开头不出现“+”号，如果多项式n&nbsp;次项系<BR>数为负，则多项式以“-”号开头。<BR>4.&nbsp;对于不是最高次的项，以“+”号或者“-”号连接此项与前一项，分别表示此项<BR>系数为正或者系数为负。紧跟一个正整数，表示此项系数的绝对值（如果一个高于0&nbsp;次的项，<BR>其系数的绝对值为1，则无需输出1）。如果x&nbsp;的指数大于1，则接下来紧跟的指数部分的形<BR>式为“x^b”，其中b&nbsp;为x&nbsp;的指数；如果x&nbsp;的指数为1，则接下来紧跟的指数部分形式为“x”；<BR>如果x&nbsp;的指数为0，则仅需输出系数即可。<BR>5.&nbsp;多项式中，多项式的开头、结尾不含多余的空格。 

 
 # 输入格式 
输入文件名为&nbsp;poly.in，共有2&nbsp;行<BR>第一行&nbsp;1&nbsp;个整数，n，表示一元多项式的次数。<BR>第二行有&nbsp;n+1&nbsp;个整数，其中第i&nbsp;个整数表示第n-i+1&nbsp;次项的系数，每两个整数之间用空<BR>格隔开。 

 
 # 输出格式 
输出文件&nbsp;poly.out&nbsp;共1&nbsp;行，按题目所述格式输出多项式。 

 
 # 提示 
NOIP2009普及组&nbsp;第一题 
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
<tr><td>输入样例1：
5
100 -1 1 -3 0 10
输入样例2：
3
-50 0 0 1
</td><td>输出样例1：
100x^5-x^4+x^3-3x^2+10
输出样例2：
-50x^3+1
</td></tr></table>
