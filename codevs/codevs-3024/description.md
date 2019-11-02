<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>大妈打完三战回家，我知道他是怎么回来的，欧洲到日本有L个站点他决定乘坐恰好n次飞机（不是学院都市的超音速飞机）和m次火车来从第一个站点到达最后一个站点。但是有一点很重要的就是跟御坂美琴那样的壕不同大妈很穷，所以他决定要尽量花费最少的费用，当然如果能赚到钱那就更好了。由于当麻交友甚广，他们在某些站点可以见到一些故友，可以得到资助，而在有些站点不但不会赚钱，还会因为要住宿，买车票，旅游等而花费一定的费用。如果他乘坐火车，那么就会受到所经过的站点（包括终点不包括起点）的影响，花费一定费用或赚到一定的钱，而他做飞机的话就不会受到站点的影响，他已经知道了每个站点的情况，为防止钱花的过多被index咬头他决定找你来帮他找到最省钱（赚钱）的方案</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件back.in第一行包含三个整数，为他们决定坐火车的次数m，他们决定坐飞机的次数n，站点数L。第二行为L个整数，每个数都在-200到200之间，表示每个站点的情况，正数表示能赚到钱，负数表示会花费钱。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件back.out包含一个整数，表示他们最多能赚到多少钱（如果入不敷出就输出负数来表示他们花了多少钱）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 6 14</p>
<p>12 32 43 -1 32 -9 -10 32 -43 -21 -32 12 -31 -3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>150</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例解释】</p>
<p>一种最赚钱的方法为：1-〉2（火车），2-〉3（火车），3-〉4（火车），4-〉5（火车），5-〉7（飞机），7-〉8（火车），8-〉9（飞机），9-〉10（飞机），10-〉11（飞机），11-〉12（火车），12-〉13（飞机），13-〉14（飞机）</p>
<p>【数据范围】</p>
<p>n+m&lt;L</p>
<p>对于60%的数据，1&lt;=n，m&lt;=50，1&lt;=L&lt;=200。</p>
<p>对于100%的数据，1&lt;=n，m&lt;=200，1&lt;=L&lt;=500。</p>
</div>
</div>