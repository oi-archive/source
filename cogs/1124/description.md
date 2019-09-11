# 题目描述


<h3>
【题目描述】
</h3>
<p>
<span style="font-size:10.5pt;font-family:宋体;color:#323E32;"><span style="font-size:14.166666030883789px;line-height:23.999998092651367px;">设G为有n个顶点的有向无环图，G中各顶点的编号为1到n，且当<i，j>为G中的一条边时有i &lt; j。设w（i，j）为边<i，j>的长度，请设计算法，计算图G中&lt;1，n&gt;间的最长路径。</i，j></i，j></span><br/>
</span><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><i< span=""><span style="font-size:10.5pt;font-family:宋体;color:#323E32;"></span><span style="font-size:10.5pt;font-family:" color:#323e32;"=""></span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;"></span><span style="font-size:10.5pt;font-family:" color:#323e32;"=""></span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;"></span><span style="font-size:10.5pt;font-family:" color:#323e32;"=""></span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;"></span><span style="font-size:10.5pt;font-family:" color:#323e32;"=""></span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;"></span><span style="font-size:10.5pt;font-family:" color:#323e32;"=""></span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;"></span><span style="font-size:10.5pt;font-family:" color:#323e32;"=""></span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;"></span><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><i< span=""><span style="font-size:10.5pt;font-family:宋体;color:#323E32;"></span><span style="font-size:10.5pt;font-family:" color:#323e32;"=""></span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;"></span><span style="font-size:10.5pt;font-family:" color:#323e32;"=""></span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;"></span><span style="font-size:10.5pt;font-family:" color:#323e32;"=""></span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;"></span><span style="font-size:10.5pt;font-family:" color:#323e32;"=""></span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;"></span> </i<></span></i<></span> 
</p>
<h3>
【输入格式】
</h3>
<p>
<span style="font-size:10.5pt;font-family:宋体;color:#323E32;">输入文件</span><span style="font-size:10.5pt;font-family:" color:#323e32;"="">longest.in</span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;">的第一行有两个整数</span><span style="font-size:10.5pt;font-family:" color:#323e32;"="">n</span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;">和</span><span style="font-size:10.5pt;font-family:" color:#323e32;"="">m,</span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;">表示有</span><span style="font-size:10.5pt;font-family:" color:#323e32;"="">n</span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;">个顶点和</span><span style="font-size:10.5pt;font-family:" color:#323e32;"="">m</span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;">条边，接下来</span><span style="font-size:10.5pt;font-family:" color:#323e32;"="">m</span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;">行中每行输入</span><span style="font-size:10.5pt;font-family:" color:#323e32;"="">3</span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;">个整数</span><span style="font-size:10.5pt;font-family:" color:#323e32;"="">a</span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;">，</span><span style="font-size:10.5pt;font-family:" color:#323e32;"="">b</span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;">，</span><span style="font-size:10.5pt;font-family:" color:#323e32;"="">v</span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;">（表示从</span><span style="font-size:10.5pt;font-family:" color:#323e32;"="">a</span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;">点到</span><span style="font-size:10.5pt;font-family:" color:#323e32;"="">b</span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;">点有条边，边的长度为</span><span style="font-size:10.5pt;font-family:" color:#323e32;"="">v</span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;">）。</span> 
</p>
<h3>
【输出格式】
</h3>
<p>
<span style="font-size:10.5pt;font-family:宋体;color:#323E32;">输出文件</span><span style="font-size:10.5pt;font-family:" color:#323e32;"="">longest.out</span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;">，一个整数，即</span><span style="font-size:10.5pt;font-family:" color:#323e32;"="">1</span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;">到</span><span style="font-size:10.5pt;font-family:" color:#323e32;"="">n</span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;">之间的最长路径</span><span style="font-size:10.5pt;font-family:" color:#323e32;"="">.</span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;">如果</span><span style="font-size:10.5pt;font-family:" color:#323e32;"="">1</span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;">到</span><span style="font-size:10.5pt;font-family:" color:#323e32;"="">n</span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;">之间没连通，输出</span><span style="font-size:10.5pt;font-family:" color:#323e32;"="">-1</span><span style="font-size:10.5pt;font-family:宋体;color:#323E32;">。</span> 
</p>
<h3>
【样例输入】
</h3>
<pre>2 1
1 2 1
</pre>
<h3>
【样例输出】
</h3>
<pre>1
</pre>
<span style="color:#323E32;">说明：若输入样例为<span>2 0</span>，则输出为<span>-1</span>。<span></span></span> 
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
<span style="color:#323E32;">20%</span><span style="color:#323E32;">的数据，<span>n≤100</span>　，<span>m≤1000</span></span> 
</p>
<p>
<span style="color:#323E32;">40%</span><span style="color:#323E32;">的数据，<span>n≤1,000</span>　，<span>m≤10000</span></span> 
</p>
<p>
<span style="color:#323E32;">100%</span><span style="color:#323E32;">的数据，<span>n≤1,500</span>　，<span>m≤50000</span>，最长路径不大于<span>10^9</span></span> 
</p>
<p>
<br/>
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【来源】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">冲刺</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">NOIP2010</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">模拟试题与解析（七）</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（提高组复赛）</span> 
</p>
<p>
<br/>
</p>
