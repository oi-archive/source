# 题目描述


<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【题目描述】</span> 
</h3>
<p>
<br/>
</p>
<p style="text-indent:21.7500pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">starhder</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">突发奇想，要去</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">G</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">地，于是他搞来了一张地图，看怎么走才好。</span> 
</p>
<p style="text-indent:21.7500pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">地图上有很多城市，</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">G</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">地也是一座城市。每两座城市之间都可能有直达方法，也有可能两座城市之间并不能直接相通，而要通过其他的城市转达。对于两个城市之间的直达方法，需要一定的时间，当然，如果从</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">A</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">城市到</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">B</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">城市的直达方法需要</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">T</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">时间，那么从</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">B</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">城市到</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">A</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">城市的直达方法也是</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">T</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">时间。</span> 
</p>
<p style="text-indent:21.7500pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">starhder</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">想要用最短的时间到达</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">G</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">地，但是有个问题，他发现，地图上有些城市对他很有吸引力。所以他要在经过这些城市的基础上时间最短。</span> 
</p>
<p style="text-indent:21.7500pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">starhder</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">已经用</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">、</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">、</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">3</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">、</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">4</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">、</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">5</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">……n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">标记了他可能经过的城市（</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">代表出发地，</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">代表</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">G</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">地），但是眼花缭乱的地图让他感到烦恼。他请你来解决这个问题，告诉他最小需要多少时间到达</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">G</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">地。</span> 
</p>
<p>
<br/>
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输入格式】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> </span> 
</p>
<p style="text-indent:21.7500pt;">
输入文件的第一行是三个正整数<span>n</span><span>和</span><span>m</span><span>，</span><span>t</span><span>，</span><span>n</span><span>表示总共有多少个城市（包括出发地和</span><span>G</span><span>地），城市数不会超过</span><span>200</span><span>个；</span><span>m</span><span>是城市的直达路线数（</span><span>1&lt;=m&lt;=20000</span><span>），</span><span>t</span><span>表示一定去的城市数</span><span>0&lt;=t&lt;=10</span><span>（不包括出发地和</span><span>G</span><span>地）。</span> 
</p>
<p style="text-indent:21.7500pt;">
接下来一行有<span>t</span><span>个整数，表示一定要去的城市。</span> 
</p>
<p style="text-indent:21.7500pt;">
接下来<span>m</span><span>行，每行包含三个正整数，前两个数表示分别代表一个城市，第三个数是这两个城市之间的直达时间。直达时间不会超过</span><span>1000000</span><span>。</span> 
</p>
<p>
<br/>
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输出格式】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> </span> 
</p>
<p>
输出一个数，题目要求的得最短时间。
</p>
<p>
<br/>
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输入】</span> 
</h3>
<pre>5 10 2
2 3
1 2 5
1 3 45
1 4 61
1 5 81
2 3 9
2 4 91
2 5 4
3 4 74
3 5 42
4 5 61
</pre>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输出】</span> 
</h3>
<pre>27
</pre>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【来源】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">江苏省常州高级中学 图论练习</span> 
</p>
