<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    在古老的东方，人们都采用一种奇妙的方式记录日期：他们用一些特殊的符号来表示从1开始的连续整数，1表示最小而N表示最大。创世纪的第一天，日历就被赋予了生命，它自动的开始计数，就像排列在不断地增加。</p>
<p>    我们用1——N来表示日历的元素，第一天的日历是：1,2,3,……N-1,N</p>
<p>                                                  第二天，日历自动变为1,2,3,……N,N-1</p>
<p>    每次他都生成一个以前从未出现过的“最小”的排列——将它转为（N+1）进制后数的数值最小。</p>
<p>    有一天，一个预言者出现了——虽然没人让他出现——他预言道，当这个日历到达某个上帝安排的时刻（……），这个世界就会崩溃……他还预言，假如一个某一个日子的逆序到达一个指定数值M时，世界末日将来临。</p>
<p>    逆序是什么？日历中两个不同的符号，假如排在前面的那个比后面的那个大，就是一个逆序（不一定相邻）。人们期待一个贤者来预见那一天。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>只包含一行两个正整数，分别为N和M。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一行，为世界末日的日期，每个数字间用一个空格隔开。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 3 5 4 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于10%的数据有N&lt;=10。</p>
<p>对于40%的数据有N&lt;=1000。</p>
<p>对于100%的数据有N&lt;=50000。</p>
<p>所有数据均有解。</p>
<p>为避免出现错误，请在程序最后加上一个 writeln;</p>
</div>
</div>