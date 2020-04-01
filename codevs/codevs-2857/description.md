<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">在算术表达式中，除了加、减、乘、除等运算外，往往还有括号。包括有大括号{}，中括号[]，小括号()，尖括号&lt;&gt;等。 对于每一对括号，必须先左边括号，然后右边括号；如果有多个括号，则每种类型的左括号和右括号的个数必须相等；对于多重括号的情形，按运算规则，从外到内的括号嵌套顺序为：大括号-&gt;中括号-&gt;小括号-&gt;尖括号。例如，{[()]}，{()},{{}}为一个合法的表达式，而([{}])，{([])},[{&lt;&gt;}]都是非法的。</span></p>
<!--EndFragment-->

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行为一个整数n（1≤n≤100），接下来有n行仅由上述四类括号组成的括号表达式。第i+1行表示第i个表达式。每个括号表达式的长度不超过255。</span></p>
<!--EndFragment-->

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt;"><span style="font-family: '宋体'; font-size: 10.5pt; font-weight: bold; mso-spacerun: 'yes';">：</span><span style="font-family: '宋体'; font-size: 10.5pt; mso-spacerun: 'yes';">输出共N行，对应于i行输入，合法则输出YES，非法则输出NO。</span></p>
<!--EndFragment-->

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">5</span></p>
<p style=""><span style="">{[(&lt;&gt;)]}</span></p>
<p style=""><span style="">[()]</span></p>
<p style=""><span style="">&lt;&gt;()[]{}</span></p>
<p style=""><span style="">[{}]</span></p>
<p style=""><span style="">{()}</span></p>
<!--EndFragment-->

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">YES</span></p>
<p style=""><span style="">YES</span></p>
<p style=""><span style="">YES</span></p>
<p style=""><span style="">NO</span></p>
<p style=""><span style="">YES</span></p>
<!--EndFragment-->

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>每个括号表达式的长度不超过255。</p>
</div>
</div>