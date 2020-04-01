<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p> 小徐从美国回来后，成为了USACO中国区的奶牛销售代理商，专门出售质优价廉的“FJ”牌奶牛。上题中，小徐终于凑够了钱，把她的小伙伴们接过来。</p>
<p>现在，她需要给她自己和其他3个伙伴安排房间。在同一直线上有N间房子（2&lt;=N&lt;=10^5），每间房子有一个唯一的位置（即X坐标）Xi。</p>
<p>（0&lt;=Xi&lt;=10^9）。为了方便交流，请你写一个程序，安排4间房子，使它们的最远距离最短。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：一个正整数N</p>
<p>第二行：N个正整数，Xi,空格隔开</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p align="left">最短的最远距离</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7</p>
<p>1 7 4 20 13 2 11</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3（选择1、2、4、7）</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>这个。就是二分。</p>
<p>设f（x）为最远距离为x时能否安排4间房子</p>
<p>这个函数当然有单调性，所以，果断二分搜索x。</p>
</div>
</div>