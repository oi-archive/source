<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>学校需要将<span style="font-family: 'Times New Roman';">n</span><span style="">台计算机连接起来，不同的</span><span style="font-family: 'Times New Roman';">2</span><span style="">台计算机之间的连接费用可能是不同的。为了节省费用，我们考虑采用间接数据传输结束，就是一台计算机可以间接地通过其他计算机实现和另外一台计算机连接。</span></p>
<p>为了使得任意两台计算机之间都是连通的（不管是直接还是间接的），需要在若干台计算机之间用网线直接连接，现在想使得总的连接费用最省，让你编程计算这个最小的费用。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入<span style="">第一行为两个整数</span><span style="font-family: 'Times New Roman';">n,m</span><span style="">（</span><span style="font-family: 'Times New Roman';">2&lt;=n&lt;=100000，2<span>&lt;=m</span>&lt;=100000</span><span style="">），表示计算机总数，</span><span><span style="font-family: 'Times New Roman';">和可以互相建立连接的连接个数。</span></span><span style="font-family: 'Times New Roman';">接下来m行，每行三个整数a,b,c 表示在机器a和机器b之间建立连接的话费是c。(题目保证一定存在可行的连通方案, 数据中可能存在权值不一样的重边，但是保证没有自环)</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出<span style="font-family: 宋体;">只有一行一个整数，表示最省的总连接费用。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3</p>
<p>1 2 1</p>
<p>1 3 2</p>
<p>2 3 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>最终答案需要用long long类型来保存</p>
</div>
</div>