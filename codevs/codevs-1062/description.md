<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    在网络通信中，经常需要求最短路径。但完全用最短路径传输有这样一个问题：如果最终在两个终端节点之间给出的最短路径只有一条。则在该路径中的任一个节点或链路出现故障时，信号传输将面临中断的危险。因此，对网络路由选择作了以下改进：</p>
<p>为任意两节点之间通信提供三条路径供其选择，即最短路径、第二最短路径和第三最短路径。</p>
<p>    第一最短路径定义为：给定一个不含负回路的网络D={V，A，W}，其中V={v1，v2，…，vn}，A为边的集合，W为权的集合，设P1是D中最短（v1，vn）路。称P1为D中最短（v1，vn）路径，如果D中有一条（v1，vn）路，P2满足以下条件：</p>
<p>（1）P2≠P1；（2）D中不存在异于P1的路P，使得：</p>
<p>（3）W（P1）≤W（P）&lt;W（P2）</p>
<p>则称P2为D的第二最短路径。</p>
<p>    第三最短路径的定义为：设P2是D中第二最短（v1，vn）路径，如果D中有一条（v1，vn）路P3满足以下条件：</p>
<p>（1）P3≠P2并且P3≠P1；（2）D中不存在异于P1，P2的路P，使得：</p>
<p>（3）W（P2）≤W（P）&lt;W（P3）</p>
<p>则称P3为D中第三最短路径。</p>
<p>    现给定一有N个节点的网络，N≤30，求给定两点间的第一、第二和第三最短路径。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入：  n  S  T  Max   （每格数值之间用空格分隔）</p>
<p>        M11  M12  …  M1n</p>
<p>        M21  M22  …  M2n</p>
<p>              …   … </p>
<p>        Mn1  Mn2  …  Mnn</p>
<p>    其中，n为节点数，S为起点，T为终点，Max为一代表无穷大的整数，Mij描述I到J的距离，若Mij=Max，则表示从I到J无直接通路，Mii=0。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出：三条路径(从小到大输出)，每条路径占一行，形式为：路径长度 始点&hellip;终点&nbsp; （中间用一个空格分隔）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5  1       5     10000                               </p>
<p>0         1         3         10000     7          </p>
<p>10000     0          1         10000     10000       </p>
<p>10000     10000     0         1         4</p>
<p>10000     10000     10000     0        1</p>
<p>10000     1         10000     10000     0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4  1  2  3  4  5</p>
<p>5  1  3  4  5</p>
<p>6  1  2  3  5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>