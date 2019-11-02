<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>由于 szp 太 6 了，gzm 和 hcx 决定一起膜拜 szp</p><p>gzm 和 hcx 使用分身术分出了 N*N 个分身填满了 N*N 的矩阵，每个分身有一个膜拜 方向，这个方向可以为东南西北，分别可以膜拜到所有位于分身右侧/下侧/左侧/上侧的所有位置。</p><p>用x代表矩阵从上往下数第x行，y代表从左往右数第y列。定义a点位于b点左侧等同于a点的y坐标小于b点的y坐标，其余三项定义类似。</p><p>szp 由于被这么多人膜拜感到不好意思，所以他会尝试离开这个矩。szp 的移动方式很 特别，他可以闪现到任意一个坐标（x，y）（然而矩阵太大了他并不能跑掉，所以 1&lt;=x,y&lt;=n）</p><p>用 <strong>M x y</strong> 表示 szp 的一次闪现操作，意为 szp 闪现到了坐标为(x,y)处，同时，gzm 和 hcx 可能改变矩阵中任意一个分身的朝向，这个操作用 <strong>C x y d</strong> 表示，意为位于 x,y 位置的分身改变他的方向为 d (d 是一个整数，d=1,2,3,4 分别表示东南西北)</p><p>gzm 和 hcx 很好奇每次 szp 移动后会有多少个分身膜拜 szp，然而由于他们太弱了需要 你来解答这个问题。</p><p><br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行:  包含两个整数 N，Q</p><p>接下来 N 行  每行有 N 个整数，表示矩阵中分身的初始状态</p><p>接下来 Q 行，每行为一个操作 (M x,y  或  C x y d) 意义与题目描述中相同</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每一个询问操作 每行输出一个整数表示答案<br/></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3</p><p>1 1 1</p><p>1 1 1</p><p>1 1 1</p><p>M 2 1</p><p>C 2 2 3</p><p>M 1 1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0</p><p>1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>样例解释</strong></p><p><br></p><p>初始状态下所有分身全部朝向<br></p><p>第一次讯问： szp 出现在 2 行 1 列位置，没有分身可以膜拜到他 </p><p>第一次修改：位于 2 行 2 列的分身更改朝向到西</p><p>第二次询问： szp 出现在 1 行 1 列的位置，这时只有位于 2 行 2 列朝向为西的分身 可以膜拜到 szp</p><p><strong><br></strong></p><p><strong>数据范围</strong><br></p><p><br></p><p>对于 30%的数据 N,Q&lt;=100</p><p>对于另 10%的数据  输入中没有 C 操作</p><p>对与 100%的数据 1&lt;=N&lt;=4000，1&lt;=Q&lt;=50000</p><p><br></p><p><strong>提示</strong></p><p><br></p><p>与 szp 位置重合的分身将不会膜拜 szp</p><p><br></p><p><br></p><p><br></p>
</div>
</div>