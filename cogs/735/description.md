# 题目描述


<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«问题描述：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">给定一张航空图，图中顶点代表城市，边代表2城市间的直通航线。现要求找出一条满</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">足下述限制条件的且途经城市最多的旅行路线。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">(1)从最西端城市出发，单向从西向东途经若干城市到达最东端城市，然后再单向从东</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">向西飞回起点(可途经若干城市)。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">(2)除起点城市外，任何城市只能访问1次。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«编程任务：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于给定的航空图，试设计一个算法找出一条满足要求的最佳航空旅行路线。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«数据输入：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">由文件<span>airl.in</span>提供输入数据。文件第1 行有2个正整数N 和V，N 表示城市数，N&lt;100，</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">V 表示直飞航线数。接下来的N行中每一行是一个城市名，可乘飞机访问这些城市。城市名</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">出现的顺序是从西向东。也就是说，设i,j 是城市表列中城市出现的顺序，当i&gt;j 时，表示</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">城市i 在城市j 的东边，而且不会有2 个城市在同一条经线上。城市名是一个长度不超过</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">15 的字符串，串中的字符可以是字母或阿拉伯数字。例如，AGR34或BEL4。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">再接下来的V 行中，每行有2 个城市名，中间用空格隔开，如 city1 city2 表示city1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">到city2 有一条直通航线，从city2 到city1 也有一条直通航线。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«结果输出:</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">程序运行结束时，将最佳航空旅行路线输出到文件<span>airl.out</span> 中。文件第1 行是旅行路</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">线中所访问的城市总数M。接下来的M＋1 行是旅行路线的城市名，每行写1 个城市名。首</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">先是出发城市名，然后按访问顺序列出其它城市名。注意，最后1行（终点城市）的城市名</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">必然是出发城市名。如果问题无解，则输出“No Solution!”。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入文件示例 输出文件示例</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span>airl.in</span></span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">8 9</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Vancouver</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Yellowknife</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Edmonton</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Calgary</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Winnipeg</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Toronto</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Montreal</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Halifax</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Vancouver Edmonton</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Vancouver Calgary</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Calgary Winnipeg</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Winnipeg Toronto</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Toronto Halifax</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Montreal Halifax</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Edmonton Montreal</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Edmonton Yellowknife</span><br/>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Edmonton Calgary</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span>airl.out</span><br/>
</span> 
</p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">7</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Vancouver</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Edmonton</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Montreal</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Halifax</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Toronto</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Winnipeg</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Calgary</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Vancouver</span><br/>
