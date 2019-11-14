
# Description

<div class="content"><div>给一个包含n个点，m条边的无向连通图。从顶点1出发，往其余所有点分别走一次并返回。</div>
<div>往某一个点走时，选择总长度最短的路径走。若有多条长度最短的路径，则选择经过的顶点序列字典序最小的那条路径(如路径A为1,32,11，路径B为1,3,2,11，路径B字典序较小。注意是序列的字典序的最小，而非路径中节点编号相连的字符串字典序最小)。到达该点后按原路返回，然后往其他点走，直到所有点都走过。</div>
<div>可以知道，经过的边会构成一棵最短路径树。请问，在这棵最短路径树上，最长的包含K个点的简单路径长度为多长？长度为该最长长度的不同路径有多少条？</div>
<div>这里的简单路径是指：对于一个点最多只经过一次的路径。不同路径是指路径两端端点至少有一个不同，点A到点B的路径和点B到点A视为同一条路径。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行输入三个正整数n,m，K，表示有n个点m条边，要求的路径需要经过K个点。接下来输入m行，每行三个正整数Ai,Bi,Ci(1&lt;=Ai,Bi&lt;=n,1&lt;=Ci&lt;=10000)，表示Ai和Bi间有一条长度为Ci的边。数据保证输入的是连通的无向图。</div>
<div>
<div></div>
</div>
<div>
<p></p>
</div></div>

# Output

<div class="content"><div>输出一行两个整数，以一个空格隔开，第一个整数表示包含K个点的路径最长为多长，第二个整数表示这样的不同的最长路径有多少条。</div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 6 4<br/>
1 2 1<br/>
2 3 1<br/>
3 4 1<br/>
2 5 1<br/>
3 6 1<br/>
5 6 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 4</span></div>

# Hint

<div class="content"><p></p><div>对于所有数据n&lt;=30000,m&lt;=60000，2&lt;=K&lt;=n。</div><br/>
<div>数据保证最短路径树上至少存在一条长度为K的路径。</div><br/>
<div>2016.12.7新加数据一组by - wyx-150137</div><br/>
<p></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

