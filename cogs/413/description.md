# 题目描述


<p>
<br/>
</p>
<div align="center">
 
</div>
<b><span style="font-size:14pt;">试题描述</span></b><br/>
<span style="font-size:12pt;">有一块</span><span style="font-size:12pt;">n*m</span><span style="font-size:12pt;">的矩形巧克力，准备将它切成</span><span style="font-size:12pt;">n*m</span><span style="font-size:12pt;">块。巧克力上共有</span><span style="font-size:12pt;">n-1</span><span style="font-size:12pt;">条横线和</span><span style="font-size:12pt;">m-1</span><span style="font-size:12pt;">条竖线，你每次可以沿着其中的一条横线或竖线将巧克力切开，无论切割的长短，沿着每条横线切一次的代价依次为</span><span style="font-size:12pt;">y<sub>1</sub></span><span style="font-size:12pt;">，</span><span style="font-size:12pt;">y<sub>2</sub></span><span style="font-size:12pt;">，…，</span><span style="font-size:12pt;">y<sub>n-1</sub></span><span style="font-size:12pt;">，而沿竖线切割的代价依次为</span><span style="font-size:12pt;">x<sub>1</sub></span><span style="font-size:12pt;">，</span><span style="font-size:12pt;">x<sub>2</sub></span><span style="font-size:12pt;">，…，</span><span style="font-size:12pt;">x<sub>m-1</sub></span><span style="font-size:12pt;">。例如，对于下图</span><span style="font-size:12pt;">6*4</span><span style="font-size:12pt;">的巧克力，我们先沿着三条横线切割，需要</span><span style="font-size:12pt;">3</span><span style="font-size:12pt;">刀，得到</span><span style="font-size:12pt;">4</span><span style="font-size:12pt;">条巧克力，然后再将这</span><span style="font-size:12pt;">4</span><span style="font-size:12pt;">条巧克力沿竖线切割，每条都需要</span><span style="font-size:12pt;">5</span><span style="font-size:12pt;">刀，则最终所花费的代价为</span><span style="font-size:12pt;">y<sub>1</sub>+y<sub>2</sub>+y<sub>3</sub>+4*(x<sub>1</sub>+x<sub>2</sub>+x<sub>3</sub>+x<sub>4</sub>+x<sub>5</sub>)</span><span style="font-size:12pt;">。</span> 
<p>
<br/>
</p>
<p style="text-align:center;">
<span style="font-size:12pt;"><img width="352" height="202" alt="" src="/images/chocolate1.bmp"/></span> 
</p>
<div>
<span style="font-size:12pt;">当然，上述简单切法不见得是最优切法，那么怎样切割该块巧克力，花费的代价最少呢？</span> 
</div>
<div>
 
</div>
<div>
<b><span style="font-size:14pt;">输入数据</span></b> 
</div>
<div>
<span style="font-size:12pt;">第一行为两个整数</span><span style="font-size:12pt;">n</span><span style="font-size:12pt;">和</span><span style="font-size:12pt;">m</span><span style="font-size:12pt;">。</span> 
</div>
<div>
<span style="font-size:12pt;">接下来</span><span style="font-size:12pt;">n-1</span><span style="font-size:12pt;">行，每行一个整数，分别代表</span><span style="font-size:12pt;">x<sub>1</sub></span><span style="font-size:12pt;">，</span><span style="font-size:12pt;">x<sub>2</sub></span><span style="font-size:12pt;">，…，</span><span style="font-size:12pt;">x<sub>n-1</sub></span><span style="font-size:12pt;">。</span> 
</div>
<div>
<span style="font-size:12pt;">接下来</span><span style="font-size:12pt;">m-1</span><span style="font-size:12pt;">行，每行一个整数，分别代表</span><span style="font-size:12pt;">y<sub>1</sub></span><span style="font-size:12pt;">，</span><span style="font-size:12pt;">y<sub>2</sub></span><span style="font-size:12pt;">，…，</span><span style="font-size:12pt;">y<sub>m-1</sub></span><span style="font-size:12pt;">。</span> 
</div>
<div>
<b> </b> 
</div>
<div>
<b><span style="font-size:14pt;">输出数据</span></b><b><span style="font-size:12pt;">                </span></b> 
</div>
<div>
<span style="font-size:12pt;">输出一整数，为切割巧克力的最小代价。</span> 
</div>
<div>
 
</div>
<div>
<b><span style="font-size:14pt;">样例输入</span></b> 
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
<span style="font-size:12pt;">6 4</span> 
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
<span style="font-size:12pt;">2</span> 
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
<span style="font-size:12pt;">1</span> 
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
<span style="font-size:12pt;">3</span> 
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
<span style="font-size:12pt;">1</span> 
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
<span style="font-size:12pt;">4</span> 
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
<span style="font-size:12pt;">4</span> 
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
<span style="font-size:12pt;">1</span> 
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
<span style="font-size:12pt;">2</span> 
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
 
</div>
<div>
<b><span style="font-size:14pt;">样例输出</span></b> 
</div>
<div>
<span style="font-size:12pt;">42</span> 
</div>
<div>
 
</div>
<div>
<b><span style="font-size:14pt;">测试数据范围</span></b> 
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
<span style="font-size:12pt;">30%</span><span style="font-size:12pt;">的数据，</span><span style="font-size:12pt;">n&lt;=100,m&lt;=100</span> 
</div>
<div style="margin:0cm 0cm 0pt 21pt;">
<span style="font-size:12pt;">100%</span><span style="font-size:12pt;">的数据，</span><span style="font-size:12pt;">n&lt;=10000</span><span style="font-size:12pt;">，</span><span style="font-size:12pt;">m&lt;=10000</span> 
</div>
