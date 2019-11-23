<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>对于 加、减、乘、除这种四则运算的表达式，我们使用的是先乘除、后加减的从左到右的顺序进行运算，如果要指定特定的顺序，就要增加括号进行表达，比如 (A+B)*C , A+(F-(A+Y))*(B-C)/D 。</p>
<p>除了上述表达方式之外，在1929年，波兰逻辑学家Lukasiewicz提出一种不用括号的逻辑符号体系，后来人们称之为波兰表示法，波兰表达式的特点是运算符位于运算对象的后面，因此称为后缀表示。在对波兰表达式进行运算，严格按照自左至右的顺序进行。下面给出一些表达式及其相应的波兰表达式。</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="284">
<p>普通表达式</p>
</td>
<td valign="top" width="284">
<p>波兰表达式</p>
</td>
</tr>
<tr>
<td valign="top" width="284">
<p>A-B</p>
</td>
<td valign="top" width="284">
<p>AB-</p>
</td>
</tr>
<tr>
<td valign="top" width="284">
<p>(A-B)*C+D</p>
</td>
<td valign="top" width="284">
<p>AB-C*D+</p>
</td>
</tr>
<tr>
<td valign="top" width="284">
<p>(B+C)/(A-D)</p>
</td>
<td valign="top" width="284">
<p>BC+AD-/</p>
</td>
</tr>
</tbody>
</table>
<p> </p>
<p>【普通表达式】</p>
<p>普通表达式 (EXP) 定义如下：</p>
<p>1、  大写字母 A,B,C,D …Z  是 EXP</p>
<p>2、  EXP+EXP , EXP–EXP , EXP*EXP , EXP/EXP 是EXP</p>
<p>3、  (EXP) 是EXP</p>
<p> </p>
<p>普通表达式使用习惯性的括号优先。先乘除后加减的顺序进行运算。</p>
<p> </p>
<p>【普通表达式转换成波兰表达式】</p>
<p>普通表达式可以按照运算顺序构建二叉树然后转换成波兰表达式。</p>
<p> </p>
<p>例如：</p>
<p>(A-B)*C+D*E</p>
<p> </p>
<p>对应的运算二叉树如下：</p>
<p> </p>
<p><img height="178" src="../../../media/image/problem/2574.png" width="240"></p>
<p>然后对该二叉树进行后序遍历，就可以得到波兰表达式：  AB-C*DE*+</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入包含一行，50个字符以内，代表普通表达式</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出包含一行，代表转换后的波兰表达式</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>(A-B)*C+D*E</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>AB-C*DE*+</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>输入包含一行，50个字符以内</span></p>
</div>
</div>