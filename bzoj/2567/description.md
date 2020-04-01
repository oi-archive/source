
# Description

<div class="content"><div style="background: white" align="left"><span style="font-size: medium"><span style="color: #200000">　　小</span><span style="color: #200000">H</span><span style="color: #200000">去美国假期实践的时候遇到了一件很有趣的事情。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　话说小</span><span style="color: #200000">H</span><span style="color: #200000">的导师家的别墅后，有一块很大的草坪。本来这是一件很和美的事情。但是，草坪的后面就是一块小森林，森林里面的兔子总是跑到草坪上来吃草。当然了，吃些草倒是没什么，但是兔子们总是将他们的排泄物留在草坪上，使得主人家的两只牧羊犬吃了它们的排泄物之后总是拉肚子。于是，小</span><span style="color: #200000">H</span><span style="color: #200000">的导师需要建一道篱笆，将后院的草坪围起来。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　篱笆销售商已经将一些标准大小的篱笆放置在草坪的边界上了。这些篱笆的长度足够覆盖整个草坪的边界，但是现在的摆放却留下了很多的空隙。然而篱笆既重又难以放置，每次放下都会毁坏一些草。因此，小</span><span style="color: #200000">H</span><span style="color: #200000">及其同伴希望找出一组篱笆的放置方法，使得所有篱笆中移动最远的一段，移动的距离最少。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　抽象来说，草坪的边界可以看做一个</span><span style="color: #200000">[0,L]</span><span style="color: #200000">的区间，既有可能是一条直线，又有可能是环形的。每块篱笆的中点为</span><span style="color: #200000">C_i</span><span style="color: #200000">，可以覆盖</span><span style="color: #200000">[C_i-r,C_i+r]</span><span style="color: #200000">的范围（环形的情况类似）。我们希望移动后的篱笆覆盖的区间包含整个边界。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　由于篱笆销售商提供的篱笆数量比较多，小</span><span style="color: #200000">H</span><span style="color: #200000">及其同伴希望知道，对于询问（</span><span style="color: #200000">X</span><span style="color: #200000">，</span><span style="color: #200000">Y</span><span style="color: #200000">），如果只是用编号为</span><span style="color: #200000">X</span><span style="color: #200000">到</span><span style="color: #200000">Y</span><span style="color: #200000">的篱笆，这个最短的移动距离是多少。这样他们就可以将多余的篱笆退回，毕竟浪费可耻嘛</span><span style="color: #200000">~~</span><span style="color: #200000">。</span></span></div></div>

# Input

<div class="content"><div style="background: white" align="left"><span style="font-size: medium"><span style="color: #200000">　　输入文件的第一行是一个整数</span><span style="color: #200000">T</span><span style="color: #200000">，为测试数据组数。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　对于每组数据，第一行有</span><span style="color: #200000">5</span><span style="color: #200000">个整数</span><span style="color: #200000">N</span><span style="color: #200000">、</span><span style="color: #200000">L</span><span style="color: #200000">、</span><span style="color: #200000">r</span><span style="color: #200000">、</span><span style="color: #200000">Q</span><span style="color: #200000">和</span><span style="color: #200000">K</span><span style="color: #200000">，分别表示篱笆的数量、草坪边界的长度、和每段篱笆的半径，询问数，和边界的类型（</span><span style="color: #200000">K=1</span><span style="color: #200000">表示边界是一条直线，</span><span style="color: #200000">K=2</span><span style="color: #200000">表示边界是环形的）。保证有</span><span style="color: #200000">2rN≥L</span><span style="color: #200000">。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　接下来一行有</span><span style="color: #200000">N</span><span style="color: #200000">个整数，表示</span><span style="color: #200000">C_i</span><span style="color: #200000">的值，以升序给出。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　随后有</span><span style="color: #200000">Q</span><span style="color: #200000">行，每行</span><span style="color: #200000">2</span><span style="color: #200000">个整数</span><span style="color: #200000">X</span><span style="color: #200000">和</span><span style="color: #200000">Y</span><span style="color: #200000">，表示一组询问。保证</span><span style="color: #200000">X≤Y</span><span style="color: #200000">且篱笆数量足够多覆盖整个边界。</span></span></div></div>

# Output

<div class="content"><div style="background: white" align="left"><span style="font-size: medium"><span style="color: #200000">　　对于每组数据，首先在第一行中给出一个实数，表示移动最远的篱笆需要移动的距离。随后对于每组询问，在单独的一行中给出对应的结果。所有结果精确到小数点后</span><span style="color: #200000">5</span><span style="color: #200000">位。</span></span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
6 8 1 2 1<br/>
1 1 2 3 4 5<br/>
1 5<br/>
3 6<br/>
6 8 1 2 2<br/>
1 1 2 3 4 5<br/>
1 5<br/>
3 6<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2.00000<br/>
3.00000<br/>
2.00000<br/>
1.00000<br/>
1.50000<br/>
1.50000<br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据约定<br/><br/>
　　时间限制：2秒。<br/><br/>
　　0&lt;L,r≤2^30，0≤C_i≤L。<br/><br/>
　　T=10。<br/><br/>
数据 1 2 3 4 5 6 7 8 9 10 <br/><br/>
K 1 1 1 1 2 2 2 2 2 2 <br/><br/>
N 1100 110000 1100 12000 110 1100 120000 1100 12000 120000 <br/><br/>
Q 0 0 1000 10000 0 0 0 1000 10000 10000</p><br/>
<p> </p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2012国家集训队Round 1 day3">2012国家集训队Round 1 day3</a></p></div>

