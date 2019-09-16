# 题目描述


<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【题目背景】</span><br/>
</h3>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">『谜题在丛林中散发芳香</span><br/>
<span style="font-family:Microsoft YaHei;font-size:16px;">绿叶上露珠跳跃着歌唱</span><br/>
<span style="font-family:Microsoft YaHei;font-size:16px;">火焰在隐暗的角落升腾飞起</span><br/>
<span style="font-family:Microsoft YaHei;font-size:16px;">月华照射着神祇们忠诚的信徒。』</span> 
</p>
<p>
	————《瓦尔基里福音书·第六乐章：幻想》————
</p>
<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【题目描述】</span> 
</h3>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">Tristan 解决了英灵殿的守卫安排后，便到达了静谧的精灵领地——Alfheim。由于Midgard<br/>
处在Alfheim 和冥界Hel 的中间，精灵族领地尚未受到冥界恶灵的侵入。族长Galanodel 为<br/>
了帮助米德加尔特抵御外敌，对邪恶亡灵军团使用了高等魔法，从而使得亡灵军团每个士兵<br/>
的行进速度变得不一致，从而打乱冥王Hel 安排的最佳阵型。由于这个军团离Midgard 还很<br/>
远，因此在抵达Midgard 之前，对于A、B 两个亡灵，若A 的初始位置在B 后面且A 的速<br/>
度比B 快，A 就会冲到B 的前面去。现在Galanodel 想知道，会有多少对亡灵之间出现反超<br/>
现象？</span> 
</p>
<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【输入格式】</span> 
</h3>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">第一行一个整数n，表示排成一队的邪恶亡灵军团有多少人。<br/>
第二行n 个整数a[i]，表示邪恶亡灵们在数轴上的初始坐标。数据保证这些坐标全部不同。<br/>
亡灵军团向数轴正方向前进。<br/>
第三行n 个整数v[i]，表示邪恶亡灵们的行进速度。</span> 
</p>
<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【输出格式】</span> 
</h3>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">一行一个正整数k，表示「反超」的个数。</span> 
</p>
<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【样例输入】</span> 
</h3>
<pre>3
1 2 3
2 1 3
</pre>
<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【样例输出】</span> 
</h3>
<pre>1</pre>
<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【提示】</span> 
</h3>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">Time Limit:1s</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">对于30%的数据，1&lt;= N&lt;= 1000；<br/>
对于100%的数据，1&lt;=N&lt;= 10^5。<br/>
所有数据的绝对值均不超过maxlongint。<br/>
</span> 
</p>
<h3>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【来源】</span> 
</h3>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">《末世神话：精灵族的急援》</span> 
</p>
