<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    在遥远的HX国，住着一个旅行家小L，他希望骑着他的自行车游遍全国。在这个国家中，每个城市都有一个编号，共有n个城市，编号从1到n。有的城市没有小L想去的景点，而有的城市有且仅有一个小L想去的景点，所有城市都是这两种情况之一。小L非常热爱信息学，他编写程序给他的旅行安排了一条最短路线以到达所有他想去的景点（所以他旅行线路上城市编号是乱序的）：他第1个到达的城市编号为a1，第i 个到达的城市编号为ai，最后到达城市an结束这次旅行。小L希望用恰好m个月（m&lt; n）的时间完成这次旅行，所以他需要制定一个理性的旅行计划。</p>
<p>    当他到达一个城市时，如果这个城市有他想要去的景点，他会因此获得1点快乐值；但是若到达的城市没有他想去的景点，他会因旅途的疲惫得到1点疲劳值。一个月的时间足够他游玩任意多个城市，但他也希望拿出一定时间来休息。他每个月总是在本月所达到的最后一个城市休息（但如果这个城市有景点，那么小L总会游玩完这个景点再休息）。当然，小L希望每个月都能有一定的旅行任务，即便这个月他所到达的城市中并没有他想去的景点，<br>换句话说，每个月他都会至少到达一个新的城市。小L无法自己安排旅行计划，所以求助于你。你需要告诉他一个序列：<br><br>x1,x2, …, xm<br><br>    xi表示小L第i个月休息时，他所在的城市编号。由于他最后一个月必须完成他的旅行，所以xm肯定等于an。例如，设n = 5，m= 3，(a1, a2, a3, a4, a5) = (3, 2, 4, 1, 5)，(x1, x2, x3) = (2, 1, 5)，这意味着：第1个月先后到达3号和2号城市，并在2号城市休息；第2个月先后到达4号和1号城市，并在1号城市休息；第3个月到达5号城市，并在5号城市休息。这样的方案序列有很多种，设每种方案序列中的第i个月旅行中当月获得的快乐值与疲劳值的差的绝对值为di，设第k种方案序列中求出的d1, d2, …, dm这个m个值的最大值为ck，小L希望所选择的方案序列的ck在所有方案序列中是最小的。事实上，可能有多个方案序列的ck达到并列最小值。由于小L喜爱编程，他患上了一定的强迫症（虽然他自己认为他的强迫症让他炫的发黄），他希望给他的序列是这多个方案中字典序最小的。。<br>    Tips：比较两个序列字典序即比较第一个不相同数字的大小，如1, 2, 3, 4 &lt; 1, 2, 4, 3。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第一行为两个空格隔开的正整数n, m，表示旅行的城市数与旅行所花的月数。<br>    接下来n行，其中第i 行包含两个空格隔开的整数ai和bi，ai表示他第i个去的城市编号；bi为0或1：如果bi为0，则表示城市ai没有小L想去的景点，若为1则表示城市ai有小L想去的景点。<br>    ai 两两不同且有1 ≤ ai ≤ n，即{ai}为1, 2, …, n的一个排列，例如{2, 1, 3, 4, …, n}。<br>    对于10%的数据，n ≤10；<br>    对于25%的数据，m ≤10；<br>    对于30%的数据，n ≤100；<br>    对于40%的数据，m ≤100；<br>    对于40%的数据，n ≤1000；<br>    对于55%的数据，n ≤180000；<br>    对于100%的数据，n ≤500000，m ≤200000。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; 包括一行，包含m个空格隔开的正整数x1,x2, &hellip;, xm，为给小L安排旅行计划对应的路线。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>8 3 <br>2 0<br>3 1 <br>4 1 <br>1 0 <br>5 0 <br>6 1 <br>7 1 <br>8 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 6 8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>第1个月得到2点快乐值与2点疲劳值，第2个月得到1点快乐值与1点疲劳值，第3<br>个月得到1点快乐值与1点疲劳值。3个月中疲劳值与快乐值差的最大值为0，达到所有方<br>案最小值。<br>可行方案有：<br>1 6 8 <br>3 6 8 <br>3 1 8 <br>其中1 6 8字典序最小。</p>
</div>
</div>