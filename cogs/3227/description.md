# 题目描述


<h3>
【题目描述】
</h3>
<p>
本题面由 @数声风笛离亭晚 翻译。$(前排征求评测数据QwQ)$
</p>
<p>
Tour operator Your Personal Holiday organises guided bus trips acrossthe Benelux. Every day the bus moves from one city $S$ to another city $F$.On this way, the tourists in the bus can see the sights alongside the route travelled. Moreover, the bus makes a number of stops (zero or more) at some beautiful cities, where the tourists get out to see the local sights.
</p>
<p>
Different groups of tourists may have different preferences for the sights they want to see, and thus for the route to be taken from $S$ to $F$. Therefore, Your Personal Holiday wants to offer its clients a choice from many different routes. As hotels have been booked in advance, the starting city $S$ and the final city $F$, though, are fixed. Two routes from $S$ to $F$ are considered different if there is at least one road from a city $A$ to a city $B$ which is part of one route, but not of the other route.There is a restriction on the routes that the tourists may choose from.
</p>
<p>
To leave enough time for the sightseeing at the stops (and to avoid using too much fuel), the bus has to take a short route from $S$ to $F$.It has to be either a route with minimal distance, or a route which is one distance unit longer than the minimal distance. Indeed, by allowing routes that are one distance unit longer, the tourists may have more choice than by restricting them to exactly the minimal routes. This enhances the impression of a personal holiday.
</p>
<p>
For example, for the above road map, there are two minimal routes from $S$ = 1 to $F$= 5:1→2→5 and 1→3→5, both of length 6. There is one route thatis one distance unit longer: 1→3→4→5, of length 7.Now, given a (partial) road map of the Benelux and two cities $S$ and $F$,tour operator Your Personal Holiday likes to know how many different routes it can offer toits clients, under the above restriction on the route length.
</p>
<p>
                  <img src="/upload/image/20190807/20190807112733_91059.png" alt=""/> 
</p>
<p>
Your Personal Holiday 旅行社组织了一场游览比荷卢三国的巴士观光之旅，每一天，观光巴士从城市$S$开往城市$F$。通过这样，游客们可以看到沿途的美丽风景。另外，该观光巴士在一些风景优美的城市有停靠站( 0 个或更多)，方便游客下车去景点游玩。
</p>
<p>
不同的游客群体可能对他们想要观看的景点有不同的偏好，因此从$S$到$F$的路线也会时常更改。Your Personal Holiday 旅行社希望为客户提供多种不同路线的选择，由于酒店已提前预订，因此起始城市$S$和最终城市$F$是固定不变的。如果沿途中从城市$A$到城市$B$的至少一条道路是一条路线的一部分，而不是另一条路线的一部分，则认为从$S$到$F$的两条路线是不同的。
</p>
<p>
为了留出足够的时间在车站观光（并避免使用太多的燃料），游客可以选择的路线也有限制，观光巴士必须选择$S$到$F$的较短路线，它必须是具有最短路线，或者是比最短路长一个距离单位的路线。实际上，若通过比最短路线距离稍长的路线，游客可能会有更多的选择，而不是将它们限制在最短路线上。这样可以增强游客们的观景体验。
</p>
<p>
以该地图为例，从城市$S$到城市$F$($S = 1, F = 5$)的最短路径有两条,分别为$ 1 → 2 → 5 $和$ 1 → 3 → 5 $，其长度均为$ 6 $。还有一条长度比最短路线长一个单位距离的路线，为$ 1 → 3 → 4 → 5 $，其长度为$ 7 $。现在，有好几张比荷卢三国的(部分)地图，起点城市$S$和终点城市$F$。 Your Personal Holiday 旅行社想知道按照以上路线选择方法，有多少种不同的路线可以提供给游客们。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
The first line of the input file contains a single number $T$: the number of test cases to follow. Each test case has the following format:
</p>
<p>
Oneline with two integers $N$ and $M$, separated by a single space, with $2≤N≤1,000$ and $1≤M≤10,000$:the number of cities and the number of roads in the road map.
</p>
<p>
$M$ lines, each with three integers $A$, $B$ and $L$, separated by single spaces, with $1≤A,B≤N$, $A≠B$ and $1≤L≤1,000$, describing a road from city $A$ to city $B$ with length $L$.
</p>
<p>
The roads are unidirectional. Hence, if there is a road from $A$ to $B$, then there is not necessarily also a road from $B$ to $A$. There may be different roads from a city $A$ to a city $B$.One line withtwo integers $S$ and $F$, separated by a single space, with $1≤S$,$F≤N$and $S≠F$: the starting city and the final city of the route.
</p>
<p>
There will be at least one route from $S$ to $F$.
</p>
<p>
<br/>
</p>
<p>
每个输入文件包含多组数据。
</p>
<p>
输入文件的第一行,包含一个正整数$T$,代表该输入文件中所含的数据组数。
</p>
<p>
接下来是$T$组数据,每组数据的格式如下：
</p>
<p>
第一行包含两个整数$N$和$M$,两个数之间以一个空格分开，分别代表城市的数量和地图上道路的个数。
</p>
<p>
接下来的$M$行,每行包含三个整数$A$、$B$和$L$,每个数之间以一个空格分开,代表从$A$城市到达$B$城市的路径长度为$L$.这些道路是单向的。因此，如果有从城市$A$到城市$B$的道路，但不一定有从城市$B$到城市$A$的道路,但不排除测试数据中提供双向道路的情况。
</p>
<p>
第 $M+2$ 行包含两个整数$S$和$F$，两个数之间以一个空格分开，代表本次观光游览的起点城市与终点城市。
</p>
<p>
保证存在至少一条可以从城市$S$到达城市$F$的路线。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
For every test case in the input file, the output should containa single number, on a single line: the number of routes ofminimal length or one distance unit longer.
</p>
<p>
<br/>
</p>
<p>
输出文件包含$T$行，分别对应$T$组数据的答案，每组数据的答案格式如下：
</p>
<p>
一个整数，表示最短路径和长度比最短路径长 $1$ 单位路径的路径的数量和。
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre>2
5 8
1 2 3
1 3 2
1 4 5
2 3 1
2 5 3
3 4 2
3 5 4
4 5 3
1 5
5 6
2 3 1
3 2 1
3 1 10
4 5 2
5 2 7
5 2 7
4 1

</pre>
<h3>
【样例输出】
</h3>
<pre>3
2

</pre>
<h3>
【提示】
</h3>
<p>
The first test case above corresponds to the picture in the problem description.
</p>
<p>
<br/>
</p>
<p>
第一个测试数据对应着题目描述中的图片。
</p>
<p>
<br/>
</p>
<p>
对于全部数据，保证有：
</p>
<p>
$2≤N≤1,000, 1≤M≤10,000, 1≤A,B≤N, A≠B, 1≤L≤1,000, 1≤S,F≤N, S≠F, T≤1,000,000,000.$
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://poj.org/problem?id=3463" target="_blank">PKU JudgeOnline T3463</a> 
</p>
<div style="background:initial !important;border:initial !important;border-radius:initial !important;border-spacing:initial !important;border-collapse:initial !important;direction:ltr !important;flex-direction:initial !important;font-weight:initial !important;height:initial !important;letter-spacing:initial !important;min-width:initial !important;max-width:initial !important;min-height:initial !important;max-height:initial !important;margin:auto !important;outline:initial !important;padding:initial !important;position:absolute;table-layout:initial !important;text-align:initial !important;text-shadow:initial !important;width:initial !important;word-break:initial !important;word-spacing:initial !important;overflow-wrap:initial !important;box-sizing:initial !important;display:initial !important;color:inherit !important;font-size:13px !important;font-family:X-LocaleSpecific, sans-serif, Tahoma, Helvetica !important;line-height:13px !important;vertical-align:top !important;white-space:inherit !important;left:541px;top:60px;opacity:0.65;" id="s3gt_translate_tooltip_mini" class="s3gt_translate_tooltip_mini_box" is_mini="true">
<div id="s3gt_translate_tooltip_mini_logo" class="s3gt_translate_tooltip_mini" title="翻译所选文本">
</div>
<div id="s3gt_translate_tooltip_mini_sound" class="s3gt_translate_tooltip_mini" title="朗读" title_play="朗读" title_stop="停止">
</div>
<div id="s3gt_translate_tooltip_mini_copy" class="s3gt_translate_tooltip_mini" title="复制到剪贴板">
</div>
<link rel="stylesheet" type="text/css" href="moz-extension://d2451c64-ecb2-4fa8-94dc-4b9a6cd8af4e/skin/s3gt_tooltip_mini.css"/>
<style type="text/css" media="print">#s3gt_translate_tooltip_mini { display: none !important; }</style>
</div>
