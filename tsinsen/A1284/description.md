<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　小H去美国假期实践的时候遇到了一件很有趣的事情。<br/>
　　话说小H的导师家的别墅后，有一块很大的草坪。本来这是一件很和美的事情。但是，草坪的后面就是一块小森林，森林里面的兔子总是跑到草坪上来吃草。当然了，吃些草倒是没什么，但是兔子们总是将他们的排泄物留在草坪上，使得主人家的两只牧羊犬吃了它们的排泄物之后总是拉肚子。于是，小H的导师需要建一道篱笆，将后院的草坪围起来。<br/>
　　篱笆销售商已经将一些标准大小的篱笆放置在草坪的边界上了。这些篱笆的长度足够覆盖整个草坪的边界，但是现在的摆放却留下了很多的空隙。然而篱笆既重又难以放置，每次放下都会毁坏一些草。因此，小H及其同伴希望找出一组篱笆的放置方法，使得所有篱笆中移动最远的一段，移动的距离最少。<br/>
　　抽象来说，草坪的边界可以看做一个[0,L]的区间，既有可能是一条直线，又有可能是环形的。每块篱笆的中点为C_i，可以覆盖[C_i-r,C_i+r]的范围（环形的情况类似）。我们希望移动后的篱笆覆盖的区间包含整个边界。<br/>
　　由于篱笆销售商提供的篱笆数量比较多，小H及其同伴希望知道，对于询问（X，Y），如果只是用编号为X到Y的篱笆，这个最短的移动距离是多少。这样他们就可以将多余的篱笆退回，毕竟浪费可耻嘛~~。</div>
# 输入格式

<div class="pdcont">　　输入文件的第一行是一个整数T，为测试数据组数。<br/>
　　对于每组数据，第一行有5个整数N、L、r、Q和K，分别表示篱笆的数量、草坪边界的长度、和每段篱笆的半径，询问数，和边界的类型（K=1表示边界是一条直线，K=2表示边界是环形的）。保证有2rN≥L。<br/>
　　接下来一行有N个整数，表示C_i的值，以升序给出。<br/>
　　随后有Q行，每行2个整数X和Y，表示一组询问。保证X≤Y且篱笆数量足够多覆盖整个边界。</div>
# 输出格式

<div class="pdcont">　　对于每组数据，首先在第一行中给出一个实数，表示移动最远的篱笆需要移动的距离。随后对于每组询问，在单独的一行中给出对应的结果。所有结果精确到小数点后5位。</div>
# 样例输入

<div class="pddata">2<br/>
6 8 1 2 1<br/>
1 1 2 3 4 5<br/>
1 5<br/>
3 6<br/>
6 8 1 2 2<br/>
1 1 2 3 4 5<br/>
1 5<br/>
3 6</div>
# 样例输出

<div class="pddata">2.00000<br/>
3.00000<br/>
2.00000<br/>
1.00000<br/>
1.50000<br/>
1.50000</div>
# 数据约定

<div class="pdcont">　　时间限制：2秒。<br/>
　　0&lt;L,r≤2^30，0≤C_i≤L。<br/>
　　T=10。<br/>
<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">数据<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">6<br/>
</td><td valign="top" style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">8<br/>
</td><td valign="top" style="border:solid 1.0pt">9<br/>
</td><td valign="top" style="border:solid 1.0pt">10<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">K<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">N<br/>
</td><td valign="top" style="border:solid 1.0pt">1100<br/>
</td><td valign="top" style="border:solid 1.0pt">110000<br/>
</td><td valign="top" style="border:solid 1.0pt">1100<br/>
</td><td valign="top" style="border:solid 1.0pt">12000<br/>
</td><td valign="top" style="border:solid 1.0pt">110<br/>
</td><td valign="top" style="border:solid 1.0pt">1100<br/>
</td><td valign="top" style="border:solid 1.0pt">120000<br/>
</td><td valign="top" style="border:solid 1.0pt">1100<br/>
</td><td valign="top" style="border:solid 1.0pt">12000<br/>
</td><td valign="top" style="border:solid 1.0pt">120000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt"><i>Q</i><br/>
</td><td valign="top" style="border:solid 1.0pt">0<br/>
</td><td valign="top" style="border:solid 1.0pt">0<br/>
</td><td valign="top" style="border:solid 1.0pt">1000<br/>
</td><td valign="top" style="border:solid 1.0pt">10000<br/>
</td><td valign="top" style="border:solid 1.0pt">0<br/>
</td><td valign="top" style="border:solid 1.0pt">0<br/>
</td><td valign="top" style="border:solid 1.0pt">0<br/>
</td><td valign="top" style="border:solid 1.0pt">1000<br/>
</td><td valign="top" style="border:solid 1.0pt">10000<br/>
</td><td valign="top" style="border:solid 1.0pt">10000<br/>
</td></tr></tbody></table></div>

</div>