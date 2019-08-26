
# Description

<div class="content"><div>小A走到一个山脚下，准备给自己造一个小屋。这时候，小A的朋友（op，又叫管理员）打开了创造模式，然后飞到</div>
<div>山顶放了格水。于是小A面前出现了一个瀑布。作为平民的小A只好老实巴交地爬山堵水。那么问题来了：我们把这</div>
<div>个瀑布看成是一个n个节点的树，每个节点有权值（爬上去的代价）。小A要选择一些节点，以其权值和作为代价将</div>
<div>这些点删除（堵上），使得根节点与所有叶子结点不连通。问最小代价。不过到这还没结束。小A的朋友觉得这样</div>
<div>子太便宜小A了，于是他还会不断地修改地形，使得某个节点的权值发生变化。不过到这还没结束。小A觉得朋友做</div>
<div>得太绝了，于是放弃了分离所有叶子节点的方案。取而代之的是，每次他只要在某个子树中（和子树之外的点完全</div>
<div>无关）。于是他找到你。</div></div>

# Input

<div class="content"><p> 输入文件第一行包含一个数n，表示树的大小。</p>
<div>接下来一行包含n个数，表示第i个点的权值。</div>
<div>接下来n-1行每行包含两个数fr，to。表示书中有一条边（fr，to）。</div>
<div>接下来一行一个整数，表示操作的个数。</div>
<div>接下来m行每行表示一个操作，若该行第一个数为Q，则表示询问操作，后面跟一个参数x，表示对应子树的根；若</div>
<div>为C，则表示修改操作，后面接两个参数x，to，表示将点x的权值加上to。</div>
<div>n&lt;=200000，保证任意to都为非负数</div></div>

# Output

<div class="content"><p> 对于每次询问操作，输出对应的答案，答案之间用换行隔开。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
4 3 2 1<br/>
1 2<br/>
1 3<br/>
4 2<br/>
4<br/>
Q 1<br/>
Q 2<br/>
C 4 10<br/>
Q 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
1<br/>
4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

