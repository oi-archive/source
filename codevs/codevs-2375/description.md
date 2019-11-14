<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>简单起见，假定总共有 N 个人以及M种不同类型事件。 <br>定义事件之间的二元关系“相关”： <br>相关关系是一个二元关系，就是说我们只能定义两种类型的事件间是否相关； <br>同一种类型的事件之间一定是相关的； <br>若事件 x与事件y是相关的，那么事件 y与事件x也一定是相关的； <br>令Qi=(Qi1,Qi2, .., Qici)表示第 i 个人计划完成的事件序列（称为计划序列），Ci表示Qi的长度。Qi中每个事件Qi,j都是 M种事件中的某一种，且同一种类型的事件可以发生多次。 <br>随着时间的推移每个计划序列中的事件都会发生一次且恰好一次；为了简单起见，不会有任何两个事件发生在同一时刻。 <br>为了描述事件的发生顺序，定义P=(Qi1j1, Qi2j2,...,Qiljl)为世界的一条发展轨迹，P是满足如下条件的有序序列： <br>1. 对于每个人，计划序列中的每个事件 Qi,j都在P出现一次且恰好一次； <br>2. 对于属于同一个计划序列的两个事件 Qi,j1和Qi,j2（1 ≤ j1 &lt; j2 ≤ Ci），Qi,j1<br>一定发生在 Qi,j2之前（也就是在P中位于更靠前的位置） ；</p>
<p>两条轨迹 P1和 P2被定义为本质不同的，当且仅当存在两个相关的事件 Qi,j和 Qu,v，他们在 P1和 P2中发生的先后顺序不同，也就是说，如果在 P1中 Qi,j发生在Qu,v之前且在P2中Qi,j发生在Qu,v之后，那么 P1和P2就是本质不同的；如果在P1中Qi,j发生在 Qu,v之后且在P2中Qi,j发生在 Qu,v之前，那么P1和P2也是本质不同的； <br>注意：本质相同具有传递性，即若 P1与 P2本质相同且 P2与 P3本质相同，那么P1与P3一定也本质相同。 <br> 给定 N, M、每个人计划序列以及事件之间的相关关系。你需要计算一共有多少种本质不同的世界运行轨迹。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p> 第一行包括一个整数，表示人数 N。 <br>输入文件第二行包括一个整数，表示事件种类数 M，所有类型的事件按照 0<br>至M – 1编号。 <br>接下来依次给出每个人的计划序列的描述，对于第 i 个人： <br>首先一行一个整数表示序列长度 Ci。 <br>第二行包含 Ci个整数，依次给出 Qi中的每个事件Qi,j。 <br>最后 M行输入一个 M 行M列的矩阵dep 用来描述相关关系，每行包含 M个整数，都是 0 或者 1。dep(i,j)表示矩阵自上往下的第 i 行，自左往右的第 j 列所包含的整数。若dep(i, j)的值为1，那么第 i 类事件和第j 类事件就是相关的，否则这两类事件不相关。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>只有一行，一个整数表示本质不同的世界轨迹数 T。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 <br>3 <br>2 <br>0 <br>1 <br>2 <br>2 <br>1 <br>1 1 0 <br>1 1 1 <br>0 1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>总人数 N ≤ 10; <br>事件种类数 M ≤ 15; <br>计划序列长度 Ci ≤ 20; <br>世界轨迹数 T ≤ 10<sup>6</sup>。</p>
</div>
</div>