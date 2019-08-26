
# Description

<div class="content"><div>给你一棵树，点带权，且以点1为根。有这么一个游戏：从根开始，每次拿出一个点，然后在它和它的所有儿子中</div>
<div>随机选择一个点(每个点的概率相同)。若这个点是当前拿出的点，游戏结束且你获得其点权的分数；否则拿出该点</div>
<div>，然后重复上述过程。</div>
<div>现在你要算出这个游戏的期望得分，而且要满足两个操作：</div>
<div>操作1：修改某个点的权值。</div>
<div>操作2：将某个节点为根的子树转移到另一个节点的下方。</div>
<div></div>
<p></p>
<p></p></div>

# Input

<div class="content"><div>输入数据第一行包含一个数n,m，表示点的个数和操作个数。</div>
<div>第二行包含n个整数，表示每个点的点权。</div>
<div>接下来n行每行两个数，表示一条树边的两个端点。</div>
<div>在接下来m行每行3个数字type,x,y。表示一个操作。</div>
<div>若type=0，则表示将点x的权值修改成y；否则表示将x为根的子树转移到y下方。</div>
<div>(若y是x的后辈，则视为没有操作。)</div>
<div>n,m&lt;=200000。</div>
<div></div></div>

# Output

<div class="content"><div>对于每次操作，都输出操作过后进行游戏的期望得分。</div>
<div>注意：为了防止精度误差，这里将答案对10^9+7取模，并把除法看成是乘逆元。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
2 3 3 4 4<br/>
1 2<br/>
1 3<br/>
2 4<br/>
2 5<br/>
0 3 1<br/>
1 2 3<br/>
1 5 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">222222226<br/>
166666670<br/>
416666672</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

