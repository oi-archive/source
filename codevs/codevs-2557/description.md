<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>张程易是一名神奇的魔法少女，在oier之中有着极高的地位。<br>他的老师老王对他的程序水平赞叹不已，于是下决心培养这名小子。<br>老王的训练方式很奇怪，他会一口气让张程易做很多道题，<br>要求他在规定的时间完成。<br>而老王为了让自己的威信提高，自己也会把这些题都做一遍。<br>张程易和老王都有一个水平值，他们水平值的比值和做这些题<br>所用时间的比值成反比。比如如果张程易的水平值是1，老王的水平值是2<br>那么张程易做同一道题的时间就是老王的2倍。 <br> <br>每个题目有他所属的知识点，这我们都知道，<br>比如递归，动归，最短路，网络流……<br>在这里我们不考虑这些事情，我们只知道他们分别是知识点1，知识点2……<br>每一个知识点有他对应的难度，比如动态规划经常难于模拟……<br>而每一个同一知识点下的题目，对于张程易来讲，都是一样难的。<br>而做出每一道题，老王都有其独特的奖励值。<br>而奖励值和题目的知识点没有必然联系。 <br>现在张程易同学请你帮忙，计算<br>在老王规定的时间内，<br>张程易所能得到最大奖励值是多少 。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件包括以下内容：<br>第一行：<br>张程易的水平值和老王的水平值。<br>数据保证张程易的水平值小于老王的水平值（哪怕它不现实），<br>且老王的水平值是张程易的水平值的整数倍。<br>第二行：<br>题目的总数m和知识点的总数n。<br>第三行：<br>n个整数。第i个整数表示 老王在做第i个知识点的题目所需的时间。<br>接下来有m行数每一行包括两个整数p，q。<br>p表示该题目所属的知识点，q表示该题目对应的奖励值。<br>最后一行是规定的时间。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件只有一行，表示能到得到的最大奖励值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 2</p>
<p>6 4</p>
<p>1 2 3 4</p>
<p>1 5</p>
<p>2 6</p>
<p>3 3</p>
<p>4 8</p>
<p>3 3</p>
<p>4 5</p>
<p>20</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>22</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的数据，题目总数&lt;=5000,规定时间&lt;=5000</p>
</div>
</div>