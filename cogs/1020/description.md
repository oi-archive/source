# 题目描述


<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">哈密顿路(hamilton.pas/.c/.cpp)</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目叙述】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">SHY 喜欢研究各种各样奇奇怪怪的东西~</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">一天，SHY 研究了一个关于哈密顿路的问题。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">如果一条路径满足：不经过重复顶点、不经过重复边、首尾相连， 那么称这条路径为简单环。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">给出一张无向图，求这个无向图当中长度不小于3（即经过不少于3 个点）的简单环的个数。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第一行两个整数N、M，表示图有N 个点、M 条边。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">接下来M 行，每行两个整数a、b，表示顶点a 和顶点b 之间有一条无向边。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">数据保证没有自环和重边的出现。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">一行一个整数，表示无向图当中长度不小于3 的简单环的个数。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入样例】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">4 6</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 4</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 4</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3 4</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出样例】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">7</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例解释】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">七个环分别为：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1-&gt;2-&gt;3-&gt;1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1-&gt;2-&gt;4-&gt;1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1-&gt;3-&gt;4-&gt;1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2-&gt;3-&gt;4-&gt;1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1-&gt;2-&gt;3-&gt;4-&gt;1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1-&gt;2-&gt;4-&gt;3-&gt;1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1-&gt;3-&gt;2-&gt;4-&gt;1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【数据范围】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于50%的数据,保证答案不大于10^6.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于100%的数据,N&lt;=20, 保证答案可以用64 位整形存储,请C/C++语言选手一定要注意</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入输出问题，对于使用C++语言的选手推荐采用cin/cout 进行输入/输出操作。</span><br/>
