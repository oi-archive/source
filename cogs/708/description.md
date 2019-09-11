# 题目描述


<p style="text-align:center;">
	<span style="font-size:16px;color:#000000;font-family:&#39;Microsoft YaHei&#39;;"><span style="font-size:16px;color:#000000;font-family:&#39;Microsoft YaHei&#39;;"><strong>有何不可(why.in/why.out)</strong></span></span> 
</p>
<p style="text-align:center;">
	<span style="font-size:16px;line-height:44px;font-family:&#39;Microsoft YaHei&#39;;"><b>陈立杰 灰色头像模拟赛 P4</b></span> 
</p>
<p>
	<span><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">引子： 为你唱这首歌 没有什么风格</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">它仅仅代表着 我想给你快乐</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">为你解冻冰河 为你做一只扑火的飞蛾</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">没有什么事情是不值得</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">为你唱这首歌 没有什么风格</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">它仅仅代表着 我希望你快乐</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">为你辗转反侧 为你放弃世界有何不可</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">夏末秋凉里带一点温热 有换季的颜色</span><br/>
<br/>
</span></span> 
</p>
<p>
	<span><span><span><strong><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">背景：</span></strong><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">某天，WJMZBMR在外面闲逛，看到神牛XXX在跟他的GF（你们懂的）逛街。他的GF看中了N件物品，每件物品有价格和喜爱度，</span></span></span></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">可WJMZBMR知道XXX不是神马富二代。</span></span></span></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> XXX身上一分钱都没有（全被他GF花光了）。XXX非常的痛苦的时候，被春哥看到了，春哥正好心情很好，</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">看在XXX平时信春哥的份上，给了XXX M元钱。 同时那天是伟大的数学家Fibonacci的生日，所以所有商品的价格全部是Fibonacci数。</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> XXX很爱他的GF，他希望在自己能及的范围内让买来的物品的喜爱度最大。 WJMZBMR在旁边表示压力很大囧。。。</span> 
</p>
<p>
	<span><span><span><br/>
</span></span></span> 
</p>
<p>
	<span><span><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><strong>数学定义：</strong></span><strong></strong><br/>
</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Fibonacci数列：满足a[1]=1,a[2]=1,a[n]=a[n-1]+a[n-2]的数列。</span></span></span> 
</p>
<p>
	<span><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 前几项为1,1,2,3,5,8,13 Fibonacci数：Fibonacci数列中的数</span><br/>
</span></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">N个物品，体积都是Fibonacci数，价值也给出，每个物品只有一个，放入体积为M的背包中，求最大价值。</span></span></span> 
</p>
<p>
	<span><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 01背包问题的扩展</span><br/>
</span></span> 
</p>
<p>
	<span><span><br/>
</span></span> 
</p>
<p>
	<span><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><strong>输入：</strong></span><strong></strong><br/>
</span></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第一行N和M表示物品数和钱数 </span></span></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">接下来N行，每行两个数分别表示一个物品的价格和喜爱度</span></span></span> 
</p>
<p>
	<span><span><br/>
</span></span> 
</p>
<p>
	<span><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><strong>输出：</strong></span><strong></strong><br/>
</span></span> 
</p>
<p>
	<span><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">一行表示最大价值</span><br/>
</span></span> 
</p>
<p>
	<span><span><br/>
</span></span> 
</p>
<p>
	<span><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><strong>样例输入：</strong></span><strong></strong><br/>
</span></span> 
</p>
<p>
	<span><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3 10</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5 8</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">8 10</span></span></span> 
</p>
<p>
	<span><span><strong><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">样例输出：</span><br/>
</strong></span></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">13</span></span></span> 
</p>
<p>
	<span><span><strong><span><br/>
</span></strong></span></span> 
</p>
<p>
	<span><span><strong><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">样例的解释：</span></strong><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">选择第一个和第三个物品</span></span></span> 
</p>
<p>
	<span><span><br/>
<span style="font-weight:bold;font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">数据范围：</span><br/>
<span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">100%的数据 N&lt;=200</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 40%的数据 M&lt;=10000 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 100%的数据 M&lt;=10^9 </span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 物品重量价值，可以用int和longint存储，但是总价值/总重量说不定就溢出了</span></span></span></span> 
</p>
