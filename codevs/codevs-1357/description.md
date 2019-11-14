<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小 H 是一位探险家。在险峻的珠穆朗玛峰，原始辽阔的非洲大草原，美丽冻人的南极大陆等<br>地方都留下过这位探险家的足迹。这次，他来到了位于南美洲充斥着大量毒虫猛兽的以及各<br>式各样传说的亚马逊热带雨林进行探险。为此，他花了许多时间来准备这次激动人心的探险。<br>在准备就绪后，小 H 和他的助手在当地导游的带领下踏入了这片雨林。 <br>通过 GPS 定位系统，他们获得了雨林大致的地图。这个地图是一个 n 行 m 列的字符网格<br>图，’.’表示的是空地，’*’表示的是不可通行的区域，’#’表示的是需要清理的区<br>域，’H’表示小 H 所在的位置，该区域是空地。他们的移动方式有 t 种，用<br>a[i],b[i](1&lt;=i&lt;=t)表示，假设他们所在的位置为第 x 行第 y 列，那么他们下一步的位置将<br>是第 x+a[i]行第 y+b[i]列，也可以是反方向，即第x-a[i]行第 y-b[i]列。小 H 一行人每天<br>可在选择一种移动方式，朝着正方向或者反方向连续走若干步之后停下，不可以不走。在当<br>天的行走过程中，他们不可以到达不可通行的区域，如果他们到达了一个需要清理的区域，<br>他们会停止移动。为了以后探险的方便，他们会用该天剩下的时间来清理该区域，之后该区<br>域将永久变成空地。 <br> 现在，为了使探险活动顺利的进行，他们将 q 个询问通过网络发送给了你，询问他们在<br>第 d[i](1&lt;=i&lt;=q)天能到达的区域个数，题目保证不会有无路可走的情况。你能帮助他解决<br>这个问题吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第 1 行包含三个正整数，分别表示 n、m、t。 <br>在第 2 行至第 n+1 行中，每行都有 m 个字符（只可能是’.’，’*’，’#’，’H’，其中’H’<br>有且只有一个）。 <br>在第 n+2 行至第 n+t+1 行中，每行有两个整数，分别表示 a[i]，b[i]（a[i]，b[i]不可能<br>同时为 0）。 <br>在第 n+t+2 行包含一个正整数，表示 q。 <br>在第 n+t+3 行至第 n+t+q+2 行共有 q 个整数，表示他们所询问的时间点（即 d[i]）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出共 q 行，对于每一个询问，输出他们所能走到的地点的个数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3 2 <br>H#. <br>*.. <br>… <br>1 0 <br>0 1 <br>2 <br>1 <br>2</p>

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
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 20%的数据，满足 n，m&lt;=4, q &lt;= 100； <br>对于 70%的数据，满足 n，m&lt;=300； <br>对于 100%的数据，满足 n，m&lt;=1000, t&lt;=5, q&lt;=1000, 0&lt;=d[i]&lt;=10^9；</p>
</div>
</div>