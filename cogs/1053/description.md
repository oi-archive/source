# 题目描述


<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">问题描述</span> 
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">一元 n 次多项式可用如下的表达式表示： $ f(x) = a_nx^n + a_{n-1}x^{n-1} + \cdots + a_1x + a_0, \quad a_n \ne 0 $</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">其中，$a_ix^i$ 称为 i 次项，$a_i$ 称为 i 次项的系数。给出一个一元多项式各项的次数和系数，请按照如下规定的格式要求输出该多项式：</span> 
</p>
<ol>
<li>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">多项式中自变量为 x ，从左到右按照次数递减顺序给出多项式。</span> 
</li>
<li>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">多项式中只包含系数不为 0 的项。</span> 
</li>
<li>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">如果多项式 n 次项系数为正，则多项式开头不出现“+”号，如果多项式 n 次项系数为负，则多项式以“-”号开头。</span> 
</li>
<li>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于不是最高次的项，以“+”号或者“-”号连接此项与前一项，分别表示此项系数为正或者系数为负。紧跟一个正整数，表示此项系数的绝对值（如果一个高于 0 次的项，其系数的绝对值为 1，则无需输出 1）。如果 x 的指数大于 1，则接下来紧跟的指数部分的形式为“x^b”，其中 b 为 x 的指数；如果 x 的指数为 1，则接下来紧跟的指数部分形式为“x”；如果 x 的指数为 0，则仅需输出系数即可。</span> 
</li>
<li>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">多项式中，多项式的开头、结尾不含多余的空格。</span> 
</li>
</ol>
<p>
<br/>
</p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入</span> 
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入文件名为poly.in，共有2 行。</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第一行 1 个整数，n，表示一元多项式的次数。</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第二行有 n+1 个整数，其中第 i 个整数表示第 n-i+1 次项的系数，每两个整数之间用空</span> 
</p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出</span> 
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出poly.out共 1 行，按题目所述格式输出多项式。</span> 
</p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入输出样例1</span> 
<table>
<tbody>
<tr>
<th>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">poly.in</span> 
</th>
<th>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">poly.out</span> 
</th>
</tr>
<tr>
<td>
<pre>5
100 -1 1 -3 0 10</pre>
</td>
<td>
<pre>100x^5-x^4+x^3-3x^2+10</pre>
</td>
</tr>
</tbody>
</table>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入输出样例2</span> 
<table>
<tbody>
<tr>
<th>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">poly.in</span> 
</th>
<th>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">poly.out</span> 
</th>
</tr>
<tr>
<td>
<pre>3
-50 0 0 1</pre>
</td>
<td>
<pre>-50x^3+1</pre>
</td>
</tr>
</tbody>
</table>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">数据范围</span> 
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 ≤ n ≤ 100，多项式各次项系数的绝对值均不超过100。</span> 
</p>
