

# 问题描述



# i,j



# i,j


<p style="text-indent:21.7500pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">如下图，矩阵<span>M</span><span>描述了一棵树。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
<img src="/upload/image/20121017/20121017090945_78539.png" alt=""/> 
</p>
<p style="text-indent:21.7500pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">树的重量是指树上所有边权之和。对于任意给出的合法矩阵<span>M</span><span>，它所能表示树的重量是惟一确定的，不可能找到两棵不同重量的树，它们都符合矩阵</span><span>M</span><span>。你的任务就是，根据给出的矩阵</span><span>M</span><span>，计算</span><span>M</span><span>所表示树的重量。下图是上面给出的矩阵</span><span>M</span><span>所能表示的一棵树，这棵树的总重量为</span><span>15</span><span>。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span><img src="/upload/image/20121017/20121017090955_40582.png" alt=""/><br/>
</span></span> 
</p>
<p style="text-align:center;">
<br/>
</p>

# 输入


<p style="text-indent:21.7500pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输入数据包含若干组数据。每组数据的第一行是一个整数<span>n</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">&lt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">n</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">&lt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">30</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">。其后<span>n</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">-</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">l<span>行，给出的是矩阵</span><span>M</span><span>的一个上三角</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">不包含对角线</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，矩阵中所有元素是不超过<span>100</span><span>的非负整数。输入数据保证合法。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输入数据以<span>n=0</span><span>结尾。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>

# 输出



# 样例


<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">weight.in</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">                         </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">weight.out</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">                                 </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">15</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5 9 12 8</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">                          </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">71</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">8 11 7</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">15 36 60</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">31 55</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">36</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<br/>
</p>
