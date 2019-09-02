

# a_i,b_i


<p style="text-indent:21pt;">
	<span style="font-family:Microsoft YaHei;">激光器附带了</span><span style="font-family: ;" yahei?;?="" microsoft="">9</span><span style="font-family:Microsoft YaHei;">个发射匣，代表</span><span style="font-family: ;" yahei?;?="" microsoft="">1~9</span><span style="font-family:Microsoft YaHei;">这</span><span style="font-family: ;" yahei?;?="" microsoft="">9</span><span style="font-family:Microsoft YaHei;">个数字。只有把同一个等价类的数字对应的发射匣安置在一排上，Xenon Laser - k才能够启动。给定</span>$N$<span style="font-family:Microsoft YaHei;">个波段，现在就请你求出</span><span style="font-family: ;" yahei?;?="" microsoft="">1~9</span><span style="font-family:Microsoft YaHei;">这</span><span style="font-family: ;" yahei?;?="" microsoft="">9</span><span style="font-family:Microsoft YaHei;">个数字分成了哪些等价类，并且每行输出一个等价类。</span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:Microsoft YaHei;">本题描述比较抽象，请参考样例解释。</span><span></span> 
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;">输入格式</span><span></span></b> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:Microsoft YaHei;">第一行两个整数</span>$N$<span style="font-family:Microsoft YaHei;">,</span>$k$<span style="font-family:Microsoft YaHei;">。</span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:Microsoft YaHei;">接下来</span>$N$<span style="font-family:Microsoft YaHei;">行每行两个整数 $</span>a_i,b_i$ <span>, $</span><span style="font-family:Microsoft YaHei;">a_i,b_i$</span><span style="font-family:Microsoft YaHei;">为正整数，满足<span style="font-family: ;" yahei?;?="" microsoft="">$b_{i-1} &lt; a_i &lt; b_i$</span></span><span style="font-family:Microsoft YaHei;">。</span> 
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;"><span></span>输出格式</span><span></span></b> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:Microsoft YaHei;">每行一个</span>$k$<span style="font-family:Microsoft YaHei;">等价类，各行之内都按照数字从小到大排序，数字中间没有空格，行与行之间按照等价类中最小的数字从小到大排序。具体格式参考样例。</span> 
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;">样例输入</span><span style="font-family: ;" yahei?;?="" microsoft="">1</span></b> 
</p>
<pre><span style="font-family:;font-size:12pt;">1 1</span></pre>
<pre><span style="font-family:;font-size:12pt;">1 566</span></pre>
<b><br/>
</b> 
<p>
	<b><span style="font-family:Microsoft YaHei;">样例输出</span><span style="font-family: ;" yahei?;?="" microsoft="">1</span></b> 
</p>
<pre><span style="font-family:;font-size:12pt;">123456</span></pre>
<pre><span style="font-family:;font-size:12pt;">789</span></pre>
<p>
	<b><span style="font-family:Microsoft YaHei;">样例输入</span><span style="font-family: ;" yahei?;?="" microsoft="">2</span></b> 
</p>
<pre><span style="font-family:;font-size:12pt;">1 2</span></pre>
<pre><span style="font-family:;font-size:12pt;">30 75</span></pre>
<p>
	<b><span style="font-family:Microsoft YaHei;">样例输出</span><span style="font-family: ;" yahei?;?="" microsoft="">2</span></b> 
</p>
<pre><span style="font-family:;font-size:12pt;">12</span></pre>
<pre><span style="font-family:;font-size:12pt;">345</span></pre>
<pre><span style="font-family:;font-size:12pt;">6</span></pre>
<pre><span style="font-family:;font-size:12pt;">7</span></pre>
<pre><span style="font-family:;font-size:12pt;">89</span></pre>
<p>
	<b><span style="font-family:Microsoft YaHei;">样例说明</span><span></span></b> 
</p>
<p style="text-align:left;text-indent:21pt;" align="left">
	<span style="font-family:Microsoft YaHei;">第一个样例中</span>$k=1$<span style="font-family:Microsoft YaHei;">，只允许修改个位。对于</span><span style="font-family: ;" yahei?;?="" microsoft="">1~559</span><span style="font-family:Microsoft YaHei;">这些数，个位无论如何修改都在波段内。对于</span><span style="font-family: ;" yahei?;?="" microsoft="">560~566</span><span style="font-family:Microsoft YaHei;">这些数，个位修改为大于等于</span><span style="font-family: ;" yahei?;?="" microsoft="">7</span><span style="font-family:Microsoft YaHei;">的数字时（例如</span><span style="font-family: ;" yahei?;?="" microsoft="">562</span><span style="font-family:Microsoft YaHei;">的</span><span style="font-family: ;" yahei?;?="" microsoft="">2</span><span style="font-family:Microsoft YaHei;">修改为</span><span style="font-family: ;" yahei?;?="" microsoft="">8</span><span style="font-family:Microsoft YaHei;">），就不在波段内了。因此</span><span style="font-family: ;" yahei?;?="" microsoft="">1~6</span><span style="font-family:Microsoft YaHei;">和</span><span style="font-family: ;" yahei?;?="" microsoft="">7~9</span><span style="font-family:Microsoft YaHei;">属于不同的等价类。</span> 
</p>
<p style="text-align:left;text-indent:21pt;" align="left">
	<span style="font-family:Microsoft YaHei;">第二个样例每一位上都可以修改。修改方法与上面一个样例类似。</span><span></span> 
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;">数据范围与约定</span><span></span></b> 
</p>
<p style="text-align:left;text-indent:21pt;" align="left">
	<span style="font-family:Microsoft YaHei;">对于</span><span style="font-family: ;" yahei?;?="" microsoft="">25% </span><span style="font-family:Microsoft YaHei;">的数据，</span>$1 \le n \le 50 $<span style="font-family:Microsoft YaHei;">，</span>$1 \le a_i \le b_i \le 6000 $<span style="font-family:Microsoft YaHei;">。</span> 
</p>
<p style="text-align:left;text-indent:21pt;" align="left">
	<span style="font-family:Microsoft YaHei;">对于另</span><span style="font-family: ;" yahei?;?="" microsoft="">25% </span><span style="font-family:Microsoft YaHei;">的数据，</span>$n=1$<span style="font-family:Microsoft YaHei;">。</span> 
</p>
<p style="text-align:left;text-indent:21pt;" align="left">
	<span style="font-family:Microsoft YaHei;">对于另</span><span style="font-family: ;" yahei?;?="" microsoft="">30% </span><span style="font-family:Microsoft YaHei;">的数据，</span>$k=1$<span style="font-family:Microsoft YaHei;">。</span> 
</p>
<p style="text-align:left;text-indent:21pt;" align="left">
	<span style="font-family:Microsoft YaHei;">对于</span><span style="font-family: ;" yahei?;?="" microsoft="">100% </span><span style="font-family:Microsoft YaHei;">的数据，</span>$1 \le n \le 10000 , 1 \le k \le 19 , 1 \le a_i \le b_i \le 10^{18} $<span style="font-family:Microsoft YaHei;">。</span> 
</p>
<p style="text-align:left;text-indent:21pt;" align="left">
	<span style="font-family:Microsoft YaHei;">在所有的数据中，均匀分布着</span><span style="font-family: ;" yahei?;?="" microsoft="">25% </span><span style="font-family:Microsoft YaHei;">的随机数据。<span></span></span><span></span><span></span> 
</p>
