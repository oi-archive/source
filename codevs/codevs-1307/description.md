<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>众所周知，一只欧少(一种草食类动物)的力量是很弱的。为了抵抗敌人，有1～n这n只欧少组成了一棵树的形式。作为FFF团的一员，英勇的你决定率领部队与它们决一死战。你的部队每秒只能击败一只欧少，并且若你要击败某只欧少，必须先击败其树上的所有祖先。欧少当然是会反击的——每只欧少有一个攻击力，如果这1s它还活着，那么它就会对你们发起一次攻击(T_T)，打倒ai名队员。现在你想知道，你至少需要带多少名队员参加这项危险的任务。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为两个值 n,r<br>代表有 n 个欧少,r 为总指挥欧少的编号(树的根)<br>第二行有 n 个数,第 i 个数代表第 i只欧少的攻击力。<br>第 3~n+1 行<br>每行 2 个数 x,y<br>表示 y 号欧少的父亲是 x 号欧少</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个数,表示最少要带的部队人口,</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 1<br>1 2 1 2 4<br>1 2<br>1 3<br>2 4<br>3 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>33</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>摧毁 1,3,5,2,<br>1 × 1 +1 × 2+4 × 3+2 × 4+2 × 5= 33<br>对于%60 的数据 n&lt;=2000<br>对于%100 的数据 n&lt;=20000<br><br></p>
</div>
</div>