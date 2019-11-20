<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 'Segoe UI', Helvetica, Arial, sans-serif;"><span style="">已知收银员要找给</span>小<span style=""> </span><span style="">Z<span style=""> </span></span><span style="">的金</span><span style=""> </span><span style="">额<span style=""> </span><span style="">N</span><span style="">、</span><span style="">钱柜里的硬币种</span>类<span style=""> </span><span style="">K<span style=""> </span></span><span style="">以及</span><span style=""> </span><span style="">K<span style=""> </span></span><span style="">种硬币的面额</span><span style="">，</span><span style="">计算有多少种不同的找零方法</span>？<span style=""> </span><span style="">这里的</span></span><span style=""> </span><span style="">“不同<span style="">”</span>是指所找零钱至少有一种硬币的数量不相同。假设现在只有</span><span style=""> </span><span style="">2<span style=""> </span></span><span style="">种硬币，一种面额</span>是<span style=""> </span><span style="">5<span style=""> </span></span><span style="">分</span><span style="">，</span><span style="">另一种面额</span>是<span style=""> </span><span style="">1<span style=""> </span></span><span style="">分</span><span style="">，</span><span style="">要找给</span>小<span style=""> </span><span style="">Z<span style=""> </span></span><span style="">的金额</span>是<span style=""> </span><span style="">8<span style=""> </span></span><span style="">分钱</span><span style="">，</span><span style="">可以给</span>小<span style=""> </span><span style="">Z<span style=""> </span></span>找<span style=""> </span><span style="">1<span style=""> </span></span><span style="">个五分硬币加</span>3<span style=""> </span></span><span style="font-family: 'Segoe UI', Helvetica, Arial, sans-serif;">个一分硬币，或者找</span><span style="font-family: 'Segoe UI', Helvetica, Arial, sans-serif;"> </span><span style="font-family: 'Segoe UI', Helvetica, Arial, sans-serif;">8<span style=""> </span></span><span style="font-family: 'Segoe UI', Helvetica, Arial, sans-serif;">个一分硬币。用</span><span style="font-family: 'Segoe UI', Helvetica, Arial, sans-serif;"> </span><span style="font-family: 'Segoe UI', Helvetica, Arial, sans-serif;">3<span style=""> </span></span><span style="font-family: 'Segoe UI', Helvetica, Arial, sans-serif;">个一分硬币加</span><span style="font-family: 'Segoe UI', Helvetica, Arial, sans-serif;"> </span><span style="font-family: 'Segoe UI', Helvetica, Arial, sans-serif;">1<span style=""> </span></span><span style="font-family: 'Segoe UI', Helvetica, Arial, sans-serif;">个五分硬币本质上与</span><span style="font-family: 'Segoe UI', Helvetica, Arial, sans-serif;"> </span><span style="font-family: 'Segoe UI', Helvetica, Arial, sans-serif;">1<span style=""> </span></span><span style="font-family: 'Segoe UI', Helvetica, Arial, sans-serif;">个五分硬币</span><span style="font-family: 'Segoe UI', Helvetica, Arial, sans-serif;">加<span style=""> </span><span style="">3<span style=""> </span></span><span style="">个一分硬币没有任何区别，因此只可以用两种不同的方式找出八分钱。</span></span><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入数据第一行有两个用空格隔开的整数 N 和 K，其中 1≤N≤300，表示超市收银员 要找给小 Z 的金额，1≤K≤8，表示收银员的钱柜里共有 K 种不同面额的硬币。第 2 到 K+1 行每行包含一个正整数 Ci，其中 1≤Ci≤100，表示一种硬币的面额，在输入数据中硬币 面额按降序排列（从最大到最小）。   不同种类的硬币面额各不相同，每种硬币都取之不尽 用之不竭。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出数据仅有一行包含一个整数，表示超市收银员可能的找零方案数。答案保证不会 超出长整型范围。需要注意的是如果没有面额为 1 分的硬币，有些金额将无法找零，此时 结果就输出 0。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">83 5
50
25
10
5
1</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">159</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例解释</p><p style="">输入详解：收银员要找给小 Z 金额 83 分，共有 5 种硬币，面额分别为：50,25,10, 5, 1</p><p style="">输出详解：以下是全部 159 种找零方案中的 前 15 种和最后一种:</p><p>0×50    0×25    0×10    0×5    83×1<br style="">0×50    0×25    0×10    1×5    78×1<br style="">0×50    0×25    0×10    2×5    73×1<br style="">0×50    0×25    0×10    3×5    68×1<br style="">0×50    0×25    0×10    4×5    63×1<br style="">0×50    0×25    0×10    5×5    58×1<br style="">0×50    0×25    0×10    6×5    53×1<br style="">0×50    0×25    0×10    7×5    48×1<br style="">0×50    0×25    0×10    8×5    43×1<br style="">0×50    0×25    0×10    9×5    38×1<br style="">0×50    0×25    0×10    10×5    33×1<br style="">0×50    0×25    0×10    11×5    28×1<br style="">0×50    0×25    0×10    12×5    23×1<br style="">0×50    0×25    0×10    13×5    18×1<br style="">0×50    0×25    0×10    14×5    13×1<br style="">……………………………………………<br style="">1×50    1×25    0×10    1×5    3×1<br style=""> </p><p style=""> 数据范围</p><p style="">10%的数据满足：N≤50，K≤3，Ci≤10</p><p style="font-family: 'Microsoft Yahei';">30%的数据满足：N≤100，K≤5，Ci≤20</p><p style="font-family: 'Microsoft Yahei';">60%的数据满足：N≤100，K≤7，Ci≤50</p><p style="font-family: 'Microsoft Yahei';">100%的数据满足：N≤300，K≤8，Ci≤100</p><p><br></p>
</div>
</div>