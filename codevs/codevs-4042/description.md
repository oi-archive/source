<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">话说YJY上次丢了成绩单（见4024）被老师训了一顿，很生气，于是一气之下，YJY和朋友一起从城市A去城市B旅游，消消气。<b>他</b>知道每个城市都有四个飞机场，分别位于一个矩形的四个顶点上，同一个城市中两个机场之间有一条笔直的高速铁路，第I个城市中高速铁路了的单位里程价格为Ti，任意两个不同城市的机场之间均有航线，所有航线单位里程的价格均为t。</p><p style="">那么YJY应如何安排到城市B的路线才能尽可能的节省花费呢?<b>他</b>发现这并不是一个简单的问题，而且他的智商很......，而他并不能暴露他的IQ，so，他偷偷地来向你请教。找出一条从城市A到B的旅游路线，出发和到达城市中的机场可以任意选取，要求总的花费最少。</p><hr><p style=""><strong>如图片无法正常显示，请到  http://yunpan.cn/cd6iAuIj3gTqn （提取码：19b0）查看下载（无需下载任何插件即可查看）。下面图片由“贴图库”提供技术支持</strong></p><p style=""><img height="294" src="/source/codevs/codevs-4042/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy00MDQyL2h0dHA6Ly9pMy50aWV0dWt1LmNvbS81N2RjMWVlNmQ1YmIwMDQ3LnBuZw==.png" style="" width="581"></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">第一行有四个正整数s，t，A，B。S(0&lt;S&lt;=100)表示城市的个数，t表示飞机单位里程的价格，A，B分别为城市A，B的序号，(1&lt;=A，B&lt;=S)。</p><p style="">接下来有S行，其中第I行均有7个正整数xi1，yi1，xi2，yi2，xi3，yi3，Ti，这当中的(xi1，yi1)，(xi2，yi2)，(xi3，yi3)分别是第I个城市中任意三个机场的坐标，T I为第I个城市高速铁路单位里程的价格。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family:宋体"></span><span style="color: rgb(51, 51, 51); font-family: &#39;Lucida Grande&#39;, Lucida, &#39;Lucida Sans Unicode&#39;, &#39;Lucida Sans&#39;, Tahoma, &#39;Segoe UI&#39;, Verdana, 微软雅黑, &#39;Microsoft YaHei&#39;, 宋体; font-size: 14px; line-height: 21px; background-color: rgb(255, 255, 255);">输出最小费用(结果保留两位小数)</span><span style="font-family:宋体"></span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 10 1 3</p><p>1 1 1 3 3 1 30</p><p>2 5 7 4 5 2 1</p><p>8 6 8 8 11 6 3</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>47.55</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">图的最短路径问题</span></p><p><span style="">NOIP2001第四题，有删改。</span></p><p><span style="">YJY与LZC系列</span></p>
</div>
</div>