
# Description

<div class="content"><div><span style="font-size: medium">虽然春希将信息传递给了雪菜，但是雪菜却好像完全不认得春希了。心急如焚的春希打开了第二世代机能，对雪菜的脑内芯片进行了直连-hack。</span></div>
<div><span style="font-size: medium">进入到雪菜内部的春希发现（这什么玩意。。），雪菜的脑部结构被分成了n个块落，并且一些块落之间被有向边连接着。由于四分五裂的脑部，雪菜关于春希的记忆也完全消失，春希为了恋人，启动了inversionprocess.</span></div>
<div><span style="font-size: medium">在inversion process中，要想使雪菜回到正常状态，需要纳米机器人的帮助。纳米机器人可以从任意一个可以作为起点的块落出发进行修复，也可以在任意一个可以作为终点的块落结束修复（并不是到了某个终点就一定要停止）。春希希望所有的节点都能被修复(只要纳米机器人到过该点就算修复过)，这样才能让雪菜重获新生。</span></div>
<div style="text-indent: 12pt"><span style="font-size: medium">作为纳米机器人1号的你能帮助春希算算至少需要多少个机器人才能拯救雪菜吗？</span></div>
<div style="text-indent: 12pt"><span style="font-size: medium">当然，如果无论如何都无法使得春希的愿望被满足的话，请输出”no solution”（不包括引号）</span></div></div>

# Input

<div class="content"><div style="text-indent: 18pt"><span style="font-size: medium">题目包含多组数据</span></div>
<div><span style="font-size: medium">第1行有一个正整数t，表示数据的组数。</span></div>
<div><span style="font-size: medium">第2行有两个正整数n、m，a，b，分别表示块落的数量、有向边的数量、起点的数量、终点的数量。</span></div>
<div><span style="font-size: medium">第3行有a个正整数，表示可以作为起点的块落。</span></div>
<div><span style="font-size: medium">第4行有b个正整数，表示可以作为终点的块落。</span></div>
<div><span style="font-size: medium">第5行至第m+4行，每行有两个正整数u、v，表示能从编号为u的块落到编号为v的块落。</span></div>
<div><span style="font-size: medium">之后以此类推。</span></div></div>

# Output

<div class="content"><div style="text-indent: 12pt"><span style="font-size: medium">输出共有t行，每行输出对应数据的答案。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
2<br/>
2 1 1 1<br/>
1<br/>
2<br/>
2 1<br/>
3 2 3 3<br/>
1 2 3<br/>
1 2 3<br/>
1 2<br/>
1 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
no solution<br/>
2<br/>
【数据规模和约定】<br/>
对于30%的数据，满足n &lt;= 10, m &lt;= 100。<br/>
对于60%的数据，满足n &lt;= 200, m &lt;= 5000。<br/>
对于100%的数据，满足t&lt;=10,n &lt;= 1000, m &lt;= 10000。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

