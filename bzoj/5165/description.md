
# Description

<div class="content"><div>现有一棵树。您需要写一个树上倍增算法，以实现如下操作：</div>
<div>A x 新建一个节点，将它作为x节点的儿子，编号为当前节点总数+1。</div>
<div>Q k p1 p2 p3.... 查询p1,p2,p3...这些节点的LCA。其中k表示查询节点的个数。</div>
<div>最初树上只有一个节点，编号为1。 </div>
<div>多个节点的LCA定义为：这些节点的公共祖先中深度最大的。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行，一个正整数，表示操作个数。 </div>
<div>接下来行，每行输入一个操作，格式如题目描述所述。</div>
<div>保证任何输入的数都是正整数。</div>
<div>n≤3000000 k≤1000。</div>
<div>保证询问不超过1000次</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每一个Q操作，输出一行一个正整数，表示所询问节点的LCA。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
A 1<br/>
A 2<br/>
A 3<br/>
A 1<br/>
A 5<br/>
A 5<br/>
Q 2 3 6<br/>
Q 2 6 7<br/>
Q 2 4 2<br/>
Q 3 7 6 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
5<br/>
2<br/>
5<br/>
解释<br/>
3,6的LCA是1。 <br/>
6,7的LCA是5。 <br/>
4,2的LCA是2。 <br/>
7,6,5的LCA是5。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=ruanxingzhi版权所有">ruanxingzhi版权所有</a></p></div>

