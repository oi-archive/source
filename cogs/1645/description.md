# 题目描述


<h3>
【题目描述】
</h3>
<p>
有趣的石子游戏来了！有n堆石子，命名为0，1，2，...，n-1。两名玩家轮流捡石子。每一轮游戏，每名玩家选择三堆石子i,j,k（i&lt;j，j&lt;=k并且i中至少有一枚石子）。然后，这名玩家从第i堆中拿走一枚石子，并向第j堆和第k堆中各放入一枚石子。（如果j=k，就意味着向第j堆中放两枚石子）。无法按规则操作的玩家就输了。
</p>
<p>
David是先手并且他希望赢。你能写一个程序帮助他吗？
</p>
<p>
石子堆数n不超过23.每一堆的石子数不超过1000.假设对手非常聪明，会按照最佳方式操作。
</p>
<h3>
【输入格式】
</h3>
<p>
输入包含多组数据。
</p>
<p>
每组数据有两行。第一行有一个正整数n（1&lt;=n&lt;=23），表示石子堆数。第二行有n个空格隔开的非负整数S0,...,Sn-1（0&lt;=Si&lt;=1000），代表第0堆到第n-1堆的石子数量。
</p>
<p>
输入结束标志为一行一个0.
</p>
<h3>
【输出格式】
</h3>
<p>
对每组数据，按如下格式输出一行“Game t: i j k”。其中t是数据组数，i,j,k代表如果David想赢，他应该在第一步选择的三堆石子。如果有多组i,j,k，输出字典序最小的一组。如果他无法取胜，则i,j,k都是-1.
</p>
<h3>
【样例输入】
</h3>
<p>
4
</p>
<p>
1 0 1 100
</p>
<p>
3
</p>
<p>
1 0 5
</p>
<p>
2
</p>
<p>
2 1
</p>
<p>
0
</p>
<h3>
【样例输出】<br/>
</h3>
<p>
Game 1: 0 2 3
</p>
<p>
Game 2: 0 1 1
</p>
<p>
Game 3: -1 -1 -1
</p>
<h3>
【来源】
</h3>
<p>
<a target="_blank" href="http://uva.onlinejudge.org/index.php?option=com_onlinejudge&amp;Itemid=8&amp;page=show_problem&amp;problem=4124">UVa1378 A Funny Stone Game</a> 
</p>
<p>
<a target="_blank" href="https://icpcarchive.ecs.baylor.edu/index.php?option=com_onlinejudge&amp;Itemid=8&amp;page=show_problem&amp;problem=1669">LA3668 A Funny Stone Game</a> 
</p>
<p>
ACM ICPC 2006 Asia Regional Contest,Beijing: A Funny Stone Game
</p>
