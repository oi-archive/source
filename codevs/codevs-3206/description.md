<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>某国个人所得税法规定，普通公民的主要应纳税收入项目及纳税金额如下：</span></p>
<p><span>工资、薪金所得。按月计算征税，以每月收入额减除费用<span style="font-family: Verdana;">800</span><span style="">元后的余额作爲该月应纳税所得额，税率如下表所示：</span></span></p>
<p><span>级数 月应纳税所得额 税率（<span style="font-family: Verdana;">%</span><span style="">）</span></span></p>
<p><span>1 <span style="">不超过</span><span style="font-family: Verdana;">500</span><span style="">元的 </span><span style="font-family: Verdana;">5</span></span></p>
<p><span>2 <span style="">超过</span><span style="font-family: Verdana;">500</span><span style="">元</span><span style="font-family: Verdana;">~2000</span><span style="">元的部分 </span><span style="font-family: Verdana;">10</span></span></p>
<p><span>3 <span style="">超过</span><span style="font-family: Verdana;">2000</span><span style="">元</span><span style="font-family: Verdana;">~5000</span><span style="">元的部分 </span><span style="font-family: Verdana;">15</span></span></p>
<p><span>4 <span style="">超过</span><span style="font-family: Verdana;">5000</span><span style="">元</span><span style="font-family: Verdana;">~20000</span><span style="">元的部分 </span><span style="font-family: Verdana;">20</span></span></p>
<p><span>5 <span style="">超过</span><span style="font-family: Verdana;">20000</span><span style="">元</span><span style="font-family: Verdana;">~40000</span><span style="">元的部分 </span><span style="font-family: Verdana;">25</span></span></p>
<p><span>6 <span style="">超过</span><span style="font-family: Verdana;">40000</span><span style="">元</span><span style="font-family: Verdana;">~60000</span><span style="">元的部分 </span><span style="font-family: Verdana;">30</span></span></p>
<p><span>7 <span style="">超过</span><span style="font-family: Verdana;">60000</span><span style="">元</span><span style="font-family: Verdana;">~80000</span><span style="">元的部分 </span><span style="font-family: Verdana;">35</span></span></p>
<p><span>8 <span style="">超过</span><span style="font-family: Verdana;">80000</span><span style="">元</span><span style="font-family: Verdana;">~100000</span><span style="">元的部分 </span><span style="font-family: Verdana;">40</span></span></p>
<p><span>9 <span style="">超过</span><span style="font-family: Verdana;">100000</span><span style="">元的部分 </span><span style="font-family: Verdana;">45</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>输入文件的第一行爲一个正整数<span style="font-family: Arial;">M</span><span style="">（</span><span style="font-family: Arial;">M&lt;= 50000</span><span style="">），表示该公司的职员总数（职员编号依次爲</span><span style="font-family: Arial;">1,2,</span><span style="">…</span><span style="font-family: Arial;">,M</span><span style="">）。接下来的各行每行表示一年内某一个职员的一项收入信息。具体格式如下： 工资、薪金收入信息：</span><span style="font-family: Arial;">PAY </span><span style="">职员编号 收入时间 收入金额</span></span></p>
<p><span>一次性劳务报酬收入信息：<span style="font-family: Arial;">INCOME </span><span style="">职员编号 收入时间 收入金额</span></span></p>
<p><span>其中，收入时间格式爲：<span style="font-family: Arial;">MM/DD</span><span style="">，</span><span style="font-family: Arial;">MM</span><span style="">表示月份（</span><span style="font-family: Arial;">1&lt;= MM&lt;=12</span><span style="">），</span><span style="font-family: Arial;">DD</span><span style="">表示日期（</span><span style="font-family: Arial;">1&lt;= DD&lt;=31</span><span style="">）；收入金额是一个正整数（单位：元），并假设每人每项收入金额小于</span><span style="font-family: Arial;">100</span><span style="">万元。</span></span></p>
<p><span>输入文件以字符“<span style="font-family: Arial;">#</span><span style="">”表示结束。输入文件中同一行相邻两项之间用一个或多个空格隔开。</span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件只有一个正数<span style="font-family: Arial;">P(</span><span style="font-family: 宋体;">保留两位小数</span><span style="font-family: Arial;">)</span><span style="font-family: 宋体;">，</span><span style="font-family: Arial;">P</span><span style="font-family: 宋体;">表示该公司所有职员一年内应交纳的个人所得税总额（单位：元）。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<div>2</div>
<div>PAY 1 2/23 3800</div>
<div>INCOME 2 4/8 4010</div>
<div>INCOME 2 4/18 800</div>
<div>PAY 1 8/14 6700</div>
<div>PAY 1 8/10 1200</div>
<div>PAY 2 12/10 20000</div>
<div>#</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5476.60</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>NOI中水题</p>
</div>
</div>