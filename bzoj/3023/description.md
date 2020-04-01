
# Description

<div class="content"><p><span style="font-size: medium">给定一个有向图，每个节点关联于一群人。这N群人按照某个特定的顺序进行以下操作：<br/>
到达并占领他们关联的节点；<br/>
从他们占领的某个节点u出发，走到与其相邻的每个点v。如果点v已经被人占领，他们会边(u,v)上发生冲突，并不再在这个方向上前进；否则，他们会占领点v，并重复这一步，直到没有能到达的点为止。<br/>
如果他们关联的节点在此前被别的人群占领，他们不会与那群人发生冲突。在这种情况下，他们什么都不做。<br/>
给定该图，以及发生冲突的边集。求一种人群的行动顺序，使得发生冲突的边集与输入相符。<br/>
以样例为例。关联于点8的人群首先行动，占领点8；接下来关联于点5的人群行动，占领点4,5,6（与4相连的点集）；关联于点6的人群出动，因为点6已经被占领，他们什么都不做；人群2占领点2,3；人群3什么都不做；人群1占领点1，并在边&lt;1,4&gt;和&lt;1,8&gt;上引发冲突；人群7占领点7并在边&lt;7,1&gt;和&lt;7,4&gt;上引发冲突；人群4什么都不做。<br/>
注意合法的顺序可能不止一种；样例中，(2, 3, 8, 4, 1, 7, 5, 6)也是一种合法的方案。注意(8, 5, 6, 3, 2, 1, 7, 4)不是合法的方案，因为按照这个方案，&lt;2,3&gt;上也会发生冲突，与输入不符。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">输入的第一行包含两个整数N,M，含义是点数和边数。<br/>
接下来M行，每行三个整数A,B,C，表示有向边A-&gt;B，如果C=1，则这条边上发生了冲突。<br/>
N&lt;=20000,M&lt;=200000。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">输出一个排列，表示人群的行动顺序。<br/>
如果没有任何顺序满足题意，输出-1。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">8 9<br/>
1 4 1<br/>
1 8 1<br/>
2 3 0<br/>
5 6 0<br/>
6 5 0<br/>
7 4 1<br/>
6 4 0<br/>
7 1 1<br/>
4 5 0<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8 5 6 2 3 1 7 4<br/>
</span></div>

# Hint

<div class="content"><p></p><p><a href="http://61.187.179.132/JudgeOnline/userinfo.php?user=Dragonite"><font color="#0000ff">Dragonite</font></a>提供SPJ</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

