<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>琐妖塔会在一会儿后倒塌。大量妖魔涌出塔去，塔内的楼梯都挤满了人（哦，错了，是妖），（那他们怎么不飞下去--）要求是，景天一行一定要下塔，琐妖塔一共N层，但是他突然大发慈悲，觉得妖怪是无辜，所以他不想踩死这些妖魔，所以他的速度最多比妖怪速度大K（否则会踩死妖怪的），并且速度不能比妖怪们慢，否则会被踩死。琐妖塔一共有N层，并且每层怪物逃跑的速度都不相同，景天每下一层，可以选择将他的速度加快一个单位或者减慢一个单位或者保持原来的速度不变。并且他下每一层的速度之和除以(N-1)要尽量大。当然跑下楼时他一定要活着。<br>现在景天刚拿到镇妖剑，头有点热，不能思考了，请你编个程序帮帮他吧！<br>提示：1楼不需要再下了，N层楼只需要下N-1层。并且在第N层楼到N-1层时必须为初始速度。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，三个整数N，V（初始速度），K（最多比其他妖快的速度值）<br>第二行，N-1个整数，分别代表从第二层到第N层的妖怪的速度<br>其中2〈=N〈=100，0〈=K〈=100，1〈=V〈=100。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>若能下楼，输出速度之和除以（N-1），保留两位小数。<br />若不能，那就仰天大吼一声，输出&ldquo;REN JIU SHI BU NENG REN CI！&rdquo;（不含引号）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>Input1<br>3 3 2<br>2 2</p>
<p>Input2<br>3 3 0<br>2 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Output1<br>3.50<br>Output2<br>REN JIU SHI BU NENG REN CI！</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>RT</p>
</div>
</div>