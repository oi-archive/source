
# Description

<div class="content"><div>网络已经成为当今世界不可或缺的一部分。每天都有数以亿计的人使用网络进行学习、科研、娱乐等活动。然而，</div>
<div>不可忽视的一点就是网络本身有着庞大的运行费用。所以，向使用网络的人进行适当的收费是必须的，也是合理的</div>
<div>。MY市NS中学就有着这样一个教育网络。网络中的用户一共有2N个，编号依次为1, 2, 3, …, 2N。这些用户之间</div>
<div>是用路由点和网线组成的。用户、路由点与网线共同构成一个满二叉树结构。树中的每一个叶子结点都是一个用户</div>
<div>，每一个非叶子结点（灰色）都是一个路由点，而每一条边都是一条网线（见下图，用户结点中的数字为其编号）</div>
<p><img border="0" src="/source/bzoj/1495/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE0OTVfMS5qcGc=.jpg" alt=""/></p>
<div>MY网络公司的网络收费方式比较奇特，称为“配对收费”。即对于每两个用户i, j (1≤i &lt; j ≤2N ) 进行收费。</div>
<div>由于用户可以自行选择两种付费方式A、B中的一种，所以网络公司向学校收取的费用与每一位用户的付费方式有关</div>
<div>。该费用等于每两位不同用户配对产生费用之和。 为了描述方便，首先定义这棵网络树上的一些概念： 祖先：根</div>
<div>结点没有祖先，非根结点的祖先包括它的父亲以及它的父亲的祖先； 管辖叶结点：叶结点本身不管辖任何叶结点</div>
<div>，非叶结点管辖它的左儿子所管辖的叶结点与它的右儿子所管辖的叶结点； 距离：在树上连接两个点之间的用边</div>
<div>最少的路径所含的边数。 对于任两个用户i, j (1≤i)</div>
<p><img border="0" src="/source/bzoj/1495/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE0OTVfMi5qcGc=.jpg" alt=""/></p>
<div>由于最终所付费用与付费方式有关，所以NS中学的用户希望能够自行改变自己的付费方式以减少总付费。然而，由</div>
<div>于网络公司已经将每个用户注册时所选择的付费方式记录在案，所以对于用户i，如果他/她想改变付费方式（由A</div>
<div>改为B或由B改为A），就必须支付Ci元给网络公司以修改档案（修改付费方式记录）。 现在的问题是，给定每个用</div>
<div>户注册时所选择的付费方式以及Ci，试求这些用户应该如何选择自己的付费方式以使得NS中学支付给网络公司的总</div>
<div>费用最少（更改付费方式费用+配对收费的费用）。</div></div>

# Input

<div class="content"><div>
<div>输入文件中第一行有一个正整数N。 第二行有2N个整数，依次表示1号，2号，…，2N号用户注册时的付费方式，每</div>
<div>一个数字若为0，则表示对应用户的初始付费方式为A，否则该数字为1，表示付费方式为B。 第三行有2N个整数，</div>
<div>表示每一个用户修改付费方式需要支付的费用，依次为C1, C2, …,CM 。( M=2N ) 以下2N-1行描述给定的两两用</div>
<div>户之间的流量表F，总第(i + 3)行第j列的整数为Fi, j+i 。（1≤i&lt;2N，1≤j≤2N ? i） 所有变量的含义可以参</div>
<div>见题目描述。N≤10，0≤Fi, j≤500，0≤Ci≤500 000</div>
</div>
<div></div></div>

# Output

<div class="content"><p>你的程序只需要向输出文件输出一个整数，表示NS中学支付给网络公司的最小总费用。（单位：元）</p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
1 0 1 0<br/>
2 2 10 9<br/>
10 1 2<br/>
2 1<br/>
3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
</span></div>

# Hint

<div class="content"><p></p><p>【样例说明】 将1号用户的付费方式由B改为A，NS中学支付给网络公司的费用达到最小</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

