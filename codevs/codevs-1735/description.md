<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>已知一个n元高次方程：</p>
<p>k<sub>1</sub>x<sub>1</sub><sup>p<sub>1</sub></sup>+k<sub>2</sub>x2<sup>p2</sup>+……+k<sub>n</sub>x<sub>n</sub><sup>p<sub>n = 0</sub></sup></p>
<p>其中：x<sub>1</sub>, x<sub>2</sub>, …,x<sub>n</sub>是未知数，k<sub>1</sub>,k<sub>2</sub>,…,k<sub>n</sub>是系数，p<sub>1</sub>,p<sub>2</sub>,…p<sub>n</sub>是指数。且方程中的所有数均为整数。</p>
<p>假设未知数1≤ x<sub>i </sub>≤M, i=1,,,n，求这个方程的整数解的个数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>文件的第1行包含一个整数n。第2行包含一个整数M。第3行到第n+2行，每行包含两个整数，分别表示k<sub>i</sub>和p<sub>i</sub>。两个整数之间用一个空格隔开。第3行的数据对应i=1，第n+2行的数据对应i=n。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>文件仅一行，包含一个整数，表示方程的整数解的个数。</p>

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
<p>150</p>
<p>1  2</p>
<p>-1  2</p>
<p>1  2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>178</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p> 1≤n≤6；1≤M≤150；</p>
<p>|k<sub>1</sub>M<sup>p<sub>1</sub></sup>|+|k<sub>2</sub>M<sup>p2</sup>|+……+|k<sub>n</sub>M<sup>p<sub>n</sub></sup><sub> |</sub>&lt; 2<sup>31</sup></p>
<p>方程的整数解的个数小于2<sup>31</sup>。</p>
<p>★本题中，指数Pi(i=1,2,……,n)均为正整数。</p>
</div>
</div>