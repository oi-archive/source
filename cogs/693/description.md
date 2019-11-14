# 题目描述


<p style="text-indent:21pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;">如果一个自然数</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;">（</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n&gt;=1</span><span style="font-family:&#39;Microsoft YaHei&#39;;">），满足所有小于</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;">的自然数（</span><span style="font-family:&#39;Microsoft YaHei&#39;;">&gt;=1</span><span style="font-family:&#39;Microsoft YaHei&#39;;">）的约数个数都小于</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;">的约数个数，则</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;">是一个</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Antiprime</span><span style="font-family:&#39;Microsoft YaHei&#39;;">数。譬如：</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1, 2, 4, 6, 12, 24</span><span style="font-family:&#39;Microsoft YaHei&#39;;">。</span> 
</p>
<p>
<b><span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">任务：</span></b><b><span style="font-size:12pt;"></span></b> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;">编一个程序：</span> 
</p>
<p style="text-indent:-18pt;margin-left:18pt;">
<span><span><span style="font-family:Microsoft YaHei;">1、</span><span> </span></span></span><span style="font-family:&#39;Microsoft YaHei&#39;;">从</span><span style="font-family:&#39;Microsoft YaHei&#39;;">ANT.IN</span><span style="font-family:&#39;Microsoft YaHei&#39;;">中读入自然数</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;">。</span> 
</p>
<p style="text-indent:-18pt;margin-left:18pt;">
<span><span><span style="font-family:Microsoft YaHei;">2、</span><span> </span></span></span><span style="font-family:&#39;Microsoft YaHei&#39;;">计算不大于</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;">的最大</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Antiprime</span><span style="font-family:&#39;Microsoft YaHei&#39;;">数。</span> 
</p>
<p style="text-indent:-18pt;margin-left:18pt;">
<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;"><span style="font-family:&#39;Microsoft YaHei&#39;;">3、</span></span><span style="font-family:&#39;Microsoft YaHei&#39;;">将结果输出到</span><span style="font-family:&#39;Microsoft YaHei&#39;;">ANT.OUT</span><span style="font-family:&#39;Microsoft YaHei&#39;;">中。</span><span style="font-size:12pt;"></span> 
</p>
<p>
<span style="font-size:12pt;"></span> 
</p>
<p>
<b><span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">输入</span></b><b><span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">( </span><span style="font-family:&#39;Microsoft YaHei&#39;;">antip.in)</span></b><b><span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">：</span></b><b><span style="font-size:12pt;"></span></b> 
</p>
<p style="text-indent:21pt;">
<span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">输入文件</span><span style="font-family:&#39;Microsoft YaHei&#39;;">antip.in</span></span><span style="font-family:&#39;Microsoft YaHei&#39;;">只有一个整数，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;">（</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1 &lt;= n &lt;= 2 000 000 000</span><span style="font-family:&#39;Microsoft YaHei&#39;;">）。</span> 
</p>
<p>
<span style="font-size:12pt;"></span> 
</p>
<p>
<b><span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">输出</span></b><b><span style="font-size:12pt;"><span style="font-family:Microsoft YaHei;">(</span><span style="font-family:&#39;Microsoft YaHei&#39;;">antip.out</span></span><span style="font-family:&#39;Microsoft YaHei&#39;;">):</span></b><b><span style="font-size:12pt;"></span></b> 
</p>
<p style="text-indent:21pt;">
<span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">输出文件</span><span style="font-family:&#39;Microsoft YaHei&#39;;">antip.out</span></span><span style="font-family:&#39;Microsoft YaHei&#39;;">也只包含一个整数，即不大于</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;">的最大</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Antiprime</span><span style="font-family:&#39;Microsoft YaHei&#39;;">数。</span> 
</p>
<p>
<span style="font-size:12pt;"></span> 
</p>
<p>
<b><span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">样例输入</span></b><b><span style="font-size:12pt;"><span style="font-family:Microsoft YaHei;">( </span><span style="font-family:&#39;Microsoft YaHei&#39;;">antip.in</span></span><span style="font-family:&#39;Microsoft YaHei&#39;;">)</span></b><b><span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">:</span></b> 
</p>
<p style="text-indent:12pt;">
<span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">1000</span> 
</p>
<p>
<span style="font-size:12pt;"></span> 
</p>
<p>
<b><span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">样例输出</span></b><b><span style="font-size:12pt;"><span style="font-family:Microsoft YaHei;">(</span><span style="font-family:&#39;Microsoft YaHei&#39;;">antip.out</span></span><span style="font-family:&#39;Microsoft YaHei&#39;;">)</span></b><b><span style="font-size:12pt;font-family:&#39;Microsoft YaHei&#39;;">：</span></b><b><span style="font-size:12pt;"></span></b> 
</p>
<p style="text-indent:10.5pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;">840</span> 
</p>
