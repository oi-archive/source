# 题目描述


<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 未名湖钓鱼(fish)</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【背景】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">在校园里，有一群没有命名小湖，那里有山有水，小湖里都有很多鱼，而且这些小湖都</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">是排列在一条直线上的。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">有一天小明去湖里钓鱼，他想钓到更多的鱼，可是他的时间是有限的，没有办法的小明</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">只好通过电话求助你，让你帮他算一下他最多可以钓到多少鱼。</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目描述】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">现在有N 个未名小湖排在一条直线上，相邻两个小湖之间的距离是相等的，需要T 分</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">钟的步行才可以到达相邻的一个小湖。每个湖刚开始的时候都会有一些鱼，未名湖神奇就神</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">奇在，你钓一次就可以把当前所有的鱼全部钓上来，但是湖中的鱼只会减少一个固定的数值，</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">而且消耗一个固定的时间K，如果当前湖中的鱼小于这个数值，则会把剩下的所有的鱼全部</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">钓上来，之后湖中的鱼归零。（如果钓鱼后减少的具体过程不明白，请参照样例）对于第i</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">个小湖，初始的鱼的数量记作s[i]，每钓一次会减少c[i]。小明只有M 的时间，他希望你能</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">在最短的时间内算出他最多可以钓多少鱼。当然，小明刚开始的时候在第一个湖的位置，并</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">且他希望在用光时间之前到达第N 个湖的位置(注意在钓鱼结束前小明必须在第n 个湖，并</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">且剩下的时间大于0)，之后结束他的钓鱼之旅。</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入数据】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第一行，四个数，N,M,T,K。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第2 至第n+1 行，每行两个数，分别表示了这N 个湖的初始鱼数量和每钓一次减少的</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">鱼的数量，即s[i],c[i]。</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出数据】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">一个数，小明可以钓到的最多的鱼的数量。</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入样例】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3 12 2 2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">10 2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">9 1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">15 5</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出样例】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">35</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例说明】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">小明一开始在第一个湖，钓一次鱼。之后到第三个湖，钓两次鱼。结果为10+15+10=35</span><br/>
<br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【数据范围】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于30%的数据，N&lt;=100,M&lt;=100,T&lt;=100,K&lt;=100。</span><br/>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于100%的数据，N&lt;=5000,M&lt;=100000,T&lt;=100,K&lt;=1000，S&lt;=10000,C&lt;=1000。</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">湖北省NOIP2011寒假集训Day5<br/>
</span> 
</p>
