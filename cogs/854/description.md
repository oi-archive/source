# 题目描述


<p align="center" style="text-align:center;">
	<b><span style="font-size:14.0pt;font-family:宋体;"><span style="font-family:Microsoft YaHei;">题</span><span style="font-family:&#39;Microsoft YaHei&#39;;">4  </span></span></b><b><span style="font-size:14.0pt;font-family:宋体;"><span style="font-family:Microsoft YaHei;">新版方格取数</span><span></span></span></b>
</p>
<p>
	<b><span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">【问题描述】</span><span></span></span></b>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">T</span><span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">博士的小儿子小</span><span style="font-family:&#39;Microsoft YaHei&#39;;">T</span><span style="font-family:Microsoft YaHei;">最近在玩一个游戏。</span><span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">在一个</span><span style="font-family:&#39;Microsoft YaHei&#39;;">m</span><span style="font-family:Microsoft YaHei;">行</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:Microsoft YaHei;">列的方格中有</span><span style="font-family:&#39;Microsoft YaHei&#39;;">m*n</span><span style="font-family:Microsoft YaHei;">个数，游戏规则如下：</span><span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">先在方格边缘取走一个数，以此格为起点，下一步可向该格四个方向中未取数的方格前进，取走该方格的数并继续按如上规则取数。</span><span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">如果某次取数恰好取到方格的边缘，则下一步可选择离开方格另取入口进入方格，当然也可以选择按上述规则取数。</span><span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">游戏在小</span><span style="font-family:&#39;Microsoft YaHei&#39;;">T</span><span style="font-family:Microsoft YaHei;">取完方格内所有数或无法继续取方格内剩下的任何一个数的时候结束。</span><span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">游戏有这样的得分规则：若方格内的某数</span><span style="font-family:&#39;Microsoft YaHei&#39;;">j</span><span style="font-family:Microsoft YaHei;">是方格内所有数中第</span><span style="font-family:&#39;Microsoft YaHei&#39;;">i</span><span style="font-family:Microsoft YaHei;">个取走的数，此次取数的得分为</span><span style="font-family:&#39;Microsoft YaHei&#39;;">i*j</span><span style="font-family:Microsoft YaHei;">。</span><span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">小</span><span style="font-family:&#39;Microsoft YaHei&#39;;">T</span><span style="font-family:Microsoft YaHei;">最后的得分为游戏结束时他各次取数的得分之和。</span><span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">小</span><span style="font-family:&#39;Microsoft YaHei&#39;;">T</span><span style="font-family:Microsoft YaHei;">想知道他所能取得的最大得分。</span><span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">注意：已经取走数的方格不能再次取数或经过。</span><span></span></span>
</p>
<p>
	<b><span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">【输入格式】</span><span></span></span></b>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">输入文件</span><span style="font-family:&#39;Microsoft YaHei&#39;;">newfgqs.in</span><span style="font-family:Microsoft YaHei;">的第一行是两个正整数</span><span style="font-family:&#39;Microsoft YaHei&#39;;">m</span><span style="font-family:Microsoft YaHei;">和</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:Microsoft YaHei;">，表示方格为</span><span style="font-family:&#39;Microsoft YaHei&#39;;">m</span><span style="font-family:Microsoft YaHei;">行</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:Microsoft YaHei;">列。</span><span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">第</span><span style="font-family:&#39;Microsoft YaHei&#39;;">2</span><span style="font-family:Microsoft YaHei;">到</span><span style="font-family:&#39;Microsoft YaHei&#39;;">m+1</span><span style="font-family:Microsoft YaHei;">行，每行为</span><span style="font-family:&#39;Microsoft YaHei&#39;;">n</span><span style="font-family:Microsoft YaHei;">个非负整数（注意可能为</span><span style="font-family:&#39;Microsoft YaHei&#39;;">0</span><span style="font-family:Microsoft YaHei;">），是方格里的数，保证这些数都小于</span><span style="font-family:&#39;Microsoft YaHei&#39;;">100000</span><span style="font-family:Microsoft YaHei;">（</span><span style="font-family:&#39;Microsoft YaHei&#39;;">10</span><span style="font-family:Microsoft YaHei;">万）。</span><span></span></span>
</p>
<p>
	<b><span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">【输出格式】</span><span></span></span></b>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">输出文件为</span><span style="font-family:&#39;Microsoft YaHei&#39;;">newfgqs.out</span><span style="font-family:Microsoft YaHei;">。</span><span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">只要输出一行，为小</span><span style="font-family:&#39;Microsoft YaHei&#39;;">T</span><span style="font-family:Microsoft YaHei;">能取得的最大得分。</span><span></span></span>
</p>
<p>
	<b><span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">【样例输入</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:Microsoft YaHei;">】</span><span></span></span></b>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">3 3</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">1 2 3</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">8 9 4</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">7 6 5</span>
</p>
<p>
	<b><span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">【样例输出</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:Microsoft YaHei;">】</span><span></span></span></b>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">285   </span><span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">（依次取</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1,2,3,4,5,6,7,8,9</span><span style="font-family:Microsoft YaHei;">）</span><span></span></span>
</p>
<p>
	<b><span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">【样例输入</span><span style="font-family:&#39;Microsoft YaHei&#39;;">2</span><span style="font-family:Microsoft YaHei;">】</span><span></span></span></b>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">3 3</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">0 0 0</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">0 1 0</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">0 0 0</span>
</p>
<p>
	<b><span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">【样例输出</span><span style="font-family:&#39;Microsoft YaHei&#39;;">2</span><span style="font-family:Microsoft YaHei;">】</span><span></span></span></b>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">9     </span><span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">（周围绕一圈，第</span><span style="font-family:&#39;Microsoft YaHei&#39;;">9</span><span style="font-family:Microsoft YaHei;">次取</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:Microsoft YaHei;">）</span><span></span></span>
</p>
<p>
	<b><span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">【数据范围】</span><span></span></span></b>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">对于</span><span style="font-family:&#39;Microsoft YaHei&#39;;">50%</span><span style="font-family:Microsoft YaHei;">的数据，满足</span><span style="font-family:&#39;Microsoft YaHei&#39;;">m*n&lt;=9</span><span style="font-family:Microsoft YaHei;">。</span><span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;">对于</span><span style="font-family:&#39;Microsoft YaHei&#39;;">100%</span><span style="font-family:Microsoft YaHei;">的数据，满足</span><span style="font-family:&#39;Microsoft YaHei&#39;;">m*n&lt;=16</span><span style="font-family:Microsoft YaHei;">。</span><span></span></span>
</p>
