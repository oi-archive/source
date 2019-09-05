# 题目描述


<p>
<b><span style="font-family:Microsoft YaHei;">MOTOR</span></b> 
</p>
<p>
<b><span style="font-family:Microsoft YaHei;">题目描述</span><span></span></b> 
</p>
<p style="text-align:left;text-indent:21.0pt;" align="left">
<span style="font-family:Microsoft YaHei;">Fish最喜欢玩暴力摩托，一个通宵之后，总算过了全关！正当他为自己的成绩洋洋得意的时候却发现居然还有一个特别的附加关！</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Fish</span><span style="font-family:Microsoft YaHei;">虽然累得眼睛都睁不开了，但是他还是决定再试一试！</span><span></span> 
</p>
<p style="text-align:left;text-indent:21.0pt;" align="left">
<span style="font-family:Microsoft YaHei;">这一关与以前的关不同，包含有</span><span style="font-family:&#39;Microsoft YaHei&#39;;">N</span><span style="font-family:Microsoft YaHei;">个站，之间连了</span><span style="font-family:&#39;Microsoft YaHei&#39;;">M</span><span style="font-family:Microsoft YaHei;">条双向的通路！但每条路都规定了一个</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Speed</span><span style="font-family:Microsoft YaHei;">值，在这条路上必须以这个速度前进！所以在前进的时候要频繁的调整速度，这对鱼类来说是很痛苦的，所以</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Fish</span><span style="font-family:Microsoft YaHei;">决定尽量使调整的幅度小一些，也就是使走过的路的速度最大值与最小值之差最小！</span><span></span> 
</p>
<p style="text-align:left;text-indent:21.0pt;" align="left">
<span style="font-family:Microsoft YaHei;">可最近</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Fish</span><span style="font-family:Microsoft YaHei;">由于沉溺在暴力摩托中，已经荒废了编程技术，所以只有请你来帮忙了！</span><b></b> 
</p>
<p style="text-align:left;" align="left">
<b><span style="font-family:Microsoft YaHei;"> </span></b> 
</p>
<p style="text-align:left;" align="left">
<b><span style="font-family:Microsoft YaHei;">输入文件</span><span></span></b> 
</p>
<p style="text-align:left;text-indent:21.0pt;" align="left">
<span style="font-family:Microsoft YaHei;">第一行有</span><span style="font-family:&#39;Microsoft YaHei&#39;;">2</span><span style="font-family:Microsoft YaHei;">个正整数</span><span style="font-family:&#39;Microsoft YaHei&#39;;">N</span><span style="font-family:Microsoft YaHei;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">M</span><span style="font-family:Microsoft YaHei;">，分别表示站点数，路径数。</span><span></span> 
</p>
<p style="text-align:left;text-indent:21.0pt;" align="left">
<span style="font-family:Microsoft YaHei;">接下来</span><span style="font-family:&#39;Microsoft YaHei&#39;;">M</span><span style="font-family:Microsoft YaHei;">行，每行有</span><span style="font-family:&#39;Microsoft YaHei&#39;;">3</span><span style="font-family:Microsoft YaHei;">个正整数</span><span style="font-family:&#39;Microsoft YaHei&#39;;"> X, Y, V</span><span style="font-family:Microsoft YaHei;">表示</span><span style="font-family:&#39;Microsoft YaHei&#39;;">X</span><span style="font-family:Microsoft YaHei;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;"> Y</span><span style="font-family:Microsoft YaHei;">之间有一条路，其</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Speed</span><span style="font-family:Microsoft YaHei;">值是</span><span style="font-family:&#39;Microsoft YaHei&#39;;">V</span><span style="font-family:Microsoft YaHei;">。再接下来是数</span><span style="font-family:&#39;Microsoft YaHei&#39;;">K</span><span style="font-family:Microsoft YaHei;">，表示任务数，下面</span><span style="font-family:&#39;Microsoft YaHei&#39;;">K</span><span style="font-family:Microsoft YaHei;">行，每行有一对正整数</span><span style="font-family:&#39;Microsoft YaHei&#39;;">P</span><span style="font-family:Microsoft YaHei;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Q</span><span style="font-family:Microsoft YaHei;">，表示一个任务从</span><span style="font-family:&#39;Microsoft YaHei&#39;;">P</span><span style="font-family:Microsoft YaHei;">到</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Q</span><span style="font-family:Microsoft YaHei;">。</span> 
</p>
<p style="text-align:left;" align="left">
<b><span style="font-family:Microsoft YaHei;"> </span></b> 
</p>
<p style="text-align:left;" align="left">
<b><span style="font-family:Microsoft YaHei;">输出文件</span><span></span></b> 
</p>
<p style="text-align:left;text-indent:21.0pt;" align="left">
<span style="font-family:Microsoft YaHei;">对于每一个任务输出一行，仅一个数，即最大速度与最小速度之差。</span><span></span> 
</p>
<p style="text-align:left;" align="left">
<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p>
<b><span style="font-family:Microsoft YaHei;">样例</span><span></span></b> 
</p>
<p>
<b><span style="font-family:Microsoft YaHei;">输入</span><span></span></b> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-family:Microsoft YaHei;">4 4</span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-family:Microsoft YaHei;">1 2 2</span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-family:Microsoft YaHei;">2 3 4</span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-family:Microsoft YaHei;">1 4 1</span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-family:Microsoft YaHei;">3 4 2</span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-family:Microsoft YaHei;">2</span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-family:Microsoft YaHei;">1 3</span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-family:Microsoft YaHei;">1 2</span> 
</p>
<p>
<span style="font-family:Microsoft YaHei;"> </span> 
</p>
<p>
<b><span style="font-family:Microsoft YaHei;">输出</span><span></span></b> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-family:Microsoft YaHei;">1</span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-family:Microsoft YaHei;">0</span> 
</p>
<p>
<br/>
</p>
<p>
<b><span style="font-family:Microsoft YaHei;">数据约定</span><span></span></b> 
</p>
<p>
<span style="font-family:Microsoft YaHei;">    1&lt;=n&lt;=200,
1&lt;=m&lt;=1000, 1&lt;=K&lt;=10</span> 
</p>
<p>
<br/>
</p>
