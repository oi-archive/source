# 题目描述


<p>
<b><span style="color:black;">题目描述</span></b> 
</p>
<div style="text-indent:21pt;text-align:left;" align="left">
<span style="color:black;">Andriy</span><span style="color:black;">很不厚道地把Wind的机器人都诱拐到了一个小岛上，机器人都很怕进水的。就在机器人绝望的时候，他们突然发现：竟然有一座小桥通往了对岸。</span> 
</div>
<div style="text-indent:21pt;text-align:left;" align="left">
<span style="color:black;">这座桥可以认为是一个3*n的矩形，如下图：</span> 
</div>
<p style="text-indent:21pt;text-align:left;" align="left">
<span style="color:black;"><!--[if gte vml 1]>
<![endif]--><img alt="" src="http://acm.hit.edu.cn/hoj/static/img/pic/100872a.jpg"/><br/>
</span> 
</p>
<div style="text-indent:21.75pt;">
<span style="color:black;">每个小方格都有可能覆盖有一块上面画直线或者折线的板。机器人们只有在沿着那些黑线走的时候心理才不会有恐惧感他们想知道，是否能通过旋转这些版使得存在一条最左边到最右边的通路。</span> 
</div>
<p style="text-indent:21.75pt;">
<span style="color:black;"><!--[if gte vml 1]>
<![endif]--><img alt="" src="http://acm.hit.edu.cn/hoj/static/img/pic/100872b.jpg"/><br/>
</span> 
</p>
<div>
<b><span style="color:black;">输入格式</span></b> 
</div>
<div style="text-indent:21.75pt;margin-right:-34.65pt;">
<span style="color:black;">第1行为一个整数k（k&lt;=10），表示有k组数据。</span> 
</div>
<div style="text-indent:21.75pt;margin-right:-34.65pt;">
<span style="color:black;">每组数据第一行为整数n (n&lt;=20000)</span> 
</div>
<div style="text-indent:21.75pt;margin-right:-34.65pt;">
<span style="color:black;">接下来n行，每行3个整数，描述这个桥，</span> 
</div>
<div style="text-indent:21.75pt;margin-right:-34.65pt;">
<span style="color:black;">其中0表示没有板，1表示直线的板，2表示折线的板。</span> 
</div>
<div style="margin-right:-34.65pt;">
<b><span style="color:black;">输出格式</span></b> 
</div>
<div style="text-indent:21.75pt;margin-right:-34.65pt;">
<span style="color:black;">k</span><span style="color:black;">行，每行对应一组数据，能形成通路，输出“yes”，否则输出“no”</span> 
</div>
<div style="margin-right:-34.65pt;">
<b><span style="color:black;">样例输入</span></b> 
</div>
<div style="margin-right:-34.65pt;">
<span style="color:black;">    4</span> 
</div>
<div style="text-indent:21pt;margin-right:-34.65pt;">
<span style="color:black;">5</span> 
</div>
<div style="text-indent:21pt;margin-right:-34.65pt;">
<span style="color:black;">1 2 1</span> 
</div>
<div style="text-indent:21pt;margin-right:-34.65pt;">
<span style="color:black;">2 1 2</span> 
</div>
<div style="text-indent:21pt;margin-right:-34.65pt;">
<span style="color:black;">1 2 1</span> 
</div>
<div style="text-indent:21pt;margin-right:-34.65pt;">
<span style="color:black;">2 1 2</span> 
</div>
<div style="text-indent:21pt;margin-right:-34.65pt;">
<span style="color:black;">1 2 1</span> 
</div>
<div style="text-indent:21pt;margin-right:-34.65pt;">
<span style="color:black;">3</span> 
</div>
<div style="text-indent:21pt;margin-right:-34.65pt;">
<span style="color:black;">1 1 1</span> 
</div>
<div style="text-indent:21pt;margin-right:-34.65pt;">
<span style="color:black;">1 1 1</span> 
</div>
<div style="text-indent:21pt;margin-right:-34.65pt;">
<span style="color:black;">2 0 2</span> 
</div>
<div style="text-indent:21pt;margin-right:-34.65pt;">
<span style="color:black;">3</span> 
</div>
<div style="text-indent:21pt;margin-right:-34.65pt;">
<span style="color:black;">0 0 0</span> 
</div>
<div style="text-indent:21pt;margin-right:-34.65pt;">
<span style="color:black;">0 0 0</span> 
</div>
<div style="text-indent:21pt;margin-right:-34.65pt;">
<span style="color:black;">0 0 0</span> 
</div>
<div style="text-indent:21pt;margin-right:-34.65pt;">
<span style="color:black;">4</span> 
</div>
<div style="text-indent:21pt;margin-right:-34.65pt;">
<span style="color:black;">1 2 1</span> 
</div>
<div style="text-indent:21pt;margin-right:-34.65pt;">
<span style="color:black;">2 1 2</span> 
</div>
<div style="text-indent:21pt;margin-right:-34.65pt;">
<span style="color:black;">1 2 1</span> 
</div>
<div style="text-indent:21pt;margin-right:-34.65pt;">
<span style="color:black;">0 1 2</span> 
</div>
<div style="margin-right:-34.65pt;">
<b><span style="color:black;">样例输出</span></b> 
</div>
<div style="text-indent:21pt;">
<span style="color:black;">yes</span> 
</div>
<div style="text-indent:21pt;">
<span style="color:black;">no</span> 
</div>
<div style="text-indent:21pt;">
<span style="color:black;">no</span> 
</div>
<div style="text-indent:21pt;">
<span style="color:black;">no</span> 
</div>
<div>
<b><span style="color:black;">数据规模</span></b> 
</div>
<div>
<span style="color:black;">对于30%的数据，n&lt;=500</span> 
</div>
<div>
<span style="color:black;">对于100%的数据，n&lt;=20000</span> 
</div>
<p>
 
</p>
