<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Lostmonkey发明了一种超级反弹装置。为了在绵羊朋友面前显摆，他邀请小绵羊一起玩个游戏。游戏一开始，Lostmonkey在地上沿一条直线摆放 n个反弹装置，并按从前往后的方式将反弹装置依次编号为 0 到 n-1，对 0≤i≤n-1，为第 i 个反弹装置设定了初始弹力系数 ki，当绵羊落到第 i 个反弹装置上时，它将被往后弹出 ki 步，即落到第 i+ki 个反弹装置上，若不存在第i+ki个反弹装置，则绵羊被弹飞。绵羊想知道： 从第i个反弹装置开始， 它被弹出几次 （含被弹飞的那次）后会被弹飞。为使游戏更有趣，Lostmonkey 还可以修改某个反弹装置的弹力系数，但任何时候弹力系数均为正整数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行是一个整数n，表示地上摆放n个反弹装置，输入文件第二行是用空格隔开的n个正整数k0,k1,…,kn-1，分别表示n个反弹装置的初始弹力系数。输入文件第三行是一个正整数m，表示后面还有m行输入数据。接下来的m行，每行至少有用空格隔开的两个整数i和j，若i=1，则你要输出从第j个反弹装置开始，被弹出几次后会被弹飞；若i=2，则该行有用空格隔开的三个整数i，j和k，表示第j个反弹装置的弹力系数被修改为k。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包含的行数等于输入文件最后m行中i=1的行数。第h行输出一个整数，表示对输入中给出的第h个求弹出次数的问题，基于n个反弹装置当时的弹力系数，求出的弹出次数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 <br>1 2 1 1<br>3 <br>1 1 <br>2 1 1 <br>1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 <br> 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>输入的数据保证20%的数据满足n,m≤10000。100%的数据满足n≤200000,m≤100000</p>
</div>
</div>