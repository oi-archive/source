# 题目描述

<p>今天又是核平的一天，跳蚤大军在完成建设任务后，也闲得没事做了。为贯彻劳逸结合的思想，跳蚤们分成 $n$ 队，正围在一起打着蚤国杀。同时，为了防御可能的袭击，跳蚤们在打牌现场安放了 $m$ 个 “三角莲”。</p>
<p>三角莲是一种植物，因其三角形莲叶而得名。在三角莲覆盖的区域内，它能使用技能“莲莲看”，用 “莲线” 将袭击过来的导蛋连在一起，并用 “莲刀” 一次销毁在莲线上的导蛋。它除了有防御的功能外，还能赋予跳蚤 “莲爱” 状态，使得跳蚤干劲十足，思考速度翻倍！当然它还有遮阴的作用，实乃居家旅行必备植物！</p>
<p>然而在地表……</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/241/dark.jpg" alt="黑恶势力登场"/></p>
<p>其实，垃鸡除了能发射鸡光，还能 “咯咯咯” 生出几个导蛋下来，而黑恶势力便将其改造成 “地对土导蛋”，准备对土卫二上的跳蚤大军发动奇袭。</p>
<p>黑恶势力通过 “扫描鸡光” 看到了三角莲之后并不死心，他们想统计下每个三角莲覆盖了多少队跳蚤，以便制定出一个最优的袭击计划。</p>
<p><strong>一句话题意：</strong>平面上有 $n$ 个点，$m$ 次询问，每次询问一个三角形内的点数。（边界上的点也包含）</p>

# 输入格式


<p>第一行两个正整数 $n,m$，意义如前所述。</p>
<p>接下来 $n$ 行，每行两个整数 $x,y$，表示每个队伍的坐标。</p>
<p>接下来 $m$ 行，每行六个整数 $x_1,y_1,x_2,y_2,x_3,y_3$，表示三角莲覆盖范围的三个顶点坐标。</p>
<p>数据保证每一组询问的三个点不共线且最开始的 $n$ 个点两两不同，不保证最开始输入的 $n$ 个点之间不存在三点共线。</p>

# 输出格式


<p>对于每个三角莲输出一行一个整数，表示被覆盖的点数。</p>

# 样例一


<h4>input</h4>
<pre>5 2
3 -2 
-2 1 
3 4 
-1 4 
-2 2 
3 -1 0 -2 0 5 
1 -2 -3 3 3 4 

</pre>

<h4>output</h4>
<pre>0
2

</pre>

<h4>explanation</h4>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/243/sample.png" alt="样例解释"/></p>

# 样例二


<p>见样例数据下载</p>

# 样例三


<p>见样例数据下载</p>

# 限制与约定


<p>由于一些原因，本题使用捆绑测试。每个子任务有若干个测试点，分为 $4$ 个子任务，你只有通过一个子任务的所有测试点才能得到这个子任务的分数。</p>
<p>下表中，$K$ 表示存在一个大小为 $K$ 的直线集合 $S$ 使得所有询问三角形的边都至少平行于 $S$ 中的一条直线。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务编号</th>
<th>分值</th>
<th>$n$</th>
<th>$m$</th>
<th>其他约定</th>
</tr></thead><tbody><tr><td>1</td><td>$20$</td><td>$n \leq 10^3$</td><td>$m \leq 10^3$</td><td>无</td></tr><tr><td>2</td><td>$20$</td><td rowspan="3">$n \leq 3 \times 10^4$</td><td rowspan="3">$m \leq 10^5$</td><td>$|x_i|,|y_i| \leq 100$</td></tr><tr><td>3</td><td>$30$</td><td>$K \leq 6$</td></tr><tr><td>4</td><td>$30$</td><td>无</td></tr></tbody></table></div>



<p>在所有数据中，满足 $|x_i|,|y_i| \leq 10^5$。</p>
<p><strong>时间限制：</strong>$8\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=243">样例数据下载</a></p>

# 后记


<p>正当 BOSS 打算按下桌上的按钮发动袭击的时候，地下会议室的门嘎吱一声被打开了，出现了一个人影。</p>
<p>“我是环保局工作人员，发射场的那些垃圾是你们丢的吧。在跳蚤国，你这样乱丢垃圾，是要被拿去煲汤的！诶，你们在干什么……”</p>
<p>黑恶势力最终还是被一锅端了，土卫二改造工作也顺利完成，Happy Ending~</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/243/defeat.jpg" alt="把黑恶势力干翻"/></p>
