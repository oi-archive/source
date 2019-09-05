# 题目描述


<h1>
	<span></span><span style="font-size:24px;">Problem 3 周年纪念日</span> 
</h1>
<h1>
	<span style="font-size:16px;"> (anniversary.pas/c/cpp)</span> 
</h1>
<br/>
<br/>
<h2>
	<span></span><span style="font-size:24px;">背景</span><span></span> 
</h2>
<span style="font-size:16px;">WZland即将迎来一个举国欢庆的日子—建国150亿周年纪念日，值此之际WZland有许多</span><span style="font-size:16px;">事情要准备……</span><br/>
<h2>
	<span style="font-size:24px;">问题描述</span> 
</h2>
<span style="font-size:16px;">WZland的国王决定举办一个晚会，这次晚会要求所有的WZland居民都参加，但是他发现</span><span style="font-size:16px;">WZland的所有城市之间的道路都已经毁坏（平时WZland的居民都在自己的城市里活动，所</span><span style="font-size:16px;">以他们对</span><span style="font-size:16px;">于那些道路一点都不关心）。这是一件十分麻烦的事情，因为这个晚会要求所有居</span><span style="font-size:16px;">民都来参</span><span style="font-size:16px;">加，于是国王决定要重建道路。</span><br/>
<span style="font-size:16px;"> 他找出了WZland的地图，他发现WZland有N个城市，有M条破败的双向道路连接着这N</span><span style="font-size:16px;">个城市。由于周年纪念日就要到来，为了节省时间国王决定修建的道路恰好将这N个城市连</span><span style="font-size:16px;">接起来。修建一条长度为L的道路，需要花费L个Ws(Ws是WZland的通用货币)，国王想要</span><span style="font-size:16px;">将总的花费降到最少，这样他能有足够多的钱来举办晚会。国王还有一个要求，因为这些道</span><span style="font-size:16px;">路是同时开始修建的，因此修建完这些道路的总时间等于修建完最长的那条道路的时间（你</span><span style="font-size:16px;">可以认为所有工人的修建速度是一样的，即一单位时间修建1单位长度的道路），国王想要</span><span style="font-size:16px;">总的修建时间最少。</span><br/>
<span style="font-size:16px;"> 由于要举行晚会，国王需要找到一个地点来举办晚会，这同样是一件十分麻烦的事情。因</span><span style="font-size:16px;">为WZland的每个人都十分懒，他们不愿意多走路（就连在这周年纪念日也不例外）。WZland</span><span style="font-size:16px;">的居民每走1单位长度的路就会产生1单位的不高兴度（这就是为什么他们都不愿离开自己</span><span style="font-size:16px;">城市的原因）。WZland的国王想要这个晚会的不高兴度尽量低（晚会的不高兴度就等于所</span><span style="font-size:16px;">有参加晚会的人的不高兴度的和），这就要求选取一个合适的地点来举办晚会（WZland的</span><span style="font-size:16px;">居民要通过即将修建好的道路，来到这个晚会举办地）。</span><br/>
<span style="font-size:16px;"> 举个例子，如果晚会在城市u举行，城市i有Pi个人，城市u和城市i的距离为D(u,i)，那么这</span><span style="font-size:16px;">些人产生的不高兴度之和为Pi*D(u,i)。</span><br/>
<span style="font-size:16px;"> 国王把这个任务交给了你，他希望你能找出一个地点，是所有人的不高兴度之和最小。</span><br/>
<br/>
<br/>
<p>
	<span style="font-size:24px;">输入格式</span> 
</p>
<p>
	<span style="font-size:16px;"><br/>
</span> 
</p>
<span style="font-size:16px;"> 输入数据第一行包含两个整数N和M，表示WZland有N个城市，M条破坏的道路；</span><br/>
<span style="font-size:16px;"> 第2行到N+1行：第i+1行包含一个整数Pi，表示城市i的居民人数。</span><br/>
<span style="font-size:16px;"> 第N+2行到N+M+1行，每行三个整数A，B，L(1≤A,B≤N，A≠B)，表示A和B之间有一</span><span style="font-size:16px;">条长度为L的破坏道路。</span><br/>
<p>
	<span style="font-size:16px;"> 注意：两个城市之间可能会有多条道路。</span> 
</p>
<p>
	<span style="font-size:16px;"><br/>
</span> 
</p>
<h1>
	<span></span><span style="font-size:24px;">输出格式</span><span></span> 
</h1>
<p>
	<span style="font-size:16px;"><br/>
</span> 
</p>
<span style="font-size:16px;"> 输出数据包含两行。</span><br/>
<span style="font-size:16px;"> 第一行两个整数C，T(用一个空格隔开)，表示修建道路的最少花费和最少时间。</span><br/>
<span style="font-size:16px;"> 第二行两个整数U，H(用一个空格隔开)，表示晚会的地点(如果有多个地点满足条件，输</span><span style="font-size:16px;">出编号最小的那个城市)和相应地点所有人的不高兴度之和。</span><br/>
<br/>
<br/>
<h1>
	<span style="font-size:24px;">样例输入输出</span> 
</h1>
<p>
	<span style="font-size:16px;"><br/>
</span> 
</p>
<span style="font-size:16px;"> anniversary.in </span><br/>
<span style="font-size:16px;"> 5 7</span><br/>
<span style="font-size:16px;"> 3</span><br/>
<span style="font-size:16px;"> 2</span><br/>
<span style="font-size:16px;"> 2</span><br/>
<span style="font-size:16px;"> 1</span><br/>
<span style="font-size:16px;"> 4</span><br/>
<span style="font-size:16px;"> 1 5 1</span><br/>
<span style="font-size:16px;"> 1 3 7</span><br/>
<span style="font-size:16px;"> 2 1 4</span><br/>
<span style="font-size:16px;"> 2 3 6</span><br/>
<span style="font-size:16px;"> 3 4 5</span><br/>
<span style="font-size:16px;"> 2 4 3</span><br/>
<span style="font-size:16px;"> 5 4 2</span><br/>
<br/>
<br/>
<span style="font-size:16px;"> anniversary.out</span><br/>
<span style="font-size:16px;"> 11 5</span><br/>
<span style="font-size:16px;"> 5 29</span><br/>
<br/>
<br/>
<h1>
	<span style="font-size:24px;">样例解释</span> 
</h1>
<p>
	<span style="font-size:16px;">合法的修建方案如下图(相邻城市之间的距离和每个城市的人数见样例)：</span> 
</p>
<p>
	<img src="/upload/image/20120809/20120809085618_57080.png" alt=""/><span></span> 
</p>
