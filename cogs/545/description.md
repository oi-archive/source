# 题目描述


<p>
<br/>
</p>
<h2 style="font-weight:normal;">
<span style="font-size:small;">【问题描述】</span> 
</h2>
<p style="text-indent:0.85cm;">
<span style="font-size:small;">小</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>Z</i></span></span><span style="font-size:small;">自幼就酷爱数学。聪明的他特别喜欢研究一些数学小问题。</span> 
</p>
<p style="text-indent:0.85cm;">
<span style="font-size:small;">有一天，小</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>Z</i></span></span><span style="font-size:small;">在一张纸上选择了</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>n</i></span></span><span style="font-size:small;">个点，并用铅笔将它们两两连接起来，构成</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>n</i></span><span style="font-size:small;">(</span><span style="font-size:small;"><i>n</i></span><span style="font-size:small;">-1)/2</span></span><span style="font-size:small;">条线段。由于铅笔很细，可以认为这些线段的宽度为</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;">0</span></span><span style="font-size:small;">。</span> 
</p>
<p style="text-indent:0.85cm;">
<span style="font-size:small;">望着这些线段，小</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>Z</i></span></span><span style="font-size:small;">陷入了冥想中。他认为这些线段中的一部分比较重要，需要进行强调。因此小</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>Z</i></span></span><span style="font-size:small;">拿出了毛笔，将它们重新进行了描边。毛笔画在纸上，会形成一个</span><u><span style="font-size:small;"><b>半径为</b></span></u><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i><u><b>r</b></u></i></span></span><u><span style="font-size:small;"><b>的圆</b></span></u><span style="font-size:small;">。</span><u><span style="font-size:small;"><b>在对一条线段进行描边时，毛笔的中心</b></span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><b>(</b></span></span></u><u><span style="font-size:small;"><b>即圆心</b></span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><b>)</b></span></span></u><u><span style="font-size:small;"><b>将从线段的一个端点开始，沿着该线段描向另一个端点</b></span></u><span style="font-size:small;">。下图即为在一张</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;">4</span></span><span style="font-size:small;">个点的图中，对其中一条线段进行描边强调后的情况。</span> 
</p>
<p style="text-indent:0.85cm;">
<img alt="" width="333" height="253" src="/images/1.png"/> 
</p>
<p style="text-indent:0.85cm;" align="center">
<br/>
</p>
<p style="text-indent:0.85cm;">
<span style="font-size:small;">现在，小</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>Z</i></span></span><span style="font-size:small;">非常想知道在描边之后纸面上共有多大</span><u><span style="font-size:small;"><b>面积</b></span></u><span style="font-size:small;">的区域被强调，你能帮助他解答这个问题么？</span> 
</p>
<h2>
<span style="font-size:small;"><span style="font-weight:normal;">【输入文件】</span></span> 
</h2>
<p style="text-indent:0.85cm;">
<span style="font-size:small;">这是一道提交答案型试题，所有的输入文件 </span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-family:&#39;TimesNewRomanPSMT, Times New Roman, serif&#39;;"><span style="font-size:small;">path1.in~path10.in </span></span></span><span style="font-size:small;">已在相应目录下。</span> 
</p>
<p style="text-indent:0.85cm;">
<span style="font-size:small;">输入文件 </span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;">path*.in</span><span style="font-family:&#39;TimesNewRomanPSMT, Times New Roman, serif&#39;;"><span style="font-size:small;"> </span></span></span><span style="font-size:small;">第一行包含一个正整数</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>n</i></span></span><span style="font-size:small;">，表示选择的点的数目。</span> 
</p>
<p style="text-indent:0.85cm;">
<span style="font-size:small;">第</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;">2</span></span><span style="font-size:small;">至第</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>n</i></span><span style="font-size:small;">+1</span></span><span style="font-size:small;">行，第</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>i</i></span><span style="font-size:small;">+1</span></span><span style="font-size:small;">行有两个实数</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>x</i></span><sub><span style="font-size:small;"><i>i</i></span></sub><span style="font-size:small;">, </span><span style="font-size:small;"><i>y</i></span><sub><span style="font-size:small;"><i>i</i></span></sub></span><span style="font-size:small;">，表示</span><span style="font-size:small;">点</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>i</i></span></span><span style="font-size:small;">的坐标为</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;">(</span><span style="font-size:small;"><i>x</i></span><sub><span style="font-size:small;"><i>i</i></span></sub><span style="font-size:small;">, </span><span style="font-size:small;"><i>y</i></span><sub><span style="font-size:small;"><i>i</i></span></sub><span style="font-size:small;">)</span></span><span style="font-size:small;">。</span> 
</p>
<p style="text-indent:0.85cm;">
<span style="font-size:small;">第</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>n</i></span><span style="font-size:small;">+2</span></span><span style="font-size:small;">行有一个正整数</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>m</i></span></span><span style="font-size:small;">，表示小</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;">Z</span></span><span style="font-size:small;">认为比较重要的线段的条数。</span> 
</p>
<p style="text-indent:0.85cm;">
<span style="font-size:small;">第</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>n</i></span><span style="font-size:small;">+3</span></span><span style="font-size:small;">至第</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>n</i></span><span style="font-size:small;">+</span><span style="font-size:small;"><i>m</i></span><span style="font-size:small;">+2</span></span><span style="font-size:small;">行，每行有两个正整数</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>a</i></span><span style="font-size:small;">, </span><span style="font-size:small;"><i>b</i></span></span><span style="font-size:small;">表示一条线段。</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>a,</i></span><span style="font-size:small;"> </span><span style="font-size:small;"><i>b</i></span></span><span style="font-size:small;">两个数分别表示该线段的两个端点的编号。</span> 
</p>
<p style="text-indent:0.85cm;">
<span style="font-size:small;">第</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>n</i></span><span style="font-size:small;">+</span><span style="font-size:small;"><i>m</i></span><span style="font-size:small;">+3</span></span><span style="font-size:small;">行，有一个实数</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>r</i></span></span><span style="font-size:small;">，表示毛笔在纸上形成的圆的半径。</span> 
</p>
<p style="text-indent:0.85cm;">
<span style="font-size:small;">第</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>n</i></span><span style="font-size:small;">+</span><span style="font-size:small;"><i>m</i></span><span style="font-size:small;">+4</span></span><span style="font-size:small;">行，有四个实数</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>p</i></span><span style="font-size:small;">1, </span><span style="font-size:small;"><i>p</i></span><span style="font-size:small;">2, </span><span style="font-size:small;"><i>p</i></span><span style="font-size:small;">3, </span><span style="font-size:small;"><i>p</i></span><span style="font-size:small;">4</span></span><span style="font-size:small;">，为评分使用的参数。</span> 
</p>
<h2>
<span style="font-size:small;"><span style="font-weight:normal;">【输出文件】</span></span> 
</h2>
<p style="text-indent:0.77cm;">
<span style="font-size:small;">输出文件</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;">path*.out</span></span><span style="font-size:small;">仅包含一行，即为描边后被强调区域的总面积</span>。
</p>
<h2 style="font-weight:normal;">
<span style="font-size:small;">【输入样例】</span> 
</h2>
<p style="text-indent:0.74cm;">
<span style="font-family:&#39;Courier New, monospace&#39;;"><span style="font-size:small;">2</span></span> 
</p>
<p style="text-indent:0.74cm;">
<span style="font-family:&#39;Courier New, monospace&#39;;"><span style="font-size:small;">1 1</span></span> 
</p>
<p style="text-indent:0.74cm;">
<span style="font-family:&#39;Courier New, monospace&#39;;"><span style="font-size:small;">1 2</span></span> 
</p>
<p style="text-indent:0.74cm;">
<span style="font-family:&#39;Courier New, monospace&#39;;"><span style="font-size:small;">1</span></span> 
</p>
<p style="text-indent:0.74cm;">
<span style="font-family:&#39;Courier New, monospace&#39;;"><span style="font-size:small;">1 2</span></span> 
</p>
<p style="text-indent:0.74cm;">
<span style="font-family:&#39;Courier New, monospace&#39;;"><span style="font-size:small;">1</span></span> 
</p>
<p style="text-indent:0.74cm;">
<span style="font-family:&#39;Courier New, monospace&#39;;"><span style="font-size:small;">0.00001 0.001 0.1 1</span></span> 
</p>
<h2 style="font-weight:normal;">
<span style="font-size:small;">【输出样例】</span> 
</h2>
<p>
<span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-family:&#39;Courier New, monospace&#39;;"><span style="font-size:small;">5.1415927</span></span></span> 
</p>
<h2 style="font-weight:normal;">
<span style="font-size:small;">【样例说明】</span> 
</h2>
<p style="text-indent:0.77cm;">
<span style="font-size:small;">如下图所示。</span> 
</p>
<p style="text-indent:0.74cm;" align="center">
<br/>
</p>
<h2 style="font-weight:normal;">
<span style="font-size:small;">【评分标准】</span> 
</h2>
<p style="text-indent:0.77cm;">
<span style="font-size:small;">每个测试点单独评分。</span> 
</p>
<p style="text-indent:0.77cm;">
<span style="font-size:small;">本题设有</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;">4</span></span><span style="font-size:small;">个评分参数</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>p</i></span><span style="font-size:small;">1,</span><span style="font-size:small;"><i>p</i></span><span style="font-size:small;">2,</span><span style="font-size:small;"><i>p</i></span><span style="font-size:small;">3,</span><span style="font-size:small;"><i>p</i></span><span style="font-size:small;">4 (</span><span style="font-size:small;"><i>p</i></span><span style="font-size:small;">1&lt; </span><span style="font-size:small;"><i>p</i></span><span style="font-size:small;">2 &lt; </span><span style="font-size:small;"><i>p</i></span><span style="font-size:small;">3 &lt; </span><span style="font-size:small;"><i>p</i></span><span style="font-size:small;">4)</span></span><span style="font-size:small;">，已在输入文件中给出。你的得分将按照如下规则给出：</span> 
</p>
<p style="text-indent:0.74cm;">
<a name="OLE_LINK7"></a><a name="OLE_LINK8"></a><span style="font-size:small;">若你的答案与标准答案相差不超过</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>p</i></span><span style="font-size:small;">1</span></span><span style="font-size:small;">，则该测试点你将得到满分；</span> 
</p>
<p style="text-indent:0.77cm;">
<span style="font-size:small;">否则，若你的答案与标准答案相差不超过</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>p</i></span><span style="font-size:small;">2</span></span><span style="font-size:small;">，则你将得到该测试点</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;">70%</span></span><span style="font-size:small;">的分数；</span> 
</p>
<p style="text-indent:0.77cm;">
<span style="font-size:small;">否则，若你的答案与标准答案相差不超过</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>p</i></span><span style="font-size:small;">3</span></span><span style="font-size:small;">，则你将得到该测试点</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;">40%</span></span><span style="font-size:small;">的分数；</span> 
</p>
<p style="text-indent:0.77cm;">
<span style="font-size:small;">否则，若你的答案与标准答案相差不超过</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;"><i>p</i></span><span style="font-size:small;">4</span></span><span style="font-size:small;">，则你将得到该测试点</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;">10%</span></span><span style="font-size:small;">的分数；</span> 
</p>
<p style="text-indent:0.77cm;">
<span style="font-size:small;">否则该测试点你的得分为</span><span style="font-family:&#39;DejaVu Serif Condensed, serif&#39;;"><span style="font-size:small;">0</span></span><span style="font-size:small;">。</span> 
</p>
