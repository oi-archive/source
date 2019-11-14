<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    由于经济紧张，可怜的Antinomyra只好在传说中的YL区商业文明街上摆起了地摊卖作业-------本。Antinomyra为了赚更多的钱，于是了解了在这条街上各个位置每个时段摆摊的期望收入，然后期待不断地更换摆摊位置来使得自己的收入最多。</p>
<p>    假设该条街的长度为N,那么，Antinomyra把该条街道划分成N个长度为１的区间，Antinomyra可以在其中的任意一个区间摆摊。对于每一个区间，其摆摊的收益是随时间周期性变化的，比如３天为周期，第１天在该处摆摊能赚100元，第２天在该处摆摊能赚200元，第３天在该处摆摊要亏50元（可能碰上CG队）,那么第4、7、10…天同第一天，第5、8、11….天同第二天，第6,9,12…天同第3天。且对于每一个区间，周期数可以不相同。</p>
<p>    而由于移动摊位很麻烦，所以Antinomyra最多一天移动一次，即在某一天摆摊结束之后移动到另一个摊位，且由于Antinomyra懒，所以每次最多移动一个位置，即每次只能移到该天摊位旁边的两个位置中的一个，当然，也可以不移动。而摆摊的第一天可以选择任何一个位置。</p>
<p>    现在Antinomyra想知道的是，他摆摊最多t天后，最多能赚多少钱。请额外注意，Antinomyra可以在任意时刻收摊回家，并且再也不来，但是至少摆摊一天。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>共N+1行。第一行输入两个数N(N10)，T(T10<sup>16</sup>),表示街长度为N，Antinomyra准备摆摊T天。接下来N行，第i+1行输入格式为，先输入一个数M(M10)，表示区间i的收入周期长度，该行接下来的M个数表示周期中的每一天在该位置摆摊能收入多少。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p align="left">输出Antinomyra最多能赚多少钱。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 3</p>
<p>1 3</p>
<p>2 2 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>该数据街道长度为2，在第1个位置每天都能赚3块钱，而第2个位置奇数天能赚2块钱，偶数天能赚4块钱，故Antinomyra第1天在1号位摆摊，第二天移到2号位，第三天又移回1号位置摆摊。</p>
</div>
</div>