# 题目描述


USACO/fence9(<b>译 by Charles.King)</b>
<div id="bodyContent">
<b></b>
<div dir="ltr" lang="zh-cn" class="mw-content-ltr">
<b></b>
<p>
<b>Electric Fences</b>电网
</p>
<hr/>
</div>
</div>
<p>
<span id=".E6.8F.8F.E8.BF.B0" class="mw-headline">描述</span> 
</p>
<p>
在本题中，格点是指横纵坐标皆为整数的点。
</p>
<p>
为了圈养他的牛，农夫约翰建造了一个三角形的电网。他从原点（0,0）牵出一根通电的电线，连接格点(n,m)（0&lt;=n&lt;32000,0&lt;m&lt;32000），再连接格点(p,0)（p&gt;0），最后回到原点。<m<32000），再连接格点(p,0)（p></m<32000），再连接格点(p,0)（p>
</p>
<p>
牛可以在不碰到电网的情况下被放到电网内部的每一个格点上（十分苗条的牛）。如果一个格点碰到了电网，牛绝对不可以被放到该格点之上。那么有多少头牛可以被放到农夫约翰的电网中去呢？
</p>
<p>
<span id=".E6.A0.BC.E5.BC.8F" class="mw-headline">格式</span> 
</p>
<p>
<b>PROGRAM NAME</b>: fence9
</p>
<p>
<b>INPUT FORMAT</b>:
</p>
<p>
(file fence9.in)
</p>
<p>
输入文件只有一行，包含三个用空格隔开的整数：n,m和p。
</p>
<p>
<b>OUTPUT FORMAT</b>:
</p>
<p>
(file fence9.out)
</p>
<p>
输出文件只有一行，包含一个整数，代表能被指定的电网包含的牛的数目。
</p>
<p>
<span id="SAMPLE_INPUT" class="mw-headline">SAMPLE INPUT </span> 
</p>
<pre>7 5 10 <span id="SAMPLE_OUTPUT" class="mw-headline"></span></pre>
<pre><span class="mw-headline">SAMPLE OUTPUT </span> 
<pre>20
</pre>
<!-- 
NewPP limit report
Preprocessor node count: 15/1000000
Post-expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
--><!-- Saved in parser cache with key newnocow:pcache:idhash:858-0!*!*!!zh-cn!*!* and timestamp 20120711023616 --></pre>
