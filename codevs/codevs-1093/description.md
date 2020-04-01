<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">鲁宾逊先生有一只宠物猴，名叫多多。这天，他们两个正沿着乡间小路散步，突然发现路边的告示牌上贴着一张小小的纸条：“欢迎免费品尝我种的花生！——熊字”。</p>
<p style=""> </p>
<p style="">鲁宾逊先生和多多都很开心，因为花生正是他们的最爱。在告示牌背后，路边真的有一块花生田，花生植株整齐地排列成矩形网格（如图<span style="font-family: DejaVu Serif Condensed,serif;">1</span>）。有经验的多多一眼就能看出，每棵花生植株下的花生有多少。为了训练多多的算术，鲁宾逊先生说：“你先找出花生最多的植株，去采摘它的花生；然后再找出剩下的植株里花生最多的，去采摘它的花生；依此类推，不过你一定要在我限定的时间内回到路边。”</p>
<p style=""> </p>
<p style=""> </p>
<p style="">我们假定多多在每个单位时间内，可以做下列四件事情中的一件：</p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">1) </span>从路边跳到最靠近路边（即第一行）的某棵花生植株；</p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">2) </span>从一棵植株跳到前后左右与之相邻的另一棵植株；</p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">3) </span>采摘一棵植株下的花生；</p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">4) </span>从最靠近路边（即第一行）的某棵花生植株跳回路边。</p>
<p style=""> </p>
<p style="">现在给定一块花生田的大小和花生的分布，请问在限定时间内，多多最多可以采到多少个花生？注意可能只有部分植株下面长有花生，假设这些植株下的花生个数各不相同。</p>
<p style=""> </p>
<p style="">例如在图<span style="font-family: DejaVu Serif Condensed,serif;">2</span>所示的花生田里，只有位于<span style="font-family: DejaVu Serif Condensed,serif;">(2, 5), (3, 7), (4, 2), (5, 4)</span>的植株下长有花生，个数分别为<span style="font-family: DejaVu Serif Condensed,serif;">13, 7, 15, 9</span>。沿着图示的路线，多多在<span style="font-family: DejaVu Serif Condensed,serif;">21</span>个单位时间内，最多可以采到<span style="font-family: DejaVu Serif Condensed,serif;">37</span>个花生。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">输入第一行包括三个整数，<span style="font-family: DejaVu Serif Condensed,serif;">M, N</span>和<span style="font-family: DejaVu Serif Condensed,serif;">K</span>，用空格隔开；表示花生田的大小为<span style="font-family: DejaVu Serif Condensed,serif;">M * N</span>（<span style="font-family: DejaVu Serif Condensed,serif;">1 &lt;= M, N &lt;= 20</span>），多多采花生的限定时间为<span style="font-family: DejaVu Serif Condensed,serif;">K</span>（<span style="font-family: DejaVu Serif Condensed,serif;">0 &lt;= K &lt;= 1000</span>）个单位时间。接下来的<span style="font-family: DejaVu Serif Condensed,serif;">M</span>行，每行包括<span style="font-family: DejaVu Serif Condensed,serif;">N</span>个非负整数，也用空格隔开；第<span style="font-family: DejaVu Serif Condensed,serif;">i + 1</span>行的第<span style="font-family: DejaVu Serif Condensed,serif;">j</span>个整数<span style="font-family: DejaVu Serif Condensed,serif;">Pij</span>（<span style="font-family: DejaVu Serif Condensed,serif;">0 &lt;= Pij &lt;= 500</span>）表示花生田里植株<span style="font-family: DejaVu Serif Condensed,serif;">(i, j)</span>下花生的数目，<span style="font-family: DejaVu Serif Condensed,serif;">0</span>表示该植株下没有花生。</p>
<p style=""> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-bottom: 0cm;">输出包括一行，这一行只包含一个整数，即在限定时间内，多多最多可以采到花生的个数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="">【样例输入<span style="font-family: DejaVu Serif Condensed,serif;">1</span>】</p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">6 7 21</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">0 0 0 0 0 0 0</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">0 0 0 0 13 0 0</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">0 0 0 0 0 0 7</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">0 15 0 0 0 0 0</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">0 0 0 9 0 0 0</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">0 0 0 0 0 0 0</span></p>
<p> </p>
<p style=""> </p>
<p style="">【样例输入<span style="font-family: DejaVu Serif Condensed,serif;">2</span>】</p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">6 7 20</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">0 0 0 0 0 0 0</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">0 0 0 0 13 0 0</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">0 0 0 0 0 0 7</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">0 15 0 0 0 0 0</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">0 0 0 9 0 0 0</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">0 0 0 0 0 0 0</span></p>
<p> </p>
<p style=""> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style="">【样例输出<span style="font-family: DejaVu Serif Condensed,serif;">1</span>】</p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">37</span></p>
<p style=""> </p>
<p style="">【样例输出<span style="font-family: DejaVu Serif Condensed,serif;">2</span>】</p>
<p style=""> </p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">28</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;"><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>