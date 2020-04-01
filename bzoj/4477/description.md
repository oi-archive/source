
# Description

<div class="content"><p>萌萌买了一颗字符串树的种子，春天种下去以后夏天就能长出一棵很大的字<br/>
符串树。字符串树很奇特，树枝上都密密麻麻写满了字符串，看上去很复杂的样<br/>
子。<br/>
【问题描述】<br/>
字符串树本质上还是一棵树，即N个节点N-1条边的连通无向无环图，节点<br/>
从1到N编号。与普通的树不同的是，树上的每条边都对应了一个字符串。萌萌<br/>
和JYY在树下玩的时候，萌萌决定考一考JYY。每次萌萌都写出一个字符串S和<br/>
两个节点U,V，需要JYY立即回答U和V之间的最短路径（即,之间边数最少的<br/>
路径。由于给定的是一棵树，这样的路径是唯一的）上有多少个字符串以为前<br/>
缀。<br/>
JYY虽然精通编程，但对字符串处理却不在行。所以他请你帮他解决萌萌的难题。</p></div>

# Input

<div class="content"><p>输入第一行包含一个整数N，代表字符串树的节点数量。<br/>
接下来N-1行，每行先是两个数U,V，然后是一个字符串S,表示节点和U节<br/>
点V之间有一条直接相连的边，这条边上的字符串是S。输入数据保证给出的是一<br/>
棵合法的树。<br/>
接下来一行包含一个整数Q，表示萌萌的问题数。<br/>
接来下Q行，每行先是两个数U,V，然后是一个字符串S,表示萌萌的一个问<br/>
题是节点U和节点V之间的最短路径上有多少字符串以S为前缀。<br/>
输入中所有字符串只包含a-z的小写字母。<br/>
1&lt;=N,Q&lt;=100,000，且输入所有字符串长度不超过10。</p></div>

# Output

<div class="content"><p>输出Q行，每行对应萌萌的一个问题的答案。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 2 ab<br/>
2 4 ac<br/>
1 3 bc<br/>
3<br/>
1 4 a<br/>
3 4 b<br/>
3 2 ab</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1<br/>
1 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

