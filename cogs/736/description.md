

# i


<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于给定的太空船的信息，找到让所有人尽快地全部转移到月球上的运输方案。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«数据输入：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">由文件<span>home.in</span>提供输入数据。文件第1行有3 个正整数n（太空站个数），m（太空船</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">个数）和k（需要运送的地球上的人的个数）。其中 1&lt;=m&lt;=20, 1&lt;=n&lt;=13, 1&lt;=k&lt;=50。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">接下来的m行给出太空船的信息。第i+1 行说明太空船pi。第1 个数表示pi 可容纳的</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">人数Hpi；第2 个数表示pi 一个周期停靠的太空站个数r，1&lt;=r&lt;=n+2；随后r 个数是停靠</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">的太空站的编号(Si1,Si2,…,Sir)，地球用0 表示，月球用-1 表示。时刻0 时，所有太空船都</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">在初始站，然后开始运行。在时刻1，2，3…等正点时刻各艘太空船停靠相应的太空站。人</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">只有在0,1,2…等正点时刻才能上下太空船。</span><br/>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«结果输出:</span> 
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">程序运行结束时，将全部人员安全转移所需的时间输出到文件<span>home.out</span>中。如果问题</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">无解，则输出0。</span><br/>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入文件示例 输出文件示例</span> 
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span>home.in</span></span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 2 1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 3 0 1 2</span><br/>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 3 1 2 -1</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span>home.out</span><br/>
</span> 
</p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5</span><br/>
