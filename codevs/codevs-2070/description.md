<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p> yh非常想念他的女朋友小y，于是他决定前往小y所在的那块大陆。</p>
<p>小y所在的大陆共有n个城市，m条双向路，每条路连接一个或两个城市。经过一条路ei需要耗费时间ti。此外，每条路均有一个特定标识，为’L’,’O’,’V’,’E’，中的某个字母。yh从1号城市出发，前往位于n号城市的小y所在处。</p>
<p>为了考验yh，小y规定，yh必须按照‘L’-&gt;’O’-&gt;’V’-&gt;’E’-&gt;’L’-&gt;’O’-&gt;’V’-&gt;’E’-&gt;.... 的顺序选择路，且所走的第一条路是’L’,最后一条路是’E’，每走完一个完整的’LOVE’算是通过一次考验</p>
<p>在不违背小y要求的前提下，yh想花费最少的时间到达小y的所在地，同在此时间内完成最多次考验。你能帮yh算出，他最少要花多久到达城市n，完成多少次考验呢？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为两个整数n，m表示有n个城市，m条双向路。</p>
<p>第2行到第m+1行，每行有3个整数x，y，t和一个字符char，城市x,y之间有路，通过这条路花费的时间为t，这条路的特殊标志为 char。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出1行，两个整数表示yh到达城市n花费的最少时间和该时间内通过的最多次考验数，如果不能到达则输出&rsquo;HOLY&nbsp;SHIT!&rsquo;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例输入1】</p>
<p>4 4</p>
<p>1 2 1 L</p>
<p>2 1 1 O</p>
<p>1 3 1 V</p>
<p>3 4 1 E</p>
<p>【样例输入2】</p>
<p>4 4</p>
<p>1 2 1 L</p>
<p>2 3 1 O</p>
<p>3 4 1 V</p>
<p>4 1 1 E</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【样例输出1】</p>
<p>4 1</p>
<p>【样例输出2】</p>
<p>HOLY SHIT!</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%数据，1≤n≤1314，0≤M≤13520</p>
</div>
</div>