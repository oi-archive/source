# 题目描述


USACO/range
<div id="bodyContent">
<div dir="ltr" lang="zh-cn" class="mw-content-ltr">
<p>
<b>Home on the Range</b> 家的范围
</p>
<p>
译 by tim green
</p>
<hr/>
</div>
</div>
<span id=".E6.8F.8F.E8.BF.B0" class="mw-headline">描述</span> 
<p>
农民约翰在一片边长是N (2 &lt;= N &lt;= 250)英里的正方形牧场上放牧他的奶牛。(因为一些原因，他的奶牛只在正方形的牧场上吃草。)遗憾的是,他的奶牛已经毁坏一些土地。( 一些1平方英里的正方形)
</p>
<p>
农民约翰需要统计那些可以放牧奶牛的正方形牧场(至少是2x2的,在这些较大的正方形中没有一个点是被破坏的，也就是说，所有的点都是“1”)。
</p>
<p>
你的工作要在被供应的数据组里面统计所有不同的正方形放牧区域(&gt;=2x2)的个数。当然，放牧区域可能是重叠。
</p>
<span id=".E6.A0.BC.E5.BC.8F" class="mw-headline">格式</span> 
<p>
<b>PROGRAM NAME</b>: range
</p>
<p>
<b>INPUT FORMAT</b>:
</p>
<p>
(file range.in)
</p>
<p>
第 1 行:N,牧区的边长。
</p>
<p>
第 2 到　n+1行:N个没有空格分开的字符。
</p>
<p>
0 表示 &#34;那一个区段被毁坏了&#34;;1 表示 &#34; 准备好被吃&#34;。
</p>
<p>
<b>OUTPUT FORMAT</b>:
</p>
<p>
(file range.out)
</p>
<p>
按边长从小到大输出那些存在的正方形的边长和个数，一种一行。
</p>
<span id="SAMPLE_INPUT" class="mw-headline">SAMPLE INPUT </span> 
<pre>6
101111
001111
111111
001111
101101
111001
</pre>
<span id="SAMPLE_OUTPUT" class="mw-headline">SAMPLE OUTPUT </span> 
<pre>2 10
3 4
4 1
</pre>
<!-- NewPP limit report Preprocessor node count: 15/1000000 Post-expand include size: 0/2097152 bytes Template argument size: 0/2097152 bytes Expensive parser function count: 0/100 --><!-- Saved in parser cache with key newnocow:pcache:idhash:854-0!*!*!!zh-cn!*!* and timestamp 20120711015628 -->
<p>
 
</p>
