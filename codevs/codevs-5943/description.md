<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Liyundu大神撩到了n个妹子，他想对这n个妹子进行分组。为了找出最完美的分组方案，他共进行了m次尝试。每次每组分ai个妹子时，最后一组会少bi个妹子。现在请你帮他计算一下他最少撩到了多少妹子，如果没有可行答案，则说明Liyundu大神撩到了假妹子，输出-1。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数t，表示共有t组测试数据。</p><p>接下来每组数据第一行一个整数m，表示m次尝试。</p><p>然后m行每行两个整数ai，bi，表示每组分的妹子个数和最后一组少的妹子个数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共t行，每行一个整数n，表示该组数据最少有n个妹子。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p><p>3</p><p>3 0</p><p>5 0</p><p>7 2</p><p>2</p><p>4 2</p><p>2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>75</p><p>-1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于每组数据，T&lt;=100,000，n&lt;=4，ai&lt;=10000。</p><p>不保证ai互质，保证答案不超过64位整数范围。</p><p>有节操的人不要 __int128_t。</p>
</div>
</div>