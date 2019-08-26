
# Description

<div class="content"><div>一年一度的综艺节目《中国新代码》又开始了。</div>
<div>Zayid从小就梦想成为一名程序员，他觉得这是一个展示自己的舞台，于是他毫不犹豫地报名了。</div>
<div></div>
<div>题目描述</div>
<div></div>
<div>轻车熟路的Zayid顺利地通过了海选，接下来的环节是导师盲选，这一阶段的规则是这样的：</div>
<div></div>
<div>总共n名参赛选手（编号从1至n）每人写出一份代码并介绍自己的梦想。接着由所有导师对这些选手进行排名。</div>
<div>为了避免后续的麻烦，规定不存在排名并列的情况。</div>
<div></div>
<div>同时，每名选手都将独立地填写一份志愿表，来对总共m位导师（编号从1至m）作出评价。</div>
<div>志愿表上包含了共m档志愿。</div>
<div>对于每一档志愿，选手被允许填写最多C位导师，每位导师最多被每位选手填写一次（放弃某些导师也是被允许的）。</div>
<div></div>
<div>在双方的工作都完成后，进行录取工作。</div>
<div>每位导师都有自己战队的人数上限，这意味着可能有部分选手的较高志愿、甚至是全部志愿无法得到满足。节目组对”</div>
<div>前i名的录取结果最优“作出如下定义：</div>
<div></div>
<div>前1名的录取结果最优，当且仅当第1名被其最高非空志愿录取（特别地，如果第1名没有填写志愿表，那么该选手出局）。</div>
<div></div>
<div>前i名的录取结果最优，当且仅当在前i-1名的录取结果最优的情况下：第i名被其理论可能的最高志愿录取</div>
<div>（特别地，如果第i名没有填写志愿表、或其所有志愿中的导师战队均已满员，那么该选手出局）。</div>
<div></div>
<div>如果一种方案满足‘‘前n名的录取结果最优’’，那么我们可以简称这种方案是最优的。</div>
<div></div>
<div>举例而言，2位导师T老师、F老师的战队人数上限分别都是1人；2位选手Zayid、DuckD分列第1、2名。</div>
<div>那么下面3种志愿表及其对应的最优录取结果如表中所示：</div>
<div><img src="source/bzoj/5251/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwNC8xMTEoMSkuanBn.jpg" width="550" height="392" alt=""/></div>
<div>可以证明，对于上面的志愿表，对应的方案都是唯一的最优录取结果。</div>
<div>每个人都有一个自己的理想值si，表示第i位同学希望自己被第si或更高的志愿录取，如果没有，那么他就会非常沮丧。</div>
<div></div>
<div>现在，所有选手的志愿表和排名都已公示。巧合的是，每位选手的排名都恰好与它们的编号相同。</div>
<div></div>
<div>对于每一位选手，Zayid都想知道下面两个问题的答案：</div>
<div></div>
<div>在最优的录取方案中，他会被第几志愿录取。</div>
<div></div>
<div>在其他选手相对排名不变的情况下，至少上升多少名才能使得他不沮丧。</div>
<div></div>
<div>作为《中国新代码》的实力派代码手，Zayid当然轻松地解决了这个问题。</div>
<div>不过他还是想请你再算一遍，来检验自己计算的正确性。</div></div>

# Input

<div class="content"><div>每个测试点包含多组测试数据</div>
<div>第一行2个用空格隔开的非负整数T;C，分别表示数据组数、每档志愿最多允许填写的导师数目。</div>
<div>接下来依次描述每组数据，对于每组数据：</div>
<div>第1行两个用空格隔开的正整数n;m。</div>
<div>n;m分别表示选手的数量、导师的数量。</div>
<div>第2行m个用空格隔开的正整数：其中第i个整数为bi。</div>
<div>Bi表示编号为i的导师战队人数的上限。</div>
<div>第3行至第n+2行，每行m个用空格隔开的非负整数：其中第i+2行左起第j个数为ai,j</div>
<div>ai,j表示编号为i的选手将编号为j的导师编排在了第ai,j志愿。特别地，如果ai,j=0，则表示该选手没有将该导师填入志愿表。</div>
<div>在这一部分，保证每行中不存在某一个正数出现超过C次（0可能出现超过C次），同时保证所有ai,j&lt;=m。</div>
<div>第n+3行n个用空格隔开的正整数，其中第i个整数为Si</div>
<div>Si表示编号为i的选手的理想值。</div>
<div>在这一部分，保证Si&lt;=m。</div>
<div>T&lt;=5,m&lt;=n&lt;=200,Bi&lt;=N</div></div>

# Output

<div class="content"><div>按顺序输出每组数据的答案。对于每组数据，输出2行：</div>
<div>第1行输出n个用空格隔开的正整数，其中第i个整数的意义为：</div>
<div>在最优的录取方案中，编号为i的选手会被该档志愿录取。</div>
<div>特别地，如果该选手出局，则这个数为m+1。</div>
<div>第2行输出n个用空格隔开的非负整数，其中第i个整数的意义为：</div>
<div>使编号为i的选手不沮丧，最少需要让他上升的排名数。</div>
<div>特别地，如果该选手一定会沮丧，则这个数为i。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 5<br/>
2 2<br/>
1 1<br/>
2 2<br/>
1 2<br/>
1 1<br/>
2 2<br/>
1 1<br/>
1 2<br/>
1 2<br/>
2 1<br/>
2 2<br/>
1 1<br/>
0 1<br/>
0 1<br/>
2 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 1<br/>
1 0<br/>
1 2<br/>
0 1<br/>
1 3<br/>
0 1<br/>
三组数据分别与【题目描述】中的三个表格对应。<br/>
对于第1 组数据：由于选手1 没有填写第一志愿，所以他一定无法被第一志愿录取，也就一定会沮丧。<br/>
选手2 按原排名就不沮丧，因此他不需要提升排名。<br/>
对于第2 组和第3 组数据：1 号选手都不需要提升排名。<br/>
而希望被第一志愿录取 的2 号选手都必须升到第1 名才能如愿。</span></div>

# Hint

<div class="content"><p></p><p> <span style="font-family: arial, verdana, helvetica, sans-serif; font-size: 18px; background-color: rgb(228, 240, 248);">原题面:</span><a href="http://www.lydsy.com/JudgeOnline/upload/201804/day2(3).pdf" style="font-family: arial, verdana, helvetica, sans-serif; color: blue; text-decoration: none; font-size: 18px; background-color: rgb(228, 240, 248);">www.lydsy.com/JudgeOnline/upload/201804/day2(3).pdf</a></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

