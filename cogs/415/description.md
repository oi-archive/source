# 题目描述


<div style="text-align:left;">
<b><span style="font-size:14pt;">试题描述</span></b> 
</div>
<div style="text-align:left;" align="left">
<span style="font-size:12pt;">小明住在城市</span><span style="font-size:12pt;">1</span><span style="font-size:12pt;">，而他的朋友小芳住在城市</span><span style="font-size:12pt;">n</span><span style="font-size:12pt;">。最近小明收到小芳的邀请，准备于近期赴约。可是由于最近下了很多暴雨，很多道路都被淹没。从城市</span><span style="font-size:12pt;">1</span><span style="font-size:12pt;">出发到城市</span><span style="font-size:12pt;">n</span><span style="font-size:12pt;">之间有很多小城镇，并且两个小城镇之间有一条直接道路相连。小明经过对近期天气和地形的科学分析，绘出了每条道路能顺利通行的概率。</span> 
</div>
<div style="text-align:left;" align="left">
<span style="font-size:12pt;">为了能顺利到达目的地，请帮助小明找出一条最稳妥的路线，也就是从城市</span><span style="font-size:12pt;">1</span><span style="font-size:12pt;">出发到达城市</span><span style="font-size:12pt;">n</span><span style="font-size:12pt;">的路线中能顺利通行的最大概率。</span> 
</div>
<div align="left">
<span style="font-size:12pt;"> </span> 
</div>
<div>
<b><span style="font-size:14pt;">输入数据</span></b> 
</div>
<div style="text-align:left;" align="left">
<span style="font-size:12pt;">文件第一行包含两个整数</span><span style="font-size:12pt;">n</span><span style="font-size:12pt;">和</span><span style="font-size:12pt;">m</span><span style="font-size:12pt;">，</span><span style="font-size:12pt;">n</span><span style="font-size:12pt;">为城市数，</span><span style="font-size:12pt;">m</span><span style="font-size:12pt;">为道路条数。</span> 
</div>
<div style="text-align:left;" align="left">
<span style="font-size:12pt;">接下来</span><span style="font-size:12pt;">m</span><span style="font-size:12pt;">行，每行包含三个整数</span><span style="font-size:12pt;">a</span><span style="font-size:12pt;">，</span><span style="font-size:12pt;">b</span><span style="font-size:12pt;">，</span><span style="font-size:12pt;">p ( 1&lt;=p&lt;=100 )</span><span style="font-size:12pt;">，表示小城镇</span><span style="font-size:12pt;">a</span><span style="font-size:12pt;">与小城镇</span><span style="font-size:12pt;">b</span><span style="font-size:12pt;">间有一条道路，顺利通过这条道路的概率为</span><span style="font-size:12pt;">p%</span><span style="font-size:12pt;">。</span> 
</div>
<div style="text-align:left;" align="left">
</div>
<div>
<b><span style="font-size:14pt;">输出数据</span></b><b><span style="font-size:12pt;"> </span></b> 
</div>
<div style="text-align:left;" align="left">
<span style="font-size:12pt;">一个实数</span><span style="font-size:12pt;">P</span><span style="font-size:12pt;">，为到达城市</span><span style="font-size:12pt;">n</span><span style="font-size:12pt;">的最大概率，</span><span style="font-size:12pt;">P</span><span style="font-size:12pt;">精确到小数点后</span><span style="font-size:12pt;">6</span><span style="font-size:12pt;">位。</span> 
</div>
<div style="text-align:left;" align="left">
<span style="font-size:small;"><span style="line-height:24px;"><br/>
</span></span> 
</div>
<div style="text-align:left;" align="left">
</div>
<div>
<b><span style="font-size:14pt;">样例输入</span></b> 
</div>
<img src="/images/toura1(1).bmp" width="179" height="202" align="right" alt=""/> 
<div style="margin:0cm 0cm 0pt 21pt;text-align:left;" align="left">
<span style="font-size:12pt;">5 7</span> 
</div>
<div style="margin:0cm 0cm 0pt 21pt;text-align:left;" align="left">
<span style="font-size:12pt;">5 2 100</span> 
</div>
<div style="margin:0cm 0cm 0pt 21pt;text-align:left;" align="left">
<span style="font-size:12pt;">3 5 80</span> 
</div>
<div style="margin:0cm 0cm 0pt 21pt;text-align:left;" align="left">
<span style="font-size:12pt;">2 3 70</span> 
</div>
<div style="margin:0cm 0cm 0pt 21pt;text-align:left;" align="left">
<span style="font-size:12pt;">2 1 50</span> 
</div>
<div style="margin:0cm 0cm 0pt 21pt;text-align:left;" align="left">
<span style="font-size:12pt;">3 4 90</span> 
</div>
<div style="margin:0cm 0cm 0pt 21pt;text-align:left;" align="left">
<span style="font-size:12pt;">4 1 85 </span> 
</div>
<div style="margin:0cm 0cm 0pt 21pt;text-align:left;" align="left">
<span style="font-size:12pt;">3 1 70</span> 
</div>
<div>
<b><span style="font-size:14pt;">样例输出</span></b> 
</div>
<div>
<span style="font-size:12pt;">61.200000</span> 
</div>
<div>
</div>
<div>
<b><span style="font-size:14pt;">样例说明：选择路线为</span></b><b><span style="font-size:14pt;">1-4-3</span></b><b><span style="font-size:14pt;">-5</span></b><b><span style="font-size:14pt;">，概率为</span></b><b><span style="font-size:14pt;">85%*90%*80%=61.2%</span></b> 
</div>
<div>
<b><span style="font-size:14pt;">测试数据范围</span></b> 
</div>
<div style="text-align:left;" align="left">
<span style="font-size:12pt;">30%</span><span style="font-size:12pt;">的数据，</span><span style="font-size:12pt;">n&lt;=1000</span><span style="font-size:12pt;">，</span><span style="font-size:12pt;">m&lt;=3000</span> 
</div>
<div style="text-align:left;" align="left">
<span style="font-size:12pt;">100%</span><span style="font-size:12pt;">的数据，</span><span style="font-size:12pt;">n&lt;=10000</span><span style="font-size:12pt;">，</span><span style="font-size:12pt;">m&lt;=30000</span> 
</div>
