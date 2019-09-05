# 题目描述


<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【题目描述】</span>
</h3>
<p>
	<br/>
</p>
<p style="font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;color:#494949;font-size:14.399999618530273px;text-align:left;background-color:#F5F9F8;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">Bessie不小心游荡出Farmer John的田地，而走进了相邻的农民的地里。她举起一个木瓜，木瓜对奶牛来说可是不可多得得美味。这个木瓜林像一般的威斯康星州的田地一样被分割成一个R行C列的网格(1 &lt;= R &lt;= 40, 1 &lt;= C &lt;= 40)。Bessie可以从一个格沿着一条跟X轴或Y轴平行的直线走到邻接的另一个格。Bessie发现一开始她自己在木瓜林的(1,1)，也就是第一行第一列慢悠悠地咀嚼着木瓜。</span>
</p>
<p style="font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;color:#494949;font-size:14.399999618530273px;text-align:left;background-color:#F5F9F8;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">Bessie总是用她最信赖地双筒望远镜去数每一个邻接的格里挂着的木瓜的数目。然后她就游荡到那个有最多没有被吃掉的木瓜的邻接的格子（保证这样的格子只有一个）。</span>
</p>
<p style="font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;color:#494949;font-size:14.399999618530273px;text-align:left;background-color:#F5F9F8;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">按照这种移动方法，最终Bessie总是会在(R,C)停止然后吃掉那里的木瓜。</span>
</p>
<p style="font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;color:#494949;font-size:14.399999618530273px;text-align:left;background-color:#F5F9F8;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">给定这个木瓜林的大小及每个格的木瓜数F_ij(1 &lt;= F_ij &lt;= 100), 要求Bessie一共吃了多少个木瓜。</span>
</p>
<p>
	<br/>
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输入格式】</span>
</h3>
<p>
	<br/>
</p>
<p style="font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;color:#494949;font-size:14.399999618530273px;text-align:left;background-color:#F5F9F8;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">第1行: 两个空格隔开的整数R和C.</span>
</p>
<p style="font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;color:#494949;font-size:14.399999618530273px;text-align:left;background-color:#F5F9F8;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">第2..R+1行: 第i+1行有C个空格隔开的整数，表示第i行的每个格的水果数。也就是F_i1, F_i2, ..., F_iC.</span>
</p>
<p>
	<br/>
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输出格式】</span>
</h3>
<p>
	<span style="color:#494949;font-family:&#39;Microsoft YaHei&#39;;font-size:14px;line-height:21.600000381469727px;background-color:#F5F9F8;">第1行: 一个单独的整数，表示到Bessie吃完右下角(R,C)的木瓜回到牛棚的时候为止，一共在木瓜林吃掉了多少个木瓜。</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输入】</span>
</h3>
<pre>3 4
3 3 4 5
4 5 3 2
1 7 4 2</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输出】</span>
</h3>
<pre>39</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【提示】</span>
</h3>
<p>
	<span style="color:#494949;font-family:&#39;Microsoft YaHei&#39;;font-size:14px;line-height:21.600000381469727px;background-color:#F5F9F8;">木瓜林是三行四列，Bessie起始于左上角的&#34;3&#34;。</span><br/>
<span style="color:#494949;font-family:&#39;Microsoft YaHei&#39;;font-size:14px;line-height:21.600000381469727px;background-color:#F5F9F8;">Bessie按照下图数字旁边的字母的顺序吃掉木瓜。</span> 
</p>
<p>
	<span style="color:#494949;font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;font-size:14.399999618530273px;line-height:21.600000381469727px;background-color:#F5F9F8;"><img src="/upload/image/20121003/20121003162419_91868.jpg" alt=""/><br/>
</span> 
</p>
<p>
	<span style="color:#494949;font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;font-size:14.399999618530273px;line-height:21.600000381469727px;background-color:#F5F9F8;"><span style="color:#494949;font-family:&#39;Microsoft YaHei&#39;;font-size:14px;line-height:21.600000381469727px;background-color:#F5F9F8;">她吃了39个木瓜，剩下4个没有吃（也就是说除了2个格幸免于难，剩下的格子都被Bessie扫荡过了）。</span><br/>
</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【来源】</span>
</h3>
<p>
	<span style="color:#494949;font-family:&#39;Microsoft YaHei&#39;;font-size:14px;line-height:21.600000381469727px;background-color:#F5F9F8;">USACO OCT09</span> 
</p>
