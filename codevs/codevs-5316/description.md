<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>蜗牛鲍勃和那个人（它叫阿萨德）一起往前走，到了森林里，它们被一只大灰狼追。由于它们身上没带武器，只能等着大灰狼体力消耗完成。现在已知道大灰狼和蜗牛鲍勃的距离和速度，还有双方的体力（大灰狼只追鲍勃，不追阿萨德），还有它们每分钟消耗的体力。需要知道鲍勃会不会被大灰狼追上。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>7个整数，代表双方距离、速度、体力、消耗量</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>如果会被追上，输出h，如果不会，输出b，如果双方体力都耗尽且距离不等于0，输出j。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>100 //距离</p><p>5 10 //速度</p><p>100 20 //体力</p><p>5 10 //消耗量</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>b</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">样例中，第一分钟，双方距离剩余95，鲍勃体力剩余95，大灰狼剩余10，第二分钟，距离剩余90，鲍勃体力90，大灰狼体力耗尽。所以输出b。</span></p><p><span style="">数据范围：均在整型范围内，大灰狼的速度比鲍勃的速度大（一定要大）</span></p><p><br></p>
</div>
</div>