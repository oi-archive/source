
# Description

<div class="content"><p>一天，白神和他的伙伴喵喵一起走到了可以产生魔法的神奇世界。但是这个世界产生魔法有这样一个有趣的方法。在一个无向图，有N个城镇，M条道路，并且每一条道路有一个权值（不超过10^18 ）。每次从1号城镇出发，随意一条有限长度的路径，一条路可以经过多次，所经过的边将权值xor起来，若xor值不为0，则算新产生一种魔法（一个xor值对应唯一的魔法）。注意：一条边经过几次，就要xor几次）。<br/>
喵喵觉得这样太没有意思了，就在想假如我删除一些边这个世界的魔法总数还会有多少呢？喵喵可不会一下删完，他会进行Q次删边操作，每次只会删除一条边，他想知道每删除一条边，剩余的魔法种数有多少。</p></div>

# Input

<div class="content"><p>第一行3个整数，表示N个节点，M条边，之后删除Q次边。<br/>
接下来M行表示A B 之间有一条U权值的边<br/>
在接下来Q行，表示删除第编号为A的边</p></div>

# Output

<div class="content"><p>一共Q+1行，每行一个整数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3 2<br/>
1 2 1<br/>
2 3 2<br/>
3 1 4<br/>
1<br/>
3</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
2<br/>
0</span></div>

# Hint

<div class="content"><p></p><p>所有数据保证该无向图不含重边、自环。<br/><br/>
所有数据保证不会有一条边被删除多次，即对于不同i和j，有Disi≠Disj<br/><br/>
N ≤ 5000，M ≤ 20000，Q ≤20000，U≤10^18；<br/><br/>
<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

