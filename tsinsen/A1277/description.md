<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给定一个边带正权的连通无向图G=(V,E)，其中N=|V|，M=|E|，N个点从1到N依次编号，给定三个正整数u，v，和L (u≠v)，假设现在加入一条边权为L的边(u,v)，那么需要删掉最少多少条边，才能够使得这条边既可能出现在最小生成树上，也可能出现在最大生成树上？</div>
# 输入格式

<div class="pdcont">　　第一行包含用空格隔开的两个整数，分别为N和M；<br/>
　　接下来M行，每行包含三个正整数u，v和w表示图G存在一条边权为w的边(u,v)。<br/>
　　最后一行包含用空格隔开的三个整数，分别为u，v，和 L；<br/>
　　数据保证图中没有自环。</div>
# 输出格式

<div class="pdcont">　　输出一行一个整数表示最少需要删掉的边的数量。</div>
# 样例输入

<div class="pddata">3 2<br/>
3 2 1<br/>
1 2 3<br/>
1 2 2</div>
# 样例输出

<div class="pddata">1</div>
# 样例说明

<div class="pdcont">　　我们只需把边(1,2)删除即可，删除并加入新边之后，图中的生成树唯一。</div>
# 数据规模和约定

<div class="pdcont">　　对于20%的数据满足N ≤ 10，M ≤ 20，L ≤ 20；<br/>
　　对于50%的数据满足N ≤ 300，M ≤ 3000，L ≤ 200；<br/>
　　对于100%的数据满足N ≤ 20000，M ≤ 200000，L ≤ 20000。</div>

</div>