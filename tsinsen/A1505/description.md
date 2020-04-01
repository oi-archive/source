<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给定一棵N个节点的树，每个点有一个权值，有M个询问(a,b,c)若a 为1，回答b到c路径上的最小权值，若a为2，回答b到c路径上的最大权值，若a为3，回答b到c路径上的所有权值的中位数，k个数的中位数定义为从0到k-1编号从小到大排序后k/2号的那个数。</div>
# 输入格式

<div class="pdcont">　　第一行两个整数N，M<br/>
　　第二行N个整数，v[1]~v[n]，代表每个节点的权值。<br/>
　　接下来N-1行每行两个整数x，y代表x和y有一条边<br/>
　　最后M行每行三个整数a，b，c，表示一组询问。</div>
# 输出格式

<div class="pdcont">　　共M行，每行一个整数，代表询问的答案。</div>
# 样例输入

<div class="pddata">5 3<br/>
1 3 2 4 5<br/>
1 2<br/>
2 4<br/>
4 3<br/>
4 5<br/>
1 1 5<br/>
2 1 3<br/>
3 1 5</div>
# 样例输出

<div class="pddata">1<br/>
4<br/>
4</div>
# 数据规模和约定

<div class="pdcont">　　共20个数据<br/>
　　数据1~3   N,M&lt;=1000<br/>
　　数据4~6   N,M&lt;=5000<br/>
　　数据7~10  N,M&lt;=10000<br/>
　　数据11~18  N,M&lt;=30000<br/>
　　数据19~20  N,M&lt;=100000</div>

</div>