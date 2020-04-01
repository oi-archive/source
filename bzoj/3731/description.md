
# Description

<div class="content"><p>我曾在青山之中遇过你，</p>
<p>新竹做杖，鬓插紫茱萸。</p>
<p>跣足踏过无边丝雨，</p>
<p>又拾起燕川雪片片落如席……</p>
<p><br/>
Gty神(xian)犇(chong)从来不缺妹子……</p>
<p>他又来到了一棵妹子树下，发现每个妹子有一个美丽度……</p>
<p>由于Gty很 哲♂学 也很 机♂智，他只对美丽度大于某个值的妹子感兴趣。</p>
<p>他想知道某个子树中美丽度大于x的妹子个数。</p>
<p>某个妹子的美丽度可能发生变化……</p>
<p>树上可能会出现一只新的妹子……</p>
<p><br/>
但是……树枝可能会断裂，于是，Gty惊讶地发现，他的面前变成了一片妹子树组成的森林……</p>
<p><br/>
维护一棵初始有n个节点的有根树(根节点为1)，树上节点编号为1-n，每个点有一个权值wi。它可能会变成森林。</p>
<p>支持以下操作：</p>
<p>0 u x          询问以u为根的子树中，严格大于x的值的个数。(u^=lastans,x^=lastans)</p>
<p>1 u x          把u节点的权值改成x。(u^=lastans,x^=lastans)</p>
<p>2 u x          添加一个编号为&#34;当前树中节点数+1&#34;的节点，其父节点为u，其权值为x。(u^=lastans,x^=lastans)</p>
<p>3 u            删除节点u与其父节点之间的路径。此时u的父节点变成叶子节点，u变成分裂出的树的根。(u^=lastans)</p>
<p>最开始时lastans=0。<br/>
</p></div>

# Input

<div class="content"><p>输入第一行包括一个正整数n(1&lt;=n&lt;=100000)，代表树上的初始节点数。</p>
<p>接下来n-1行，每行2个整数u,v，为树上的一条无向边。</p>
<p>任何时刻，树上的任何权值大于等于0，且两两不同。</p>
<p>接下来1行，包括n个整数wi，表示初始时每个节点的权值。</p>
<p>接下来1行，包括1个整数m(1&lt;=m&lt;=100000)，表示操作总数。</p>
<p>接下来m行，每行最开始包括一个整数op,</p>
<p>若op=3，该行还会有一个整数u；</p>
<p>若op不等于3，该行还会有两个整数u,x；</p>
<p>op,u,x的范围见题目描述。</p>
<p>保证题目涉及的所有数在int内。<br/>
</p></div>

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

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p><p>数据范围见描述。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

