# 题目描述


<h3><span class="mw-headline">问题描述</span></h3>
<p>某岛国地形狭长，中部多山，东西海岸线上各有N/2个城市，有M条高速公路连接东西部的城市。为促进经济共同繁荣，该国政府决定建立一些“经济共荣 圈”。已知一个“共荣圈”由东西部各一个城市组成。每个城市要么不属于任何一个“共荣圈”，要么只属于一个“共荣圈”。“共荣圈”中的两个城市之间必须有 高速公路直接相连。该岛国政府经过分析，发现最多能够建立W个“共荣圈”。</p>
<p>A国认为“共荣圈”的建立不利于世界和平，决定出面干涉该岛国“共荣圈”的建立。通过各种手段，A国购买了一条高速公路，并禁止这条高速 公路的通行。被禁止通行这条高速公路的两端的两个城市之间如果没有其他道路相连接，将不能建立“共荣圈”。为尽可能得阻止“共荣圈”的建立，A国购买的这 条道路的选择很重要。A国想知道它有多少种购买选择，可以使该岛国无法建成W个“共荣圈”。</p>
<h3><span class="mw-headline">输入格式</span></h3>
<p>第一行，两个整数N,M，表示一共的城市个数和道路数。 接下来M行，每行两个整数A,B，表示西部城市A与东部城市B之间有一条高速公路直接连接，其中1&lt;=A&lt;=N/2，N/2+1&lt;=B&lt;=N。</p>
<h3><span class="mw-headline">输出格式</span></h3>
<p>一个整数，表示A国购买的这一条道路的可行选择数目。</p>
<h3><span class="mw-headline">样例输入</span></h3>
<pre>8 5
1 5
1 6
2 7
3 7
4 8
</pre>
<h3><span class="mw-headline">样例输出</span></h3>
<pre>1
</pre>
<h3><span class="mw-headline">样例说明</span></h3>
<p>该国最多能建立的“共荣圈”数量为3，购买并封锁(4,8)这条道路后，最多能建立的“共荣圈”数量减少为2。</p>
<h3><span class="mw-headline">数据规模</span></h3>
<ul>
    <li>对于40%的数据
    <ul>
        <li>2&lt;=N&lt;=200</li>
        <li>1&lt;=M&lt;=1000</li>
    </ul>
    </li>
    <li>对于100%的数据
    <ul>
        <li>2&lt;=N&lt;=100000</li>
        <li>1&lt;=M&lt;=100000</li>
    </ul>
    </li>
    <li>保证N为偶数</li>
</ul>
<p> </p>