<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>汤姆斯生活在一个等级为0的星球上。那里的环境极其恶劣。每天12小时的工作和成堆的垃圾让人忍无可忍。他向往着等级为N的星球上天堂般的生活。 有一些航班将人从低等级的星球送上高一级的星球，有时需要向驾驶员支付一定金额的费用，有时却又可以得到一定的金钱。 汤姆斯预先知道了从0等级星球去N等级星球的所有的航线和所需支付（或者可以得到）的金钱，他想找一条价格最低（甚至获得金钱最多）的航线。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行第一个正整数N（N≤100），接下来的数据可分为N个段落。 每段的第一行一个整数Ki（Ki≤100），表示等级为i的星球有Ki个。 接下来的Ki中第Tij行依次表示与等级为i，编号为j的星球相连的等级为i-1的星球的编号和此航线需要的费用（正数表示支出，负数表示收益，费用的绝对值不超过1000）。每行以0结束，每行的航线数≤100。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出所需（或所得）费用。正数表示支出，负数表示收益。</p>

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
<p>2  </p>
<p>1 15 0  </p>
<p>1 5 0  </p>
<p>3 1-52 10 0  </p>
<p>1 3 0  </p>
<p>2 40 0  </p>
<p>2</p>
<p>1 12 5 3 -5 0  </p>
<p>2-19 3-20 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>-1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据范围】 对于100%的数据N≤100 Ki≤100</p>
<p><img height="317" src="../../../media/image/1671.png" width="225"></p>
</div>
</div>