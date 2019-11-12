# 题目描述


<p style="text-align:center;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">海拔</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<h2 style="margin-top:0pt;margin-bottom:0pt;">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【问题描述】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</h2>
<p style="margin-top:0pt;text-indent:21pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">YT<span style="font-family:宋体;">市是一个规划良好的城市，城市被东西向和南北向的主干道划分为</span><span style="font-family:Calibri;">n×n</span><span style="font-family:宋体;">个区域。简单起见，可以将</span><span style="font-family:Calibri;">YT</span><span style="font-family:宋体;">市看作 一个正方形，每一个区域也可看作一个正方形。从而，</span><span style="font-family:Calibri;">YT</span><span style="font-family:宋体;">城市中包括</span><span style="font-family:Calibri;">(n+1)×(n+1)</span><span style="font-family:宋体;">个交叉路口和</span><span style="font-family:Calibri;">2n×(n+1)</span><span style="font-family:宋体;">条双向道路（简称道路），每条双向 道路连接主干道上两个相邻的交叉路口。下图为一张</span><span style="font-family:Calibri;">YT</span><span style="font-family:宋体;">市的地图</span><span style="font-family:Calibri;">(n = 2)</span><span style="font-family:宋体;">，城市被划分为</span><span style="font-family:Calibri;">2×2</span><span style="font-family:宋体;">个区域，包括</span><span style="font-family:Calibri;">3×3</span><span style="font-family:宋体;">个交叉路口和</span><span style="font-family:Calibri;">12</span><span style="font-family:宋体;">条双向道路。</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p style="text-align:center;"><img alt="" src="/images/altitude1.png" height="288" width="508"/></o:p></span>
</p>
<p style="margin-top:0pt;text-indent:21pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">小<span style="font-family:Calibri;">Z</span><span style="font-family:宋体;">作为该市的市长，他根据统计信息得到了每天上班高峰期间</span><span style="font-family:Calibri;">YT</span><span style="font-family:宋体;">市每条道路两个方向的人流量，即在高峰期间沿 着该方向通过这条道路的人数。每一个交叉路口都有不同的海拔高度值，</span><span style="font-family:Calibri;">YT</span><span style="font-family:宋体;">市市民认为爬坡是一件非常累的事情，每向上爬</span><span style="font-family:Calibri;">h</span><span style="font-family:宋体;">的高度，就需要消耗</span><span style="font-family:Calibri;">h</span><span style="font-family:宋体;">的体力。如果 是下坡的话，则不需要耗费体力。因此如果一段道路的终点海拔减去起点海拔的值为</span><span style="font-family:Calibri;">h(</span><span style="font-family:宋体;">注意</span><span style="font-family:Calibri;">h</span><span style="font-family:宋体;">可能是负数</span><span style="font-family:Calibri;">)</span><span style="font-family:宋体;">，那么一个人经过这段路所消耗的体力是</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;" class="15">max</span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">{0, h}<span style="font-family:宋体;">（这里</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;" class="15">max</span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">{a, b}<span style="font-family:宋体;">表示取</span><span style="font-family:Calibri;">a, b</span><span style="font-family:宋体;">两个值中的较大值）。</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<p style="margin-top:0pt;text-indent:21pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">小<span style="font-family:Calibri;">Z</span><span style="font-family:宋体;">还测量得到这个城市西北角的交叉路口海拔为</span><span style="font-family:Calibri;">0</span><span style="font-family:宋体;">，东南角的交叉路口海拔为</span><span style="font-family:Calibri;">1(</span><span style="font-family:宋体;">如上图所示</span><span style="font-family:Calibri;">)</span><span style="font-family:宋体;">，但其它交叉路口的海拔高度都无法得知。小</span><span style="font-family:Calibri;">Z</span><span style="font-family:宋体;">想知道在最理想的情况下（即你可以任意假设其他路口的海拔高度），每天上班高峰期间所有人爬坡消耗的总体力和的最小值。</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<h2 style="margin-top:0pt;margin-bottom:0pt;">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【输入格式】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</h2>
<p style="margin-top:0pt;text-indent:21pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><span style="font-family:宋体;">第一行包含一个整数</span><span style="font-family:Calibri;">n</span><span style="font-family:宋体;">，含义如上文所示。</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<p style="margin-top:0pt;text-indent:21pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">接下来<span style="font-family:Calibri;">4n(n + 1)</span><span style="font-family:宋体;">行，每行包含一个非负整数分别表示每一条道路每一个方向的人流量信息。输入顺序：</span><span style="font-family:Calibri;">n(n + 1)</span><span style="font-family:宋体;">个数表示所有从西到东方向的人流量，然后</span><span style="font-family:Calibri;">n(n + 1)</span><span style="font-family:宋体;">个数表示所有从北到南方向的人流量，</span><span style="font-family:Calibri;">n(n + 1)</span><span style="font-family:宋体;">个数表示所有从东到西方向的人流量，最后是</span><span style="font-family:Calibri;">n(n + 1)</span><span style="font-family:宋体;">个数表示所有从南到北方向的人流量。对于每一个方向，输入顺序按照起点由北向南，若南北方向相同时由西到东的顺序给出</span><span style="font-family:Calibri;">(</span><span style="font-family:宋体;">参见样例输入</span><span style="font-family:Calibri;">)</span><span style="font-family:宋体;">。</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<h2 style="margin-top:0pt;margin-bottom:0pt;">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【输出格式】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</h2>
<p style="margin-top:0pt;text-indent:21pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><span style="font-family:宋体;">仅包含一个数，表示在最理想情况下每天上班高峰期间所有人爬坡所消耗的总体力和（即总体力和的最小值），结果四舍五入到整数。</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<h2 style="margin-top:0pt;margin-bottom:0pt;">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【样例输入】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</h2>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">1</span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">1</span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">2</span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">3</span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">4</span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">5</span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">6</span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">7</span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">8</span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<h2 style="margin-top:0pt;margin-bottom:0pt;">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【样例输出】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</h2>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">3</span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<h2 style="margin-top:0pt;margin-bottom:0pt;">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【样例说明】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</h2>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">样例数据见下图。</span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p><img alt="" src="/images/altitude2.png" height="229" width="471"/></o:p></span>
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">最理想情况下所有点的海拔如上图所示。</span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<h2 style="margin-top:0pt;margin-bottom:0pt;">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【数据规模】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</h2>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">对于<span style="font-family:Calibri;">20%</span><span style="font-family:宋体;">的数据：</span><span style="font-family:Calibri;">n ≤ 3</span><span style="font-family:宋体;">；</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">对于<span style="font-family:Calibri;">50%</span><span style="font-family:宋体;">的数据：</span><span style="font-family:Calibri;">n ≤ 15</span><span style="font-family:宋体;">；</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">对于<span style="font-family:Calibri;">80%</span><span style="font-family:宋体;">的数据：</span><span style="font-family:Calibri;">n ≤ 40</span><span style="font-family:宋体;">；</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">对于<span style="font-family:Calibri;">100%</span><span style="font-family:宋体;">的数据：</span><span style="font-family:Calibri;">1 ≤ n ≤ 500</span><span style="font-family:宋体;">，</span><span style="font-family:Calibri;">0 ≤ </span><span style="font-family:宋体;">流量 </span><span style="font-family:Calibri;">≤ 1,000,000</span><span style="font-family:宋体;">且所有流量均为整数。</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<h2 style="margin-top:0pt;margin-bottom:0pt;">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【提示】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</h2>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">海拔高度不一定是整数。</span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<h2 style="margin-top:0pt;margin-bottom:0pt;">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【运行时限】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</h2>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">2<span style="font-family:宋体;">秒。</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<h2 style="margin-top:0pt;margin-bottom:0pt;">
<span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;">【运行空限】</span><span style="font-family:&#39;宋体&#39;;font-size:18pt;font-weight:bold;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</h2>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;">512M<span style="font-family:宋体;">。</span></span><span style="font-family:&#39;Calibri&#39;;font-size:10.5pt;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span>
</p>
<!--EndFragment-->
