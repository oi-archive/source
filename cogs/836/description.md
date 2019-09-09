# 题目描述


<blockquote>
	<h1>
		3.金明的游戏方案
	</h1>
Tyvj2012寒假模拟赛 <br/>
【问题描述】<br/>
金明今天很开心，他住进了他的新房，新房里有一间金明自己专用的很宽敞的房间。<br/>
金明通过金明的预算买到了许许多多的东西——包括一台电脑。更让他高兴的是，妈妈昨<br/>
天对他说：“你想玩多久电脑就玩多久，你说了算，只要别忘了睡觉就行。”<br/>
以一天为例，他把一天等分成了N 个时间段，在每个时间段玩游戏能获得的开心值各<br/>
不相同，在第i 个时间段能获得w[i]个开心值。因为要抽出时间睡觉，所以金明决定自己<br/>
一天只玩M 个时间段。<br/>
令金明万万没有想到的是，他没有考虑到很重要的一点，那就是网速！极不给力的网<br/>
速让金明感觉非常不爽。金明为了在接近1kbps（为什么不是1kb/s？1kbps 要比1kb/s<br/>
慢7 倍！）的网速中玩得更加舒畅一些，经过多次实验，他发现：每个游戏打开的时候都需<br/>
要一个时间段，多个游戏一起打开，也只需要一个时间段；只要打开游戏之后，玩起来就<br/>
不会卡。<br/>
因此，金明决定：先分配好M 个时间段（这M 个时间段可以是连续的，也可以是分散<br/>
的，只要让总的开心值尽可能得大就行），在每个连续一段玩游戏时间的第一个时间段打开<br/>
整段时间要玩的游戏。也就是说，他如果在i~j 中的所有时间段都玩游戏了，那么获得的<br/>
开心值就是SUM{w[k]}(i+1&lt;= k &lt;= j)（因为第i 个时间段用来打开所有要玩的游戏了，所<br/>
以不能获得开心值w[i]）<br/>
所有的时间段都是环形相连的，即第N 个时间段后是第1 个时间段。<br/>
金明想知道他能获得的最大开心值是多少？<br/>
【输入】<br/>
输入包含2 行。第一行两个正整数N,M，含义如题所述。<br/>
第二行N 个由一个空格隔开的非负整数w[i]。<br/>
【输出】<br/>
输出仅1 行，表示金明能获得的最大开心值。<br/>
【样例输入】<br/>
8 4<br/>
0 8 0 4 0 8 0 4<br/>
【样例输出】<br/>
16<br/>
【样例解释】<br/>
选择第1、2、5、6 个时间段，每个连续时间段的第一个时间段即第1、5 个时间段打<br/>
开网站，获得的最大开心值是w[2]+w[6]=8+8=16<br/>
【数据范围】<br/>
对于20%的数据，N &lt;=20<br/>
对于50%的数据，N &lt;=200
	<p>
		对于100%的数据，N &lt;=5,000,M &lt;= N,w[i] &lt;= 10,000
	</p>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<blockquote>
</blockquote>
<p>
	<br/>
</p>
