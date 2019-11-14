
# Description

<div class="content"><div>你发行了一种彩票，并且有P人买了它。现在你要决定谁中奖。</div>
<div>你已经决定了用一个有根树来选择优胜者。你需要做的事情被列在下面：</div>
<div>•参与者从1到P连续编号。</div>
<div>•首先，你将树画在一个矩形的白板上，并需要满足以下条件：</div>
<div>–树上的每一个结点对应白板上的一个圆圈。圆圈很小以至于你可以</div>
<div>忽略他们的大小。</div>
<div>–树上的每条边对应连接两个圈的线段。没有两条边相交。</div>
<div>–根节点一定画在白板的最上方。</div>
<div>–对于每个结点，连向它们儿子们的边都要向下走。（换句话说，父亲</div>
<div>必须画在儿子的上方。）</div>
<div>–所有的叶子需画在白板的底边。</div>
<div>•接下来，你将白板的底边分成P段，每个叶子被恰好一条线段包含。将1</div>
<div>到P这些个不同的数字分配给每个线段，然后将数字标注在线段内的叶子上。</div>
<div>•现在，你要重复下述过程：找到一个空结点X，它的所有儿子都标注了数</div>
<div>字；如果有多个这样的结点，随机选择一个；然后在X的儿子中随机选</div>
<div>择一个，将这个儿子的数字标注在X上；当根节点被标上数字时过程结</div>
<div>束。</div>
<div>你会获得整数P和用于描述你使用的树的数组tree。这棵树有N个结点，</div>
<div>从0到N-1编号。结点0是树根。对于每个其他结点，它父亲的编号小于它的</div>
<div>编号。更正式的说，对于在1和N-1之间的i，tree[i]是结点i父亲的编号。</div>
<div>你想要让抽奖公平，即，保证每个参与者有相同的机率赢取大奖。为此，你可以</div>
<div>在合法的要求下选择怎样画这棵树，以及怎样分配数字到叶子上。回答“YES”</div>
<div>（不需要引号）如果抽奖可以公平，否则回答“NO”。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>多组数据，读入到文件结束。</div>
<div>每组数据第一行读入两个整数N和P——所用树的大小以及参与者人数。</div>
<div>第二行读入N-1个整数，描述数组tree；其中第i个整数为tree[i]。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>每组数据输出单独一行一个单词“YES”或“NO”</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
0 0 0<br/>
10 2<br/>
0 0 0 1 1 2 2 3 3<br/>
10 3<br/>
0 0 1 1 2 2 4 4 4<br/>
9 3<br/>
0 0 1 1 1 3 3 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">YES<br/>
YES<br/>
NO<br/>
NO</span></div>

# Hint

<div class="content"><p></p><p>P≤N≤100</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

