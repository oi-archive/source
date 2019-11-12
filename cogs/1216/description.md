# 题目描述


<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;"><span style="font-size:16px;line-height:19.200000762939453px;font-family:&#39;Microsoft YaHei&#39;;">【背景】</span></span> 
</h3>
<p>
	<span><span style="font-size:16px;line-height:19.200000762939453px;"><span style="font-family:Microsoft YaHei;">   经过在机房里数日的切磋，LYD从杜神牛那里学会了分离与合体，出关前，杜神牛给了他一个测试......</span><br/>
<span style="font-family:Microsoft YaHei;">    杜神牛造了n个区域，它们紧邻着排成了一行，编号1~n。在这每个区域里都放着一把OI界的金钥匙，每一把都有一定的价值，LYD当然想得到它们了。然而杜神牛规定LYD不可以一下子把它们全部拿走，而是每次只可以拿一个。为了尽快的拿到所有的金钥匙，LYD自然就用上了刚学的分离与合体特技。</span></span></span><span style="font-size:16px;line-height:19.200000762939453px;font-family:&#39;Microsoft YaHei&#39;;"></span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目描述】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-family:Microsoft YaHei;">   一开始LYD可以选择从1~n-1的任何一个区域(记为K)进入，进入后LYD会在K区域发生分离，从而分离为两个小LYD。分离完成的同时会有一面墙在K和K+1区域之间升起，从而把1~k和k+1~n阻断为两个独立的区间。然后两个小LYD分别进入1~k和k+1~n，并在各自的区间内任选除了区间末尾区域以外(即1~k-1或k+1~n-1)的任何一个区域再次发生分离，就一共有了4个小小LYD……重复进行以上所叙述的分离，直到每个小LYD发现自己所在的区间只剩下了一个区域，他们就可以抱起自己梦寐以求的OI金钥匙。</span><br/>
<span style="font-family:Microsoft YaHei;">     但是LYD不能就这么分成n多个个体存在于世界上，这些小LYD还会再合体，合体的两个小LYD所在的区间中间的墙会消失。合体会获得一定的价值，计算方法是：(合并后所在区间的左右端区域里金钥匙的价值之和) 乘 (之前分离的时候所在区域的金钥匙价值)。</span><br/>
<span style="font-family:Microsoft YaHei;"> {例如：LYD曾经在1~3区间中的2号区域分离成为1~2和3两个区间，合并时获得的价值就是（1号金钥匙价值+3号价值）*(2号金钥匙价值)。}</span><br/>
<span style="font-family:Microsoft YaHei;">    LYD请你编程求出最终可以获得的总价值最大是多少。并按照分离阶段从前到后，区域从左向右的顺序，输出发生分离的区域编号 (例如：先打印1分为2的分离区域，然后从左到右打印2分为4的分离区域，然后是4分为8的......) 。</span><br/>
<span style="font-family:Microsoft YaHei;">     注意：若有多种方案，选择分离区域尽量靠左的方案（也可以理解为输出字典序最小的）。</span><br/>
</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span></span><span style="font-family:Microsoft YaHei;">第一行:正整数n (2&lt;=n&lt;=300)</span><br/>
<span style="font-family:Microsoft YaHei;"> 第二行:n个正整数，表示1~n区域里每把金钥匙的价值。</span><br/>
<span style="font-family:Microsoft YaHei;"> 保证答案及运算过程中不超出longint范围。</span><span></span></span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-family:Microsoft YaHei;">第一行一个数，即获得的最大价值</span><br/>
<span style="font-family:Microsoft YaHei;"> 第二行按照分离阶段从前到后，区域从左向右的顺序，输出发生分离的区域编号，中间用一个空格隔开，若有多种方案，选择分离区域尽量靠左的方案（也可以理解为输出字典序最小的）。</span></span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输入】</span> 
</h3>
<pre>7
1 2 3 4 5 6 7
</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输出】</span> 
</h3>
<pre>238
1 2 3 4 5 6
</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【提示】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">各个测试点1s</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-family:Microsoft YaHei;">数据范围约定</span><br/>
<span style="font-family:Microsoft YaHei;"> 对于%20的数据  N&lt;=10  </span><br/>
<span style="font-family:Microsoft YaHei;"> 对于%40的数据  N&lt;=50</span><br/>
<span style="font-family:Microsoft YaHei;"> 对于%100的数据 N&lt;=300  a[i]&lt;=300 </span><br/>
</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【来源】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">幻影^九天麟日（LYD）  TYVJ首届月赛 第二道</span> 
</p>
