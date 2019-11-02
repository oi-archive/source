<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在瑞典的达拉纳洲有一座高山。山上有一个小屋，里面住着一位牧羊女。每天清晨，隔壁的山头会传来一阵悠扬的长笛声，而牧羊女则会站在屋里用自己的歌声回应。</p>
<p>小屋的俯视图是一个有<em>n</em>个顶点的简单多边形，每一面墙可以反射声音，但是由于不可避免的能量损失，最多只能反射<em>k</em>次（<em>k</em>=0表示不能反射声音）。墙面非常光滑，因此声音的反射遵循反射角等于入射角，如图1。墙角不能反射声音，而每面墙的其他部分——即使离墙角很近——都可以反射声音。</p>
<p>突然有一天，牧羊女问自己：在小屋的哪些地方能听到她的歌声？假设所有听众都在屋里靠墙而坐，那么歌声能到达的墙一共有多长？</p>
<p>图2的四幅示意图分别画出了初始情况和声音经过0、1、2次反射后到达的区域。灰色部分表示能听到歌声的部分，黑点表示牧羊女的位置。本题所求即灰色部分在多边形边界上的<strong><span style="text-decoration: underline;">总长度</span></strong>。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含4个整数<em>n</em>，<em>k</em>，<em>x</em>，<em>y</em>分别表示小屋的墙角数、最多反射的次数以及牧羊女的坐标（牧羊女所在位置保证在屋内且至少离墙1个单位）。以下<em>n</em>行每行两个整数<em>x</em>, <em>y</em>，表示第<em>i</em>个墙角的坐标。墙角按照<strong><span style="text-decoration: underline;">顺时针或逆时针</span></strong>排列。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件仅包含一个实数<em>L</em>，表示能听到歌声的墙的总长度。保留两位小数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 0 100 135</p>
<p>20 200</p>
<p>200 100</p>
<p>300 125</p>
<p>40 10</p>
<p>100 100</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>469.86</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>3&lt;=<em>n</em>&lt;=50，0&lt;=<em>k</em>&lt;=5，所有坐标为绝对值不超过1000的整数</p>
<p>50%的数据满足<em>k</em>&lt;=1</p>
</div>
</div>