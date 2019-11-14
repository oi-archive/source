<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给定一棵大小为 n 的有根点权树,支持以下操作:<br/>
　　• 换根<br/>
　　• 修改点权<br/>
<br/>
<br/>
　　• 查询子树最小值</div>
# 输入格式

<div class="pdcont">　　第一行两个整数 n, Q ,分别表示树的大小和操作数。<br/>
　　接下来n行,每行两个整数f,v,第i+1行的两个数表示点i的父亲和点i的权。保证f &lt; i。如 果f = 0,那么i为根。输入数据保证只有i = 1时,f = 0。<br/>
<br/>
<br/>
<br/>
　　接下来 m 行,为以下格式中的一种:<br/>
　　• V x y表示把点x的权改为y<br/>
<br/>
　　• E x 表示把有根树的根改为点 x<br/>
<br/>
<br/>
<br/>
<br/>
　　• Q x 表示查询点 x 的子树最小值</div>
# 输出格式

<div class="pdcont">　　对于每个 Q ,输出子树最小值。</div>
# 样例输入

<div class="pddata">3 7<br/>
0 1<br/>
1 2<br/>
1 3<br/>
Q 1<br/>
V 1 6<br/>
Q 1<br/>
V 2 5<br/>
Q 1<br/>
V 3 4<br/>
Q 1</div>
# 样例输出

<div class="pddata">1<br/>
2<br/>
3<br/>
4</div>
# 数据规模和约定

<div class="pdcont">　　对于 20% 的数据:n, Q ≤ 100；<br/>
　　对于其余 30% 的数据:没有换根操作；<br/>
　　对于 100% 的数据:n, Q ≤ 10^5。</div>

</div>