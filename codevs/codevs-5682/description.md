<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">（对此我无可奉告）</span></p><p><span style="">生活在东京的男高中生立花泷做了个奇怪的梦，他在一个从未去过的深山小镇中，变成了女高中生三叶。他发现一颗彗星将以5cm/s的速度坠毁，将砸在三叶所在的村子附近，他想拯救她，可智商堪忧，于是找了帅气的猴王，请帅气的猴王帮助他。假若该村子的布局为严格平行的一百二十九条东西走向的街道和一百二十九条南北走向的街道所形成的网格状，各条街道的编号依次为0——128.</span></p><p><span style="">这些街道相交形成路口，第x号街道与第y号街道相交所形成的路口的坐标为(x,y)。在某些路口存在居民的小屋。</span></p><p><span style="">已知彗星砸下来会摧毁以它的降落点为中心，边长为2*d的正方形以内的所有房屋。猴王是一个邪恶的人，他想坑害立花泷，于是想让彗星摧毁更多的小屋，所以他操纵了彗星想让他砸了下来，可这一切被立花泷识破了，他想用暴力膜——拟的方法算出彗星的轨迹来阻止这一切，现在请你算出彗星在哪里降落会摧毁最多的房屋来推测猴王的阴谋。立花泷会以记者的身份江这件事情放在报纸上报导</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行包含一个整数d，表示彗星的摧毁范围。</span></p><p style=""><span style="">第二行包含一个整数n，表示有小屋的路口数目。</span></p><p style=""><span style="">接下来的n行，每行给出三个整数x，y，k，中间用一个空格隔开，分别代表路口的坐标以及该路口屋子的数量。同一坐标只会给出一次。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 微软雅黑, &#39;Microsoft YaHei&#39;; ">输出一行，包括两个整数，用一个空格隔开，分别表示能摧毁最多小屋的坠毁地点方案数，以及能摧毁的最多小屋的数量。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">1</span></p><p><span style="">2</span></p><p><span style="">4 4 10</span></p><p><span style="">6 6 20</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">1 30</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">对于100％数据，1&lt;=d&lt;=20，1&lt;=n&lt;=20，0=x&lt;=128，0&lt;=y&lt;=128，0&lt;=k&lt;=1,000,000。</span></p><p><br></p>
</div>
</div>