<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>恰逢 H 国国庆，国王邀请 n 位大臣来玩一个有奖游戏。首先，他让每个大臣在左、右手上面分别写下一个整数，国王自己也在左、右手上各写一个整数。然后，让这 n位大臣排成一排，国王站在队伍的最前面。排好队后，所有的大臣都会获得国王奖赏的若干金币，每位大臣获得的金币数分别是：排在该大臣前面的所有人的左手上的数的乘积除以他自己右手上的数，然后向下取整得到的结果。</p>
<p>国王不希望某一个大臣获得特别多的奖赏，所以他想请你帮他重新安排一下队伍的顺序，使得获得奖赏最多的大臣，所获奖赏尽可能的少。注意，国王的位置始终在队伍的最前面。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含一个整数 n，表示大臣的人数。</p>
<p>第二行包含两个整数a和b，之间用一个空格隔开，分别表示国王左手和右手上的整数。</p>
<p>接下来n行，每行包含两个整数a和b，之间用一个空格隔开，分别表示每个大臣左手和右手上的整数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出只有一行，包含一个整数，表示重新排列后的队伍中获奖赏最多的大臣所获得的</p>
<p class="p0">金币数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>1 1</p>
<p>2 3</p>
<p>7 4</p>
<p>4 6</p>

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
<p>【输入输出样例说明】</p>
<p>按 1、2、3号大臣这样排列队伍，获得奖赏最多的大臣所获得金币数为 2；</p>
<p>按 1、3、2这样排列队伍，获得奖赏最多的大臣所获得金币数为2；</p>
<p>按 2、1、3这样排列队伍，获得奖赏最多的大臣所获得金币数为 2；</p>
<p>按 2、3、1这样排列队伍，获得奖赏最多的大臣所获得金币数为 9；</p>
<p>按 3、1、2这样排列队伍，获得奖赏最多的大臣所获得金币数为 2；</p>
<p>按 3、2、1这样排列队伍，获得奖赏最多的大臣所获得金币数为 9。</p>
<p>因此，奖赏最多的大臣最少获得 2 个金币，答案输出 2。</p>
<p> </p>
<p>【数据范围】</p>
<p>对于20%的数据，有1≤ n≤ 10，0 &lt; a、b &lt; 8；</p>
<p>对于40%的数据，有1≤ n≤20，0 &lt; a、b &lt; 8；</p>
<p>对于60%的数据，有1≤ n≤100；</p>
<p>对于60%的数据，保证答案不超过 10^9；</p>
<p>对于100%的数据，有 1 ≤ n ≤1,000，0 &lt; a、b &lt; 10000。</p>
</div>
</div>