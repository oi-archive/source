<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>汉诺塔问题（又称为河内塔问题），是一个大家熟知的问题。在A，B，C三根柱子上，有n个不同大小的圆盘（假设半径分别为1-n吧），一开始他们都叠在我A上（如图所示），你的目标是在最少的合法移动步数内将所有盘子从A塔移动到C塔。</p>
<p>游戏中的每一步规则如下：</p>
<p>1. 每一步只允许移动一个盘子（从一根柱子最上方到另一个柱子的最上方）</p>
<p>2. 移动的过程中，你必须保证大的盘子不能在小的盘子上方（小的可以放在大的上面，最大盘子下面不能有任何其他大小的盘子）</p>
<p> </p>
<p>如对于n=3的情况，一个合法的移动序列式：</p>
<p>1 from A to C</p>
<p>2 from A to B</p>
<p>1 from C to B</p>
<p>3 from A to C</p>
<p>1 from B to A</p>
<p>2 from B to C</p>
<p>1 from A to C</p>
<p> </p>
<p>给出一个数n，求出最少步数的移动序列</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一个整数n</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行一个整数k，代表是最少的移动步数。</p>
<p>接下来k行，每行一句话，N from X to Y，表示把N号盘从X柱移动到Y柱。X,Y属于{A,B,C}</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7</p>
<p>1 from A to C</p>
<p>2 from A to B</p>
<p>1 from C to B</p>
<p>3 from A to C</p>
<p>1 from B to A</p>
<p>2 from B to C</p>
<p>1 from A to C</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=10</p>
</div>
</div>