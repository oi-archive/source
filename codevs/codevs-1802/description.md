<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Z 国坐落于遥远而又神奇的东方半岛上，在小 Z 的统治时代公路成为这里主 要的交通手段。Z 国共有 n 座城市，一些城市之间由双向的公路所连接。非常神 奇的是 Z 国的每个城市所处的经度都不相同，并且最多只和一个位于它东边的 城市直接通过公路相连。Z 国的首都是 Z 国政治经济文化旅游的中心，每天都有 成千上万的人从 Z 国的其他城市涌向首都。 为了使 Z 国的交通更加便利顺畅，小 Z 决定在 Z 国的公路系统中确定若干条 规划路线，将其中的公路全部改建为铁路。 我们定义每条规划路线为一个长度大于 1 的城市序列，每个城市在该序列中 最多出现一次，序列中相邻的城市之间由公路直接相连(待改建为铁路)。并且， 每个城市最多只能出现在一条规划路线中，也就是说，任意两条规划路线不能有 公共部分。 当然在一般情况下是不可能将所有的公路修建为铁路的，因此从有些城市出 发去往首都依然需要通过乘坐长途汽车，而长途汽车只往返于公路连接的相邻的 城市之间，因此从某个城市出发可能需要不断地换乘长途汽车和火车才能到达首 都。 我们定义一个城市的“不便利值”为从它出发到首都需要乘坐的长途汽车的 次数，而 Z 国的交通系统的“不便利值”为所有城市的不便利值的最大值，很明 显首都的“不便利值”为 0。小 Z 想知道如何确定规划路线修建铁路使得 Z 国的 交通系统的“不便利值”最小，以及有多少种不同的规划路线的选择方案使得“不 便利值”达到最小。当然方案总数可能非常大，小 Z 只关心这个天文数字 mod Q 后的值。 注意：规划路线 1-2-3 和规划路线 3-2-1 是等价的，即将一条规划路线翻转 依然认为是等价的。两个方案不同当且仅当其中一个方案中存在一条规划路线不 属于另一个方案</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件 design.in 第一行包含三个正整数 N、M、Q，其中 N 表示城市个数， M 表示公路总数，N 个城市从 1~N 编号，其中编号为 1 的是首都。Q 表示上文 提到的设计路线的方法总数的模数。接下来 M 行，每行两个不同的正数 ai、 bi (1≤ ai , bi ≤ N)表示有一条公路连接城市 ai和城市 bi。 输入数据保证一条公路只出现 一次。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件 design.out 应包含两行。第一行为一个整数，表示最小的&ldquo;不便利值&rdquo;。 第二行为一个整数，表示使&ldquo;不便利值&rdquo;达到最小时不同的设计路线的方 法总数 mod Q 的值。 如果某个城市无法到达首都，则输出两行-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 4 100</p>
<p>1 2</p>
<p>4 5</p>
<p>1 3</p>
<p>4 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>
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
<p>以下样例中是 10 种设计路线的方法：</p>
<p>(1) 4-5</p>
<p>(2) 1-4-5</p>
<p>(3) 4-5, 1-2</p>
<p>(4) 4-5, 1-3</p>
<p>(5) 4-5, 2-1-3</p>
<p>(6) 2-1-4-5</p>
<p>(7) 3-1-4-5</p>
<p>(8) 1-4</p>
<p>(9) 2-1-4</p>
<p>(10) 3-1-4</p>
<p>对于 20%的数据，满足 N,M ≤ 10。</p>
<p>对于 50%的数据，满足 N,M ≤ 200。</p>
<p>对于 60%的数据，满足 N,M ≤ 5000。</p>
<p>对于 100%的数据，满足 1 ≤ N,M ≤ 100000，1 ≤ Q ≤ 120000000。</p>
</div>
</div>