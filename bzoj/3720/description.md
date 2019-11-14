
# Description

<div class="content"><p>我曾在弦歌之中听过你，<br/>
<br/>
檀板声碎，半出折子戏。<br/>
<br/>
舞榭歌台被风吹去，<br/>
<br/>
岁月深处尚有余音一缕……<br/>
<br/>
<br/>
Gty神(xian)犇(chong)从来不缺妹子……<br/>
<br/>
他来到了一棵妹子树下，发现每个妹子有一个美丽度……<br/>
<br/>
由于Gty很哲♂学，他只对美丽度大于某个值的妹子感兴趣。<br/>
<br/>
他想知道某个子树中美丽度大于k的妹子个数。<br/>
<br/>
某个妹子的美丽度可能发生变化……<br/>
<br/>
树上可能会出现一只新的妹子……<br/>
<br/>
<br/>
维护一棵初始有n个节点的有根树(根节点为1)，树上节点编号为1-n，每个点有一个权值wi。<br/>
<br/>
支持以下操作：<br/>
<br/>
0 u x          询问以u为根的子树中，严格大于x的值的个数。(u^=lastans,x^=lastans)<br/>
<br/>
1 u x          把u节点的权值改成x。(u^=lastans,x^=lastans)<br/>
<br/>
2 u x          添加一个编号为&#34;当前树中节点数+1&#34;的节点，其父节点为u，其权值为x。(u^=lastans,x^=lastans)<br/>
<br/>
最开始时lastans=0。</p></div>

# Input

<div class="content"><p>输入第一行包括一个正整数n(1&lt;=n&lt;=30000)，代表树上的初始节点数。<br/>
<br/>
接下来n-1行，每行2个整数u,v，为树上的一条无向边。<br/>
<br/>
任何时刻，树上的任何权值大于等于0，且两两不同。<br/>
<br/>
接下来1行，包括n个整数wi，表示初始时每个节点的权值。<br/>
<br/>
接下来1行，包括1个整数m(1&lt;=m&lt;=30000)，表示操作总数。<br/>
<br/>
接下来m行，每行包括三个整数 op,u,v：<br/>
<br/>
op,u,v的含义见题目描述。<br/>
<br/>
保证题目涉及的所有数在int内。</p></div>

# Output

<div class="content"><p>对每个op=0，输出一行，包括一个整数，意义见题目描述。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
1 2<br/>
10 20<br/>
1<br/>
0 1 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
</span></div>

# Hint

<div class="content"><p></p><p> 2017.9.28新加数据一组by GXZlegend,未重测</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Autumn">By Autumn</a></p></div>

