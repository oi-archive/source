# 题目描述


<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"><span>【题目描述】</span></span><span style="font-family:Cambria;font-size:10.5000pt;"> </span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span><span style="font-family:Cambria;font-size:10.5000pt;">P</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>省刚经历一场不小的地震，所有城市之间的道路都损坏掉了，所以省长想请你将城市之间的道路重修一遍。</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span><span style="font-family:Cambria;font-size:10.5000pt;"><span>因为很多城市之间的地基都被地震破坏导致不能修公路了，所以省长给定了你一些城市对，在这些城市对之间可以修公路，并且都有相应的价格。而且因为施工队伍有限，所以省长要求用尽量少的道路将所有的城市连通起来，这样施工量就可以尽量少，道路可视为无向边，且数据保证至少有一种连通的方案。不过，省长为了表示自己的公正无私，要求在满足上述条件的情况下，选择一种方案，使得该方案中最贵道路的价格和最便宜道路的价格的差值尽量小，即使这样的方案会使总价提升很多也没关系。</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21.0000pt;">
<span style="font-family:Cambria;font-size:10.5000pt;"><span>那么，请你尽快地安排一种合理的方案，满足省长的要求。</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21.0000pt;">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"><span>【输入数据】</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span><span style="font-family:Cambria;font-size:10.5000pt;"><span>第一行两个数</span></span><span style="font-family:Cambria;font-size:10.5000pt;">N</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>，</span></span><span style="font-family:Cambria;font-size:10.5000pt;">M</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>，表示城市的个数以及可以修的公路数；</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span><span style="font-family:Cambria;font-size:10.5000pt;"><span>第二行开始</span></span><span style="font-family:Cambria;font-size:10.5000pt;">M</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>行，每行三个数</span></span><span style="font-family:Cambria;font-size:10.5000pt;">a,b,c</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>，表示</span></span><span style="font-family:Cambria;font-size:10.5000pt;">a,b</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>之间可以修一条价值</span></span><span style="font-family:Cambria;font-size:10.5000pt;">c</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>的无向道路。</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"><span>【输出数据】</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span><span style="font-family:Cambria;font-size:10.5000pt;"><span>一个数表示该方案中最大边减去最小边的值，要求要尽量的小。</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"><span>【输入样例】</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;">5 10</span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;">1 2 9384</span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;">1 3 887</span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;">1 4 2778</span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;">1 5 6916</span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;">2 3 7794</span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;">2 4 8336</span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;">2 5 5387</span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;">3 4 493</span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;">3 5 6650</span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;">4 5 1422</span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"><span>【输出样例】</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;">1686</span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"><span>【样例说明】</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"><span>选第</span></span><span style="font-family:Cambria;font-size:10.5000pt;">4</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>，</span></span><span style="font-family:Cambria;font-size:10.5000pt;">5</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>，</span></span><span style="font-family:Cambria;font-size:10.5000pt;">6</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>，</span></span><span style="font-family:Cambria;font-size:10.5000pt;">9</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>条边即可。</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"> </span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;"><span>【数据约定】</span></span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;">30%</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>数据满足</span></span><span style="font-family:Cambria;font-size:10.5000pt;">N&lt;=M&lt;=20</span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:Cambria;font-size:10.5000pt;">100%</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>数据满足</span></span><span style="font-family:Cambria;font-size:10.5000pt;">N&lt;=M&lt;=5000</span><span style="font-family:Cambria;font-size:10.5000pt;"><span>，</span></span><span style="font-family:Cambria;font-size:10.5000pt;">0&lt;c&lt;=50000;</span><span style="font-family:Cambria;font-size:10.5000pt;"></span> 
</p>
<br/>
