# 题目描述


<p>
<span style="font-size:12pt;">对于一个数列</span><span style="font-size:12pt;">{a<sub>i</sub>}</span><span style="font-size:12pt;">，如果有</span><span style="font-size:12pt;">i&lt;j</span><span style="font-size:12pt;">且</span><span style="font-size:12pt;">a<sub>i</sub>&gt;a<sub>j</sub></span><span style="font-size:12pt;">，那么我们称</span><span style="font-size:12pt;">a<sub>i</sub></span><span style="font-size:12pt;">与</span><span style="font-size:12pt;">a<sub>j</sub></span><span style="font-size:12pt;">为一对逆序对数。若对于任意一个由</span><span style="font-size:12pt;">1~n</span><span style="font-size:12pt;">自然数组成的数列，可以很容易求出有多少个逆序对数。那么逆序对数为</span><span style="font-size:12pt;">k</span><span style="font-size:12pt;">的这样自然数数列到底有多少个？</span> 
</p>
<div style="text-indent:21.75pt;">
 
</div>
<div>
<b><span style="font-size:14pt;">输入数据</span></b> 
</div>
<div style="text-indent:24pt;">
<span style="font-size:12pt;">第一行为两个整数</span><span style="font-size:12pt;">n</span><span style="font-size:12pt;">，</span><span style="font-size:12pt;">k</span><span style="font-size:12pt;">。</span> 
</div>
<div style="text-indent:24pt;">
 
</div>
<div>
<b><span style="font-size:14pt;">输出数据</span></b><b><span style="font-size:12pt;">                </span></b> 
</div>
<div style="text-indent:24pt;">
<span style="font-size:12pt;">写入一个整数，表示符合条件的数列个数，</span><span style="font-size:12pt;">由于这个数可能很大，你只需输出该数对</span><span style="font-size:12pt;">10000</span><span style="font-size:12pt;">求余数后的结果。</span> 
</div>
<div style="text-indent:24pt;">
 
</div>
<div>
<b><span style="font-size:14pt;">样例输入</span></b> 
</div>
<div>
<b><span style="font-size:12pt;">  </span></b><span style="font-size:12pt;">4 1</span> 
</div>
<div style="text-indent:24pt;">
 
</div>
<div>
<b><span style="font-size:14pt;">样例输出</span></b> 
</div>
<div style="text-indent:24pt;">
<span style="font-size:12pt;">3</span> 
</div>
<div>
<b><span style="font-size:14pt;">样例说明：</span></b> 
</div>
<div style="text-indent:24pt;">
<span style="font-size:12pt;">下列</span><span style="font-size:12pt;">3</span><span style="font-size:12pt;">个数列逆序对数都为</span><span style="font-size:12pt;">1</span><span style="font-size:12pt;">；分别是</span><span style="font-size:12pt;">1 2 4 3 </span><span style="font-size:12pt;">；</span><span style="font-size:12pt;">1 3 2 4 </span><span style="font-size:12pt;">；</span><span style="font-size:12pt;">2 1 3 4</span><span style="font-size:12pt;">；</span> 
</div>
<div style="text-indent:24pt;">
 
</div>
<div>
<b><span style="font-size:14pt;">测试数据范围</span></b> 
</div>
<div style="text-indent:24pt;">
<span style="font-size:12pt;">30%</span><span style="font-size:12pt;">的数据</span><span style="font-size:12pt;"> n&lt;=12</span> 
</div>
<div style="text-indent:24pt;">
<span style="font-size:12pt;">100%</span><span style="font-size:12pt;">的数据</span><span style="font-size:12pt;"> n&lt;=1000</span><span style="font-size:12pt;">，</span><span style="font-size:12pt;">k&lt;=1000</span> 
</div>
