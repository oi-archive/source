<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>PB同学是一个很懒的同学，他想写一个计算器程序程序用于“糊弄”作业。在AC了“1015 计算器的改良之后”他感觉非常不爽（没看过这道题的同学建议先去看一下）。那道题中的计算器的能力实在是太弱了，只能处理加减法，而不能处理乘除法，而且输入的数据也只能是整数。因此他想写一个新的计算器程序，其中允许出现加、减、乘、除四种运算以及小括号。不同的是，你只需要计算表达式的值，而不需要解方程。结果要求四舍五入保留小数点后三位。不过要注意乘除法的优先级是高于加减法的，表达式允许小括号的嵌套。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一个表达式（不含空格），其中可以包含整数、小数、'+'、'-'、'*'、'/'、'('和')'。（所有运算符皆为半角字符）</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>表达式的结果，四舍五入保留三位小数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5+(3+6/0.3)*0.3</p><p>注：允许出现小数但是不允许出现科学计数法。减号亦可以作为负号。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>11.900</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>表达式的长度&lt;=100个字符。</p>
</div>
</div>