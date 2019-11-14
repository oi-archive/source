
# Description

<div class="content"><div>设T 为一棵有根树，我们做如下的定义：</div>
<div>? 设a和b为T 中的两个不同节点。如果a是b的祖先，那么称“a比b不知道</div>
<div>高明到哪里去了”。</div>
<div>? 设a 和 b 为 T 中的两个不同节点。如果 a 与 b 在树上的距离不超过某个给定</div>
<div>常数x，那么称“a 与b 谈笑风生”。</div>
<div>给定一棵n个节点的有根树T，节点的编号为1 到 n，根节点为1号节点。你需</div>
<div>要回答q 个询问，询问给定两个整数p和k，问有多少个有序三元组(a;b;c)满足：</div>
<div>1. a、b和 c为 T 中三个不同的点，且 a为p 号节点；</div>
<div>2. a和b 都比 c不知道高明到哪里去了；</div>
<div>3. a和b 谈笑风生。这里谈笑风生中的常数为给定的 k。</div></div>

# Input

<div class="content"><div>
<div>第一行含有两个正整数n和q，分别代表有根树的点数与询问的个数。</div>
<div>接下来n - 1行，每行描述一条树上的边。每行含有两个整数u和v，代表在节点u和v之间有一条边。</div>
<div>接下来q行，每行描述一个操作。第i行含有两个整数，分别表示第i个询问的p和k。</div>
<div>1&lt;=P&lt;=N</div>
<div>1&lt;=K&lt;=N</div>
<div>N&lt;=300000</div>
<div>Q&lt;=300000</div>
</div>
<div></div></div>

# Output

<div class="content"><p>输出 q 行，每行对应一个询问，代表询问的答案。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
1 2<br/>
1 3<br/>
2 4<br/>
4 5<br/>
2 2<br/>
4 1<br/>
2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
1<br/>
3</span></div>

# Hint

<div class="content"><p></p><p><span style="font-family: arial, verdana, helvetica, sans-serif;">Hint:边要加双向</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

