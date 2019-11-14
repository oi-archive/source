# 题目描述


<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目描述】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span></span>最近Bugall经常在VS（平台）上Dota（游戏的名字），他最喜欢用的英雄就是沙王了.今天在业余时间他又去VS找虐了，今天他又被屠夫虐了，在Bugall不知道的情况下屠夫从河道绕到Bugall的沙王傍边然后一个钩子，接着Bugall同学的沙王就变成了烤蝎子.因为河道在有自己队人的时候才能看见，当河道没有自己队人的时候是看不见的，所以Bugall同学的沙王会经常变成烤蝎子,为了不让Bugall的沙王再次被杀，我们需要随时监视河道，这样在有敌人的时候会给Bugall足够的时间逃跑.<br/>
  <br/>
 游戏中有个道具的名字叫做&#34;眼&#34;(功能：如果在河道一点放置一个这种道具，在没有自己队人的时候也能看到河道)，但是&#34;眼&#34;是有监视范围的，即第i号点的监视范围是[i-1,i+1]。如果&#34;眼&#34;被放置到了2号点，那么它只能监视到1，2，3这3个点，现在有N个点每个点都可以放置&#34;眼&#34;，但是每个点都有放置&#34;眼&#34;的难度，现在Bguall想知道在河道的每个点都能被监视到的前提下放置眼的难度值之和最小是多少.<br/>
 （我们可以把河道想象成是由1..N连续的整数点组成）<br/>
</span> 
</p>
<h3>
<span></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span></span>第一行为一个整数N，表示河道的长度.<br/>
 接下来i+1~N+1行每行一个整数P 表示在i点放置&#34;眼&#34;的难度为P</span>
</p>
<p>
<strong>2018.4.6修正By </strong><a href="http://218.28.19.228:8080/cogs/user/detail.php?uid=1686" target="_blank"><strong>FoolMike</strong></a>
</p>
<p>
<strong>数据范围:$N \leq 3 \times 10^5$。</strong>
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出最小难度值</span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输入】</span> 
</h3>
<pre>4
1
2
4
3
</pre>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输出】</span> 
</h3>
<pre>4</pre>
