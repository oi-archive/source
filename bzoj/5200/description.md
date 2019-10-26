
# Description

<div class="content"><div>一棵Factor-Free Tree是指一棵有根二叉树，每个点包含一个正整数权值，且每个点的权值都与其所有祖先的权值互质。</div>
<div>二叉树中序遍历是指按照左子树-根-右子树的顺序递归遍历二叉树，将每个点的权值依次写下来得到的序列。</div>
<div></div>
<div>给定一个序列a_1,a_2,...,a_n，请判断它是不是可能是某棵Factor-Free Tree的中序遍历序列，如果是的话请给出例子。</div>
<div><img src="/source/bzoj/5200/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMy8xKDEpLmpwZw==.jpg" width="222" height="172" alt=""/></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个正整数n(1&lt;=n&lt;=1000000)。</div>
<div>第二行包含n个正整数a_1,a_2,...,a_n(1&lt;=a_i&lt;=10^7)，表示节点编号为1到n的每个点的权值。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>若不是，输出impossible</div>
<div>否则输出一行n个整数，依次表示序列每一项代表的节点在树中的父亲节点，若是根节点则输出0。</div>
<div>若有多组解，输出任意一组。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
2 7 15 8 9 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 0 4 2 4 5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris提供翻译及SPJ">鸣谢Claris提供翻译及SPJ</a></p></div>

