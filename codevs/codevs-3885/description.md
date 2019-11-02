<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">你发现了一张藏宝图！</span></p><p style=""><span style="">藏宝图告诉你，有一块区域被分割成</span>n<span style="">行</span>n<span style="">列的方格，每个方格的下方都可能有宝藏，不过有且只有一个方格下面确实有宝藏。</span></p><p style=""><span style="">每个方格里都插着一块木牌，每个木牌上都有两个数据。藏宝图还告诉你，那代表一个坐标。如果你从有宝藏的那个方格开始，走到该处木牌上的坐标对应的方格，这样连续重复</span>k<span style="">次，你就会到达坐标</span>(x,y)<span style="">所对应的点。</span></p><p style=""><span style="">虽然这有些复杂，但是你觉得宝藏可能很值钱，还是去了。</span></p><p style=""><span style="">不过你是坐飞机过来的，当你到了该区域的上空时，迫不及待地跳了下来，坐标竟然正好是</span>(x,y)<span style="">。你发现这里的情形和藏宝图上描述的一模一样。</span></p><p style=""><span style="">你带了些笔纸，依次记下了每个方格中的两个数据。可是你突然发现，这样还不一定能够确定宝藏所在的唯一的坐标。你想要编个程序，求出有多少个方格下可能有宝藏。</span></p><p style=""><span style="">假定藏宝图的话准确无误。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行，正整数</span>n<span style="">和</span>k<span style="">。</span></p><p style=""><span style="">第二行，正整数</span>x<span style="">和</span>y<span style="">。</span></p><p style=""><span style="">接下来</span>n<span style="">行，每行有</span>2n<span style="">个数据，依次是</span>n<span style="">个木牌上的两个数据（第一个是横坐标，第二个是纵坐标。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-top: 0px; margin-bottom: 10px; white-space: normal; box-sizing: border-box; color: rgb(88, 102, 110); font-family: &#39;Source Sans Pro&#39;, &#39;Helvetica Neue&#39;, Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px; background-color: rgb(255, 255, 255);"><span style="box-sizing: border-box; font-family: 宋体;">第一行，一个数据</span>m<span style="box-sizing: border-box; font-family: 宋体;">，代表可能有宝藏的方格数目。</span></p><p style="margin-top: 0px; margin-bottom: 10px; white-space: normal; box-sizing: border-box; color: rgb(88, 102, 110); font-family: &#39;Source Sans Pro&#39;, &#39;Helvetica Neue&#39;, Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px; background-color: rgb(255, 255, 255);"><span style="box-sizing: border-box; font-family: 宋体;">接下来</span><span style="box-sizing: border-box; font-family: Calibri;">m</span><span style="box-sizing: border-box; font-family: 宋体;">行，每行两个数据，代表可能有宝藏的坐标。（以行数为第一关键字，列数为第二关键字，从小到大排序。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="">3 6</p><p style="">2 2</p><p style="">1 2 1 3 2 1</p><p style="">2 2 1 3 2 2</p><p style="">2 3 3 1 3 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style="">3</p><p style="">1 2</p><p style="">2 2</p><p style="">3 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">对于</span>50%<span style="">的数据，</span>n&lt;=100<span style="">，</span>k&lt;=100<span style="">；</span></p><p style=""><span style="">对于</span>100%<span style="">的数据，</span>n&lt;=500<span style="">，</span>k&lt;=10000<span style="">。</span></p><p style=""><span style="">保证一切数据合法。</span></p>
</div>
</div>