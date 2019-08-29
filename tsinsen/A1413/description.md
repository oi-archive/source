<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　如果一张无向无环图中存在一条路径p，使得图中的任意一个节点与这条路径的距离至多为1，则该图被称为毛毛虫图。<br/>
　　毛毛虫图中可以有自环，但不能有重边。<br/>
　　下图是一个毛毛虫图的例子：<br/>
<img src="source/tsinsen/A1413/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ZFlKN0I5OG0=.do" width="324" height="108"/><br/>
<br/>
<br/>
<br/>
　　给定一张无向图G。你可以执行一些“合并”操作，对于每次“合并”操作，选择两个不同的节点a，b，将a，b这两个节点以及以a点或b点为端点的边从原图中删除。之后插入一个新的节点w，同时，原图中的每条边(a，x)，(b，x)，将被替换为(w，x)。如果原图中存在边(a，b)，将添加一个自环(w，w)。请注意到，每次操作后，图中的节点数将减1，但是边数不变。最终的图中，每对节点间可能有多条边，也有可能有多个自环<br/>
　　现在我们想知道，至少执行多少次“合并”操作，就可以将图G变为一张毛毛虫图。</div>
# 输入格式

<div class="pdcont">　　第一行包含两个整数n，m(1 ≤ n ≤ 2000;0 ≤ m ≤ 10^5)，n表示图中的节点数，m表示图中的边数。接下来m行，每行两个整数ai，bi，(1 ≤ ai， bi ≤ n;ai ≠ bi)，表示图中含有一条无向边(ai，bi)。图中不会含有重边。请注意，给定的图可能是不连通的。</div>
# 输出格式

<div class="pdcont">　　输出至少执行多少次“合并”操作，就可以将图G变为一张毛毛虫图。</div>
# 样例输入

<div class="pddata">4 4<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 2</div>
# 样例输出

<div class="pddata">2</div>
# 数据规模和约定

<div class="pdcont">　　1 ≤ n ≤ 2000<br/>
　　0 ≤ m ≤ 10^5</div>

</div>