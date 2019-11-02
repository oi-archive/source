<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>为了得到书法大家的真传，小E同学下定决心去拜访住在魔法森林中的隐士。魔法森林可以被看成一个包含个N节点M条边的无向图，节点标号为1..N，边标号为1..M。初始时小E同学在号节点1，隐士则住在号节点N。小E需要通过这一片魔法森林，才能够拜访到隐士。<br>魔法森林中居住了一些妖怪。每当有人经过一条边的时候，这条边上的妖怪就会对其发起攻击。幸运的是，在号节点住着两种守护精灵：A型守护精灵与B型守护精灵。小E可以借助它们的力量，达到自己的目的。<br>只要小E带上足够多的守护精灵，妖怪们就不会发起攻击了。具体来说，无向图中的每一条边Ei包含两个权值Ai与Bi。若身上携带的A型守护精灵个数不少于Ai，且B型守护精灵个数不少于Bi，这条边上的妖怪就不会对通过这条边的人发起攻击。当且仅当通过这片魔法森林的过程中没有任意一条边的妖怪向小E发起攻击，他才能成功找到隐士。<br>由于携带守护精灵是一件非常麻烦的事，小E想要知道，要能够成功拜访到隐士，最少需要携带守护精灵的总个数。守护精灵的总个数为A型守护精灵的个数与B型守护精灵的个数之和。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行包含两个整数N,M，表示无向图共有N个节点，M条边。 接下来M行，第行包含4个正整数Xi,Yi,Ai,Bi，描述第i条无向边。其中Xi与Yi为该边两个端点的标号，Ai与Bi的含义如题所述。 注意数据中可能包含重边与自环。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一行一个整数：如果小E可以成功拜访到隐士，输出小E最少需要携带的守护精灵的总个数；如果无论如何小E都无法拜访到隐士，输出&ldquo;-1&rdquo;（不含引号）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 5<br>1 2 19 1<br>2 3 8 12<br>2 4 12 15<br>1 3 17 8<br>3 4 1 17</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>32</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>2&lt;=n&lt;=50000<br>0&lt;=m&lt;=100000<br>1&lt;=ai,bi&lt;=50000</p>
</div>
</div>