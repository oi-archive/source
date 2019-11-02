<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给出一个布尔表达式，计算其值。</p><p>我们用T表示[真]，F表示[假]，&amp;表示运算 逻辑[与]，|表示运算 逻辑[或]</p><p>如果你不是很清楚 逻辑[与] 和 逻辑[或] 的含义，下面给出了运算表：</p><p>A    B    A&amp;B    A|B</p><p>T    T       T        T</p><p>T    F       F        T</p><p>F    T       F        T</p><p>F    F       F        F</p><p>运算符优先级：</p><p>允许使用圆括号调整优先级，优先计算圆括号中的表达式，在同层，&amp;运算符的优先级要高于|的优先级。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数n，表示数据组数。</p><p>接下来每组数据占一行，为一个布尔表达式。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出共n行，分别表示每组数据的计算结果，每行输出应为T或F。（有回车）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p><p>T&amp;F</p><p>F&amp;(F&amp;T|F)</p><p>F&amp;F|T</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>F</p><p>F</p><p>T</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于前30%的数据，n=1。</p><p>对于100%的数据，n&lt;=1000,任意表达式长度l&lt;=1000,输入数据保证合法。</p>
</div>
</div>