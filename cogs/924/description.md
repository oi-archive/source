# 题目描述


<p>
<br/>
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">问题描述：</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">一位信使来到一个村落送信，他的送信方式是从某户<span>A</span><span>出发直接到达某户</span><span>B</span><span>（</span><span>A</span><span>≠</span><span>B</span><span>）。这个村落中共有</span><span>n</span><span>户村民，第</span><span>i(1</span><span>≤</span><span>i</span><span>≤</span><span>n)</span><span>户村民可以用一个二元坐标</span><span>(xi,yi)</span><span>来表示其位置。信使刚刚拿到了村落的地图，但还不知道具体的任务细节，因此他想请你帮他算一下他送一次信可能走的最长距离，同时为了安慰信使，请你把最短距离也告诉他。<br/>
<br/>
</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输入格式：</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输入文件共有<span>n+1</span><span>行：</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第一行是一个整数<span>n</span><span>，表示村落中共有</span><span>n</span><span>户村民。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第<span>2</span><span>到第</span><span>n+1</span><span>行每行两个整数</span><span>xi</span><span>和</span><span>yi</span><span>，表示第</span><span>i</span><span>户村民的坐标。<br/>
<br/>
</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输出格式：</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输出文件共两行，每行一个实数，分别表示信使所可能走的最长距离和最短距离。与标准输出相差小于<span>0.001</span><span>的输出都被认为是正确的。两问分别计分，每答对一问得</span><span>5</span><span>分。<br/>
<br/>
</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输入样例<span>(</span></span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">postman</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">b.in)<span>：</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0 0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3 0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0 4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3 4<br/>
<br/>
</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输出样例<span>(</span></span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">postman</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">b.out)<span>：</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5.0000</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3.0000<br/>
<br/>
样例解释：信使可能走的最长距离是(0,0)-&gt;(3,4)，长度为5；最短距离是(0,0)-&gt;(3,0)，长度为3。<br/>
<br/>
</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">数据规模：</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">30%<span>的数据满足</span><span>n</span><span>≤5</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">000<span>。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">100%<span>的数据满足</span><span>n</span><span>≤</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">10</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0000, -1000000<span>≤</span><span>xi, yi</span><span>≤</span><span>1000000</span><span>。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<br/>
</p>
