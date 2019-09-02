# 题目描述


<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"><strong>Freda 的迷宫</strong></span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">(mazea.pas/.c/.cpp)</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">题目叙述</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">Freda 是一个迷宫爱好者，她利用业余时间建造了许多迷宫。每个迷宫都是由若干房间</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">和走廊构成的，每条走廊都连接着两个不同的房间，两个房间之间最多只有一条走廊直接相</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">连，走廊都是双向通过。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">黄昏时候，Freda 喜欢在迷宫当中漫步。每天，Resodo 都会为Freda 设计一个挑战方案。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">Resodo 会指定起点和终点，请Freda 来找到一条从起点到终点的简单路径。一条简单路径定</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">义为一个房间序列，每个房间至多在序列里出现一次，且序列中相邻的两个房间有走廊相连。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">当起点和终点之间存在且仅存在一条简单路径的时候，Freda 认为这个挑战方案是RD 的。现</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">在，请你帮帮Resodo 来写一个程序，判断一个挑战方案是否是RD 的。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输入格式</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">第一行三个整数N,M,Q.分别表示房间数，走廊数，询问数。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-size:14px;">接下来M 行每行2 个整数x,y, 0</span><x,y<=n, 表示x="" 和y="" 之间有一条走廊相连。<="" span=""><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">接下来Q 行每行2 个整数x,y, 表示询问以x 为起点,y 为终点的挑战方案是否是RD 的.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输出格式</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">对于每个询问，输出一行”Y”或者”N”（不含引号）.Y 表示该询问所表示的挑战方案</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">是RD 的,N 表示该询问所表示的挑战方案不是RD 的.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输入样例</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">6 5 3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">1 2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">2 3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">2 4</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">2 5</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">4 5</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">1 3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">1 5</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">2 6</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输出样例</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">Y</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">N</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">N</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">样例解释</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">1,3 之间只有一条路径1-&gt;2-&gt;3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">1,5 之间有两条路径1-&gt;2-&gt;5 ; 1-&gt;2-&gt;4-&gt;5</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">1,6 之间没有路径</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">数据范围与约定</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">对于30%的数据，N&lt;=100， M&lt;=1000, Q&lt;=100.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">对于50%的数据，N&lt;=1000, M&lt;=10000, Q&lt;=1000.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">对于100%的数据，N&lt;=10000, M&lt;=100000, Q&lt;=10000.</span><br/>
</x,y<=n,></span>
