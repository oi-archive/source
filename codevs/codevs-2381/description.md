<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在完成了古越州圆盘密码的研究之后，考古学家小布来到了南美大陆的西部。相传很久以前在这片土地上生活着两个部落，一个部落崇拜闪电，另一个部落崇拜高山，他们分别用闪电和山峰的形状作为各自部落的图腾。</p>
<p>小布的团队在山洞里发现了一幅巨大的壁画，壁画上被标记出了<em>N</em>个点，经测量发现这<em>N</em>个点的水平位置和竖直位置是两两不同的。小布认为这幅壁画所包含的信息仅与这<em>N</em>个点的相对位置有关，因此不妨设坐标分别为(1, <em>y</em><sub>1</sub>) , (2, <em>y</em><sub>2</sub>), ..., (<em>n</em>, <em>y<sub>n</sub></em>)，其中<em>y</em><sub>1</sub>~<em>y<sub>n</sub></em>是1~<em>N</em>的一个排列。</p>
<p>小布的团队打算研究在这幅壁画中包含着多少个图腾，其中闪电图腾的定义图示如下（<strong>图腾的形式只与4个纵坐标值的相对大小排列顺序有关）</strong>：1&lt;=a&lt;b&lt;c&lt;d ya&lt;yc&lt;yb&lt;yd</p>
<p>崇拜高山的部落有两个氏族，因而山峰图腾有如下两种形式，左边为A类，右边为B类（<strong>同样，图腾的形式也都只与4个纵坐标值的大小排列顺序有关</strong>）：</p>
<p>1&lt;=a&lt;b&lt;c&lt;d ya&lt;yb&lt;yd&lt;yc</p>
<p>1&lt;=a&lt;b&lt;c&lt;d ya&lt;yd&lt;yc&lt;yb</p>
<p>    小布的团队希望知道，这<em>N</em>个点中两个部落图腾数目的差值。因此在本题中，你需要帮助小布的团队编写一个程序，计算闪电图腾数目减去山峰图腾数目的值，由于该值可能绝对值较大，本题中只需输出该值对16777216的余数（注意余数必为正值，例如-1对16777216的余数为16777215）。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含一个整数<em>N</em>，为点的数目。</p>
<p>接下来一行包含<em>N</em>个整数，分别为<em>y</em><sub>1</sub>, <em>y</em><sub>2</sub>, …, <em>y<sub>n</sub></em>。保证<em>y</em><sub>1</sub>, <em>y</em><sub>2</sub>, …, <em>y<sub>n</sub></em>是1~<em>N</em>的一个排列。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p align="left">仅包含一个数，表示闪电图腾数目与山峰图腾数目的差值对16777216的余数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p> 4</p>
<p>       1 2 4 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>  16777215</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于10%的数据，<em>N</em>  ≤ 600；</p>
<p>对于40%的数据，<em>N</em>  ≤ 5000；</p>
<p>对于100%的数据，<em>N</em> ≤ 200000。</p>
</div>
</div>