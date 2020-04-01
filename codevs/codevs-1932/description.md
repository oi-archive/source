<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    蛋蛋非常热衷于挑战自我，今年暑假他准备沿川藏线骑着自行车从成都前往拉萨。川藏线的沿途有着非常美丽的风景，但在这一路上也有着很多的艰难险阻， 路况变化多端，而蛋蛋的体力十分有限，因此在每天的骑行前设定好目的地、同时合理分配好自己的体力是一件非常重要的事情。<br>    由于蛋蛋装备了一辆非常好的自行车，因此在骑行过程中可以认为他仅在克服风阻做功（不受自行车本身摩擦力以及自行车与地面的摩擦力影响）。某一天 他打算骑N段路，每一段内的路况可视为相同：对于第i段路，我们给出有关这段路况的3 个参数s<sub>i</sub>,k<sub>i</sub>,v<sub>i</sub>′,其中si表示这段路德长度，k表示这段路的风阻系数，v<sub>i</sub> ′表示这段路上的风速 (v<sub>i</sub>′&gt; 0 表示在这段路上他遇到了顺风，反之则意味着他将受逆风影响）。若某一时刻在这段路上骑车速度为v，则他受到的风阻 大小为F= k<sub>i</sub> (v − v<sub>i</sub> ′)<sup>2</sup> （这样若在长度为s 的路程内保持骑行速度v 不变，则 他消耗能量（做功）E = k<sub>i</sub> (v − v<sub>i</sub> ′)<sup>2</sup>s）。 设蛋蛋在这天开始时的体能值是E<sub>u</sub>，请帮助他设计一种行车方案，使他在有限的体力内用最短的时间到达目的地。请告诉他最短的时间T是多少。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第一行包含一个正整数N 和一个实数E<sub>u</sub>，分别表示路段的数量以及蛋蛋的体能值。<br>    接下来N行分别描述N个路段，每行有3 个实数s<sub>i</sub>,k<sub>i</sub>,v<sub>i</sub>′，分别表示第i段路的长度，风阻系数以及风速。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个实数T，表示蛋蛋到达目的地消耗的最短时间，要求保留到小数点后8位。<br /><br /></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 10000<br>10000 10 5<br>20000 15 8<br>50000 5 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>12531.34496464</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>一种可能的方案是：蛋蛋在三段路上都采用匀速骑行的方式，其速度依次为5.12939919, 8.03515481, 6.17837967。<br><br></p>
<p>【数据规模与约定】<br>对于10% 的数据，N = 1；<br>对于40% 的数据，N ≤ 2；<br>对于60% 的数据，N ≤ 100；<br>对于80% 的数据，N ≤ 1000；<br>对于所有数据，N≤ 10000，<br>0 ≤ E<sub>u</sub>≤ 10<sup>8</sup>，0 &lt; s<sub>i</sub>≤ 100000，0 &lt;k<sub>i</sub> ≤ 15，<br>−100 &lt; v<sub>i</sub>′ &lt; 100。数据保证最终的答案不会超过10<sup>5</sup>。<br>【提示】<br>必然存在一种最优的体力方案满足：蛋蛋在每段路上都采用匀速骑行的方式。</p>
<p> </p>
</div>
</div>