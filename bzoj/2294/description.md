
# Description

<div class="content"><p></p><dd>
<div>
<p>lqp18_31给了1tthinking一个很难的问题。这个问题由NWERC 2011某道题改编而来。下面是这个问题:</p>
<p>你在家乡的一个山坡上开车回家。你想尽可能快的回家，但是你的油箱里没有太多油了。回家的路是由一些上坡和下坡组成的。每个坡有不同的斜率和长度。如何可以在油量限制的前提下，最快回家呢？</p>
<p>我们把油量的消耗简化为一个很简单的模型。每小时油量消耗会随着速度 <em>v</em> 线性递增。但是，油量还和坡的斜率 <em>s</em> 有关。 举个例子，当走下坡路的时候，你可以以10千米每小时的速度行走而不花费任何的油。然后如果你走上坡路，你就需要耗油了。 更加详细的说, 你的汽车每小时耗油是 <em>c</em>。那么</p>
<p align="center"><em>c = max(0, αv + βs)</em>,</p>
其中 <em>α</em> 和 <em>β</em> 是两个常数， <em>v</em> 是你的速度 km/h, <em>s</em> 是斜率。 加速和减速不花费油，且可以瞬间完成。
<p>你的车有一个安全速度，你永远也不能超越这个速度vmax <strong>且在一个斜坡上，你必须以同样的速度行驶，不能变速</strong>.</p>
<p><img src="/source/bzoj/2294/img/aHR0cDovL21lZGlhLm9wZW5qdWRnZS5jbi9pbWFnZXMvZzMyMDRfMS5qcGc=.jpg" alt=""/></p>
</div>
</dd>
<dd>
<div></div>
</dd>
<p></p></div>

# Input

<div class="content"><p></p><dd>
<div>
<p>第一行一个正数：测试数据组数，最多100。接下来是每个测试数据：</p>
<ul>
    <li>一行是4个浮点数 <em>α</em> (0.1 ≤ <em>α</em> ≤ 100), <em>β</em> (0.1 ≤ <em>β</em> ≤ 100), <em>vmax</em> (0 &lt; <em>vmax</em> ≤ 200) and <em>f</em> (0 ≤ <em>f</em> ≤= 50): 常数<em>α</em>和<em>β</em>，最大速度和剩余油量。</li>
    <li>下一行一个整数 <em>r</em> (1 ≤ <em>r</em> ≤ 10,000): 斜坡数。</li>
    <li>接下来 <em>r</em> 行，每行两个浮点数，<em>x<sub>i</sub></em> and <em>y<sub>i</sub></em> (1 ≤ <em>x<sub>i</sub></em> ≤ 1000, -1000 ≤ <em>y<sub>i</sub></em> ≤ 1000，单位是米) ，表示由现在的位置平移向量(<em>x<sub>i</sub></em>,<em>y<sub>i</sub></em>)可以到达下一个斜坡的拐点（斜坡的斜率是不变的）。</li>
</ul>
</div>
</dd>
<p></p></div>

# Output

<div class="content"><p></p><dt>  每组测试数据：</dt>
<dt>一行一个浮点数：你可以回家的最快时间。保证如果可以回家，一定在24h内可以到家。如果不可能到家，输出&#34;IMPOSSIBLE&#34;。输出保留两位小数</dt>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
<br/>
1.000000 1.000000 1.000000 21.213204<br/>
10<br/>
1000 1000<br/>
1000 -1000<br/>
1000 1000<br/>
1000 -1000<br/>
1000 1000<br/>
1000 -1000<br/>
1000 1000<br/>
1000 -1000<br/>
1000 1000<br/>
1000 -1000<br/>
<br/>
10.0 100.0 150 1.0<br/>
2<br/>
100 0<br/>
100 100<br/>
<br/>
0.5 0.1 100 10<br/>
3<br/>
1000 0<br/>
100 10<br/>
100 -10</span></div>

# Sample Output

<div class="content"><span class="sampledata">14.14<br/>
IMPOSSIBLE<br/>
0.01</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

