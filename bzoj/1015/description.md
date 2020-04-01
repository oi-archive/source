
# Description

<div class="content"><p>　　很久以前，在一个遥远的星系，一个黑暗的帝国靠着它的超级武器统治者整个星系。某一天，凭着一个偶然的<br/>
机遇，一支反抗军摧毁了帝国的超级武器，并攻下了星系中几乎所有的星球。这些星球通过特殊的以太隧道互相直<br/>
接或间接地连接。 但好景不长，很快帝国又重新造出了他的超级武器。凭借这超级武器的力量，帝国开始有计划<br/>
地摧毁反抗军占领的星球。由于星球的不断被摧毁，两个星球之间的通讯通道也开始不可靠起来。现在，反抗军首<br/>
领交给你一个任务：给出原来两个星球之间的以太隧道连通情况以及帝国打击的星球顺序，以尽量快的速度求出每<br/>
一次打击之后反抗军占据的星球的连通快的个数。（如果两个星球可以通过现存的以太通道直接或间接地连通，则<br/>
这两个星球在同一个连通块中）。</p></div>

# Input

<div class="content"><p>　　输入文件第一行包含两个整数，N (1  &lt; =  N  &lt; =  2M) 和M (1  &lt; =  M  &lt; =  200,000)，分别表示星球的<br/>
数目和以太隧道的数目。星球用 0 ~ N-1的整数编号。接下来的M行，每行包括两个整数X, Y，其中（0 &lt; = X &lt;&gt; <br/>
Y 表示星球x和星球y之间有“以太”隧道，可以直接通讯。接下来的一行为一个整数k，表示将遭受攻击的星球的<br/>
数目。接下来的k行，每行有一个整数，按照顺序列出了帝国军的攻击目标。这k个数互不相同，且都在0到n-1的范<br/>
围内。</p></div>

# Output

<div class="content"><p>第一行是开始时星球的连通块个数。接下来的K行，每行一个整数，表示经过该次打击后现存星球<br/>
的连通块个数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">8 13<br/>
0 1<br/>
1 6<br/>
6 5<br/>
5 0<br/>
0 6<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 5<br/>
7 1<br/>
7 2<br/>
7 6<br/>
3 6<br/>
5<br/>
1<br/>
6<br/>
3<br/>
5<br/>
7</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
1<br/>
1<br/>
2<br/>
3<br/>
3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

