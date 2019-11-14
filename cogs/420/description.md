# 题目描述


<p>
<span style="font-size:larger;"><span style="font-family:Arial;"> <span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Elaxia最近迷恋上了空手道，他为自己设定了一套健身计划，比如俯卧撑、仰卧起坐等等，不过到目前为止，他坚持下来的只有晨跑。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 现在给出一张学校附近的地图，这张地图中包含N个十字路口和M条街道，Elaxia只能从一个十字路口跑向另外一个十字路口，街道之间只在十字路口处相交。Elaxia每天从寝室出发跑到学校，保证寝室编号为1，学校编号为N。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> Elaxia的晨跑计划是按周期（包含若干天）进行的，由于他不喜欢走重复的路线，所以在一个周期内，每天的晨跑路线都不会相交（在十字路口处），寝室和学校不算十字路口。Elaxia耐力不太好，他希望在一个周期内跑的路程尽量短，但是又希望训练周期包含的天数尽量长。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 除了练空手道，Elaxia其他时间都花在了学习和找MM上面，所有他想请你帮忙为他设计一套满足他要求的晨跑计划。 </span></span></span> 
</p>
<p>
<span style="font-size:larger;"><span style="font-family:Arial;"><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 输入</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 第一行2个数n,m。表示十字路口数和街道数。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 接下来m行，每行3个数a,b,c,表示十字路口a和十字路口b之间有条长度为c的街道（单向）。</span></span></span> 
</p>
<p>
<span style="font-size:larger;"><span style="font-family:Arial;"><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 输出</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 2个数，第一个数为最长周期的天数，第二个数为满足最长天数的条件下最短的路程长度。</span></span></span> 
</p>
<p>
<span style="font-size:larger;"><span style="font-family:Arial;"><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 输入样例</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 7 10</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 1 2 1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 1 3 1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 2 4 1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 3 4 1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 4 5 1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 4 6 1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 2 5 5</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 3 6 6</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 5 7 1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 6 7 1</span></span></span> 
</p>
<p>
<span style="font-size:larger;"><span style="font-family:Arial;"><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 输出样例</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 2 11</span><br/>
</span></span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">N&lt;=200  M&lt;=20000</span> 
</p>
