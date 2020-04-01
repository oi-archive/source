# 

 
 # 题目描述 
<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">给定一个多项式的各次项系数(从八次到零次)，让你组成一条多项式，此多项式没有多余的符号。例如，给定系数为0，0，0，1，22，-333，0，1和-1，你应该输出x^5&nbsp;+&nbsp;22x^4&nbsp;-&nbsp;333x^3&nbsp;+&nbsp;x&nbsp;-&nbsp;1<br />
组成多项式有如下规则：<br />
1.&nbsp;各项应按降序排列，即八次项排在前，零次项排在后。</p>

<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">2.&nbsp;指数前要加符号&quot;^&quot;。</p>

<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">3.&nbsp;常数项只以常数形式出现。</p>

<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">4.&nbsp;只有系数非零的项会出现在多项式中；除非所有项的系数都为零，则常数项不能省。</p>

<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">5.&nbsp;多项式只在二元运算符&quot;＋&quot;和&quot;－&quot;的前后各有一个空格，其余地方没有空格。</p>

<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">6.&nbsp;如果首项系数为正，则前面不用加符号；而如果首项系数为负，则前面应有负号，例如-7x^2&nbsp;+&nbsp;30x&nbsp;+&nbsp;66。</p>

<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">7.&nbsp;负数项应以&quot;减去非负数项&quot;的形式出现（除非此负数项是首项，则按上面的规则输出），也就是说，不能输出x^2&nbsp;+&nbsp;-3x,而要输出x^2&nbsp;-&nbsp;3x。</p>

<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">8.&nbsp;常数1和－1只能以常数项形式出现；也就是说，不能输出-1x^3&nbsp;+&nbsp;1x^2&nbsp;+&nbsp;3x^1&nbsp;-&nbsp;1,而要输出-x^3&nbsp;+&nbsp;x^2&nbsp;+&nbsp;3x&nbsp;-&nbsp;1。</p> 

 
 # 输入格式 
<p><span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">只有一行，有9个绝对值小于1000的整数，整数间有一个或多个空格。</span></p> 

 
 # 输出格式 
<p><span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">只有一行，表示你输出的多项式，行首行末无多余空格。</span></p> 

 
 # 提示 
<h2>版权</h2>

<p><span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">GDOI2001</span><br style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;" />
<span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">本题目由VijosCP&nbsp;V0.1.1&nbsp;测试版&nbsp;生成&nbsp;请勿删除此行（Vijos&nbsp;1258）。本账户不拥有版权。如无意中侵权，请告知！O(&cap;_&cap;)O谢谢</span></p> 
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
<tr><td>0  0  0  1  22  -333  0  1  -1</td><td>x^5 + 22x^4 - 333x^3 + x - 1</td></tr></table>
