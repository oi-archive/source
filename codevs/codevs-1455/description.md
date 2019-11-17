<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小明从A<sub>1</sub>到A<sub>n+1</sub>，他知道从A<sub>1</sub>到A<sub>2</sub>,从A<sub>2</sub>到A<sub>3,</sub>......,从A<sub>n</sub>到A<sub>n+1</sub>都有m条路,且从A<sub>1</sub>到A<sub>n+1</sub>都只有这些路。小明想知道,从A<sub>1</sub>地到A<sub>n+1</sub>地共有多少种方法,由于答案可能会很大,小明只要你输出总方案数mod k。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入共1行,三个正整数m,n,k</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出共1行,表示答案</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 2 100</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">假设从A<sub>1</sub>到A<sub>2</sub>的所有路为W<sub>1</sub>,W<sub>2</sub>,W<sub>3</sub>,从A<sub>2</sub>到A<sub>3</sub>的所有路为W<sub>4</sub>,W<sub>5</sub>,W<sub>6</sub></span></p>
<p><span style="">方案如下：</span><span style=""> </span></p>
<p><span style="">W<sub>1</sub>&gt;&gt;W<sub>4</sub><br>W<sub>2</sub>&gt;&gt;W<sub>4</sub><br>W<sub>3</sub>&gt;&gt;W<sub>4</sub><br>W<sub>1</sub>&gt;&gt;W<sub>5</sub><br>W<sub>2</sub>&gt;&gt;W<sub>5</sub><br>W<sub>3</sub>&gt;&gt;W<sub>5</sub><br>W<sub>1</sub>&gt;&gt;W<sub>6</sub><br>W<sub>2</sub>&gt;&gt;W<sub>6</sub><br>W<sub>3</sub>&gt;&gt;W<sub>6</sub><br>共9种方案 </span></p>
<p>对于100%的数据，m,k≤1,000,000,000，n≤10<sup>1,000,000</sup></p>
</div>
</div>