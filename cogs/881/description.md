# 题目描述


USACO/nuggets(<b>译 by ragazza gatti)
</b><div id="bodyContent"><b>
	</b><div dir="ltr" lang="zh-cn" class="mw-content-ltr"><b>
		</b><p><b>
			Beef McNuggets</b>麦香牛块
		</p>
		<hr/>
	</div>
</div>
<p>
	<span id=".E6.8F.8F.E8.BF.B0" class="mw-headline">描述</span> 
</p>
<p>
	农夫布朗的奶牛们正在进行斗争，因为它们听说麦当劳正在考虑引进一种新产品：麦香牛块。奶牛们正在想尽一切办法让这种可怕的设想泡汤。奶牛们进行斗争的策略之一是“劣质的包装”。“看，”奶牛们说，“如果你只用一次能装3块、6块或者10块的三种包装盒包装麦香牛块，你就不可能满足一次只想买1、2、4、5、7、8、11、14或者17块麦香牛块的顾客了。劣质的包装意味着劣质的产品。”
</p>
<p>
	你的任务是帮助这些奶牛。给出包装盒的种类数N(1&lt;=N&lt;=10)和N个代表不同种类包装盒容纳麦香牛块个数的正整数(1&lt;=i&lt;=256)，输出顾客不能用上述包装盒(每种盒子数量无限)买到麦香牛块的最大块数。如果所有购买方案都能得到满足或者不存在不能买到块数的上限，则输出0。不能买到的最大块数（倘它存在）不超过2,000,000,000。
</p>
<p>
	<span id=".E6.A0.BC.E5.BC.8F" class="mw-headline">格式</span> 
</p>
<p>
	<b>PROGRAM NAME</b>: nuggets
</p>
<p>
	<b>INPUT FORMAT</b>:
</p>
<p>
	(file nuggets.in)
</p>
<p>
	第1行: 包装盒的种类数N
</p>
<p>
	第2行到N+1行: 每个种类包装盒容纳麦香牛块的个数
</p>
<p>
	<b>OUTPUT FORMAT</b>:
</p>
<p>
	(file nuggets.out)
</p>
<p>
	输出文件只有一行数字：顾客不能用包装盒买到麦香牛块的最大块数或0(如果所有购买方案都能得到满足或者顾客不能买到的块数没有上限)。
</p>
<p>
	<span id="SAMPLE_INPUT" class="mw-headline">SAMPLE INPUT </span>
</p>
<pre>3
3
6
10 <span id="SAMPLE_OUTPUT" class="mw-headline"></span></pre>
<pre><span class="mw-headline">SAMPLE OUTPUT </span> 
<pre>17
</pre>
<!-- 
NewPP limit report
Preprocessor node count: 15/1000000
Post-expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
--><!-- Saved in parser cache with key newnocow:pcache:idhash:873-0!*!*!!zh-cn!*!* and timestamp 20120711063433 --></pre>
