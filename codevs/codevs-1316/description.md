<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一位使者要游历各国，他每到一个国家，都能学到一种文化，但他不愿意学习任何一种文化超过一次（即如果他学习了某种文化，则他就不能到达其他有这种文化的国家）。不同的国家可能有相同的文化。不同文化的国家对其他文化的看法不同，有些文化会排斥外来文化（即如果他学习了某种文化，则他不能到达排斥这种文化的其他国家）。</p>
<p>现给定各个国家间的地理关系，各个国家的文化，每种文化对其他文化的看法，以及这位使者游历的起点和终点（在起点和终点也会学习当地的文化），国家间的道路距离，试求从起点到终点最少需走多少路。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为五个整数N，K，M，S，T，每两个整数之间用一个空格隔开，依次代表国家个数（国家编号为1到N），文化种数（文化编号为1到K），道路的条数，以及起点和终点的编号（保证S不等于T）；</p>
<p>第二行为N个整数，每两个整数之间用一个空格隔开，其中第i个数Ci，表示国家i的文化为Ci。</p>
<p>接下来的K行，每行K个整数，每两个整数之间用一个空格隔开，记第i行的第j个数为aij，aij= 1表示文化i排斥外来文化j（i等于j时表示排斥相同文化的外来人），aij= 0表示不排斥（注意i排斥j并不保证j一定也排斥i）。</p>
<p>接下来的M行，每行三个整数u，v，d，每两个整数之间用一个空格隔开，表示国家u与国家v有一条距离为d的可双向通行的道路（保证u不等于v，两个国家之间可能有多条道路）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只有一行，一个整数，表示使者从起点国家到达终点国家最少需要走的距离数（如果无解则输出-1）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>输入样例1</p>
<p>2 2 1 1 2</p>
<p>1 2</p>
<p>0 1</p>
<p>1 0</p>
<p>1 2 10</p>
<p> </p>
<p>输入样例2</p>
<p>2 2 1 1 2</p>
<p>1 2</p>
<p>0 1</p>
<p>0 0</p>
<p>1 2 10</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>输出样例1</p>
<p>-1</p>
<p> </p>
<p>输出样例2</p>
<p>10</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【输入输出样例1说明】</p>
<p>由于到国家2必须要经过国家1，而国家2的文明却排斥国家1的文明，所以不可能到达国家2。</p>
<p>【输入输出样例2说明】</p>
<p>路线为1 -&gt; 2。</p>
<p>【数据范围】</p>
<p>对于20%的数据，有2≤N≤8，K≤5；</p>
<p>对于30%的数据，有2≤N≤10，K≤5；</p>
<p>对于50%的数据，有2≤N≤20，K≤8；</p>
<p>对于70%的数据，有2≤N≤100，K≤10；</p>
<p>对于100%的数据，有2≤N≤100，1≤K≤100，1≤M≤N2，1≤ki≤K，1≤u,v≤N，1≤d≤1000，S≠T，1 ≤S, T≤N。</p>
</div>
</div>