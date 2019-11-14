<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style=""><sup>放暑假了，llj和他的小伙伴们开心的围在一个小黑屋里看B站。</sup><br></span></p><p><span style=""><sup>经过几十天的熏陶，他们对其中丢雷姆这个绅士的运动产生了浓厚的兴趣，也想自己玩一玩。</sup></span></p><p><span style=""><sup>llj和他的小伙伴们站成了一个r行c列的矩阵，矩阵的所有初始元素均为0。游戏开始时，有同学会得到若干个雷姆，而有些同学不会。这时候矩阵上的元素会发生变化，变成该位置雷姆的个数。</sup></span></p><p><span style=""><sup>对于每一个不在边界的同学来说，在他上方的区域记为I,下</sup><sup>方的区域记为II,左方区域记为III，右方的区域记为IV，他会向四个区域最少的那一个区域丢一只雷姆，这只雷姆的位置与该同学在一条直线上（同行或同列），并且在该区域最少的一行或一列（若有多个，则选最远的那个）。当所有同学（不包括边界上的同学和没有雷姆的同学）都扔完雷姆后，记为执行了一次操作。但是同学们丢来丢去的，一旁观战的同学VK表示看不清楚，你能帮帮他吗？</sup></span></p><p><sup><span style=""><br></span></sup></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入共n+1行</span></p><p><span style="">第1行：三个整数r,c,k(分别表示矩阵行数和列数，及操作次数)</span></p><p><span style="">第2~n+1行：第i行表示矩阵i-1行的元素（即游戏开始时雷姆个数）</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: 20px;">共n行，代表操作后的矩阵</span><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">3 3 1<br></span></p><p><span style="">0 0 1</span></p><p><span style="">0 1 1</span></p><p><span style="">0 0 1</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">0 0 1<br></span></p><p><span style="">1 0 1</span></p><p><span style="">0 0 1</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">0&lt;r,c,k&lt;=10<br></span></p><p><span style="">矩阵中初始元素值不超过int范围</span></p>
</div>
</div>