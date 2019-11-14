# 题目描述


<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目描述】</span> 
</h3>
<p>
	<span style="color:#323E32;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">翻转游戏是在一个</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">4</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">格</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">×4</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">格的长方形上进行的，在长方形的</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">16</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">个格上每个格子都放着一个双面的物件。每个物件的两个面，一面是白色，另一面是黑色，每个物件要么白色朝上，要么黑色朝上，每一轮你只能翻</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">至</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">个物件，从而由黑到白的改变这些物件上面的颜色，反之亦然。每一轮被选择翻转的物件遵循以下规则：</span><span></span></span> 
</p>
<p>
	<span style="color:#323E32;font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1</span><span style="color:#323E32;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">、从</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">16</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">个物件中任选一个。</span><span></span></span> 
</p>
<p>
	<span style="color:#323E32;font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span><span style="color:#323E32;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">、翻转所选择的物件的同时，所有与它相邻的左方物件、右方物件、上方物件和下方物件</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">(</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">如果有的话</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">)</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，都要跟着翻转。</span><span></span></span> 
</p>
<p>
	<span style="color:#323E32;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">　　以下为例：</span><span></span></span> 
</p>
<p>
	<span style="color:#323E32;font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">     bwbw</span> 
</p>
<p>
	<span style="color:#323E32;font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">     wwww</span> 
</p>
<p>
	<span style="color:#323E32;font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">     bbwb</span> 
</p>
<p>
	<span style="color:#323E32;font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">     bwwb</span> 
</p>
<p>
	<span style="color:#323E32;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">　　这里</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">&#34;b&#34;</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">表示该格子放的物件黑色面朝上、</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">&#34;w&#34;</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">表示该格子放的物件白色朝上。如果我们选择翻转第三行的第一个物件，那么格子状态将变为：</span><span></span></span> 
</p>
<p>
	<span style="color:#323E32;font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">     bwbw</span> 
</p>
<p>
	<span style="color:#323E32;font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">     bwww</span> 
</p>
<p>
	<span style="color:#323E32;font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">     wwwb</span> 
</p>
<p>
	<span style="color:#323E32;font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">     wwwb</span> 
</p>
<p>
	<span style="color:#323E32;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">　　游戏的目标是翻转到所有的物件白色朝上或黑色朝上。你的任务就是写一个程序来求最</span><span></span></span> 
</p>
<p>
	<span style="color:#323E32;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">少的翻转次数来实现这一目标。</span><span></span></span> 
</p>
<p>
	<br/>
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式】</span> 
</h3>
<p>
	<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;color:#323E32;">输入文件</span><span style="font-size: 16px; font-family: &#39;Microsoft YaHei&#39;; " color:#323e32;"="">flip.in</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;color:#323E32;">包含</span><span style="font-size: 16px; font-family: &#39;Microsoft YaHei&#39;; " color:#323e32;"="">4</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;color:#323E32;">行，每行</span><span style="font-size: 16px; font-family: &#39;Microsoft YaHei&#39;; " color:#323e32;"="">4</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;color:#323E32;">个字符，每个字符</span><span style="font-size: 16px; font-family: &#39;Microsoft YaHei&#39;; " color:#323e32;"="">&#34;w&#34; </span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;color:#323E32;">或</span><span style="font-size: 16px; font-family: &#39;Microsoft YaHei&#39;; " color:#323e32;"=""> &#34;b&#34;</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;color:#323E32;">表示游戏开始时格子上物件的状态。</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span> 
</h3>
<p>
	<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;color:#323E32;">输出文件</span><span style="font-size: 16px; font-family: &#39;Microsoft YaHei&#39;; " color:#323e32;"="">flip.out</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;color:#323E32;">仅一个整数，即从给定状态到实现这一任务的最少翻转次数。如果给定的状态就已经实现了目标就输出</span><span style="font-size: 16px; font-family: &#39;Microsoft YaHei&#39;; " color:#323e32;"="">0</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;color:#323E32;">，如果不可能实现目标就输出</span><span style="font-size: 16px; font-family: &#39;Microsoft YaHei&#39;; " color:#323e32;"="">&#34;Impossible&#34;</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;color:#323E32;">。</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输入】</span> 
</h3>
<pre>bwwb
bbwb
bwwb
bwww
</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输出】</span> 
</h3>
<pre>4
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【来源】</span> 
</h3>

<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">冲刺</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">NOIP2010</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">模拟试题与解析（七）</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（提高组复赛）</span> 
</p>
</pre>
