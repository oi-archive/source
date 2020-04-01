<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>长期的宅男生活中，</span><span>JYY</span><span>又挖掘出了一款</span><span>RPG</span><span>游戏。在这个游戏中</span><span>JYY</span><span>会扮演一个英勇的骑士，用他手中的长剑去杀死入侵村庄的怪兽。 </span></p>
<p><span>在这个游戏中，</span><span>JYY</span><span>一共有两种攻击方式，一种是普通攻击，一种是法术攻击。两种攻击方式都会消耗</span><span>JYY</span><span>一些体力。 </span></p>
<p><span>采用普通攻击进攻怪兽并不能把怪兽彻底杀死，怪兽的尸体可以变出其他一些新的怪兽，注意一个怪兽可能经过若干次普通攻击后变回一个或更多同样的怪兽；而采用法术攻击则可以彻底将一个怪兽杀死。当然了，一般来说，相比普通攻击，法术攻击会消耗更多的体力值（但由于游戏系统</span><span>bug</span><span>，并不保证这一点）。 </span></p>
<p><span>游戏世界中一共有</span><span>N</span><span>种不同的怪兽，分别由</span><span>1</span><span>到</span><span>N</span><span>编号，现在</span><span>1</span><span>号怪兽入侵村庄了，</span><span>JYY</span><span>想知道，最少花费多少体力值才能将所有村庄中的怪兽全部杀死呢？</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含一个整数N。 </p>
<p>接下来N行，每行描述一个怪兽的信息； </p>
<p>其中第i行包含若干个整数，前三个整数为Si ，Ki 和Ri ，表示对于i号怪兽，普通攻击需要消耗Si 的体力，法术攻击需要消耗Ki 的体力，同时i号怪兽死亡后会产生 Ri个新的怪兽。接下来 Ri个1到N之间的整数，表示一个新出现的怪兽编号。同一编号的怪兽可以出现多个。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0"><span>输出一行一个整数，表示最少需要的体力值。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 </p>
<p>4 27 3 2 3 2 </p>
<p>3 5 1 2 </p>
<p>1 13 2 4 2 </p>
<p>5 6 1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>26</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p>N≤200,000；Ki，Si≤5*10^14</p>
</div>
</div>
</div>