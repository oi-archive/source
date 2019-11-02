<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    小L最近迷上了一款游戏，每一局他会出生在一个有n个采矿点(n - 1)条边构成的矿场中。每一局总共会产出m个金币，第i个金币会在第ti秒在采矿点pi出现，他必须要在第ti秒的时候在这个采矿点才能够得到这枚金币(当然，他也可以在这个采矿点等到这个金币出现)，否则到下一秒这枚金币就会消失(可能因为采矿点新挖出来的东西把它覆盖了，小L就找不到了)。直到最后一枚金币消失后，游戏结束。游戏开始的时刻为0，他经过一条边的时间为1。他想知道当前的这一局，他最多可以获得多少金币。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第一行有两个正整数n, m。</p><p>    接下来有(n - 1)行，每行两个正整数</p><p>u<sub>i</sub>和v<sub>i</sub>，表示第i条边联通第u<sub>i</sub>个采矿点和v<sub>i</sub>个采矿点。接下来有m行，每行两个正整数p<sub>i</sub>和t<sub>i</sub>，分别表示第i枚金币出现的位置和时间，按时间升序排序。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;&nbsp;&nbsp;&nbsp;仅一行，一个整数，表示小L在这局游戏中最大能够获得的金币数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3</p><p>1 2</p><p>1 3</p><p>1 0</p><p>2 1</p><p>3 2</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>[Hint]</strong></p><p>其中一种方法为在时刻0在1号采矿点得到1枚金币，然后去2号采矿点，在时刻1得到1枚金币，共两枚。</p><p><strong>[Limit]</strong></p><p>30%的数据满足1≤n,m≤10</p><p>70%的数据满足1≤n,m≤100,0≤t≤4000</p><p>100%的数据满足1≤n≤1000,1≤m≤200000,0≤t≤10000000,且所有数据随机生成,不存在任何两个金币出现在同一时刻</p><p><br></p>
</div>
</div>