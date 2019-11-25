<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>由于地震使得连接汶川县城电话线全部损坏，假如你是负责将电话线接到震中汶川县城的负责人，汶川县城周围分布着N(1≤N≤1,000)根按 1..N 顺次编号的废弃的电话线杆，任意两根电话线杆间都没有电话线相连。一共P(1≤P≤10,000)对电话线杆间可以拉电话线，其余的由于地震使得无法被连接。</p>
<p>第i对电话线杆的两个端点分别为Ai，Bi，它们间的距离为Li(1≤Li≤1,000,000)。数据中保证每对(Ai，Bi)最多只出现1次。编号为1的电话线杆已经接人了全国的电话网络，整个县城的电话线全都连到了编号为N的电话线杆上。也就是说，你的任务仅仅是找一条将1号和N号电话线杆连起来的路径，其余的电话线杆并不一定要连人电话网络。</p>
<p>电信公司决定支援灾区免费为汶川县城连结K(0≤K&lt;N)对由你指定的电话线杆。对于此外的那些电话线，需要为它们付费，总费用等于其中最长的电话线的长度(每根电话线仅连接一对电话线杆)。如果需要连接的电话线杆不超过K对，那么总支出为0。</p>
<p>请你计算一下，将电话线引到震中汶川县城最少需要在电话线上花多少钱?</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行包含三个用空格隔开的整数：N，P和K。</p>
<p>第二行到第P+1行：每行分别都为空格隔开的整数：Ai，Bi和Li。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件中仅包含一个整数，表示在这项工程上的最小支出。如果任务不可能完成，则输出-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 7 1</p>
<p>1 2 5</p>
<p>3 1 4</p>
<p>2 4 8</p>
<p>3 2 3</p>
<p>5 2 9</p>
<p>3 4 7</p>
<p>4 5 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>题目已有。</p>
</div>
</div>