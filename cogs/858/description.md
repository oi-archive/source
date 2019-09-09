# 题目描述


<p>
<span style="color:#000000;font-weight:bold;font-size:12pt;font-family:Microsoft YaHei;">【</span><span style="color:#000000;font-weight:bold;font-size:12pt;font-family:Microsoft YaHei;">题目描述</span><span style="color:#000000;font-weight:bold;font-size:12pt;font-family:Microsoft YaHei;">】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">有N块编号为1~N的特殊磁石相互吸附组成一条磁性链，只有它们紧挨着时才会传递吸力，他们之间的吸力很大，如果我们要从N块相连的磁石中取出一块，那么需要消耗N-1个单位的能量，空缺处不再有吸力传递，空出的位置也不会再被吸到一起。现在我们要取出Q块磁石，并且给出它们的编号，问最少要消耗多少单位的能量？</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="color:#000000;font-weight:bold;font-size:12pt;font-family:Microsoft YaHei;">【输人格式】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">    第一行两个数</span><span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">N</span><span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">和Q，Q表示</span><span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">要取走的磁石</span><span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">数；</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">    第二行Q个数，表示要</span><span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">取走哪些编号的磁石</span><span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">。</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="color:#000000;font-weight:bold;font-size:12pt;font-family:Microsoft YaHei;">【输出格式】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">    仅一行，表示最少</span><span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">消耗的能量</span><span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">。</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="color:#000000;font-weight:bold;font-size:12pt;font-family:Microsoft YaHei;">【输入样例】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">    20 3</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">    3 6 14</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="color:#000000;font-weight:bold;font-size:12pt;font-family:Microsoft YaHei;">【输出样例】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">    35</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="color:#000000;font-weight:bold;font-size:12pt;font-family:Microsoft YaHei;">【</span><span style="color:#000000;font-weight:bold;font-size:12pt;font-family:Microsoft YaHei;">数据规模</span><span style="color:#000000;font-weight:bold;font-size:12pt;font-family:Microsoft YaHei;">】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">Q≤</span><span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">N</span><span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">；</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">50％的数据l≤</span><span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">N</span><span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">≤100；1≤Q≤5。</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">10</span><span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">0％的数据l≤</span><span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">N</span><span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">≤1</span><span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">0</span><span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">00；1≤Q≤</span><span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">100</span><span style="color:#000000;font-size:12pt;font-family:Microsoft YaHei;">。</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
