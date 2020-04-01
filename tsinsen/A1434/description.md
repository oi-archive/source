<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　在Igor K大学一年级的时候，他的教授严格要求他和他的同学去解决奥林匹克编程问题。有一天在TOJ上的一个叫做“旗帜”的题目引起了他的注意。在这个问题里要找到满足条件的三色旗染色方案。事实上，这道题很简单，Igor K很快找到了解决方案并把这道题虐掉了。<br/>
　　然而，教授并没有非常在意，他认为TOJ上的题目非常枯燥和简单，它只有3种颜色和2个限制条件。他给了Igor K一个更难的任务，Igor K和它的同学们都没能做出来。（当然了，我们不去强调教授也不会做）<br/>
　　你能帮他解决这个题目吗？<br/>
　　旗帜由一个或几个平行的，相同宽度的条纹组成，每个条纹可能是白色，黑色，红色或黄色，你需要找到满足下列条件的，且条纹数量在L到R之间的旗帜数量：<br/>
　　·相邻的条纹颜色不能相同<br/>
　　·白色和黄色的条纹不能相邻<br/>
　　·红色和黑色的条纹不能相邻<br/>
　　·不能存在连续的三个条纹，依次是黑色，红色，白色或相反（即白色，红色，黑色）<br/>
　　·两个对称的旗帜认为是相同的，比如BW和WB是同一种方案。（B表示黑色，W表示白色）</div>
# 输入格式

<div class="pdcont">　　输入只包含一行两个数L，R(1&lt;=L&lt;=R&lt;=10^9)</div>
# 输出格式

<div class="pdcont">　　输出一个数表示答案，mod 1000000007输出</div>
# 样例输入

<div class="pddata">Sample1：<br/>
3 4<br/>
Sample2：<br/>
5 6</div>
# 样例输出

<div class="pddata">Sample1：<br/>
23<br/>
Sample2：<br/>
64</div>
# 样例说明

<div class="pdcont">　　在第一个样例中：<br/>
　　（W表示白色，B表示黑色，R表示红色，Y表示黄色）<br/>
　　3个条纹的情况: BWB, BYB, BYR, RWR, RYR, WBW, WBY, WRW, WRY, YBY, YRY (11种).<br/>
　　4个条纹的情况: BWBW, BWBY, BYBW, BYBY, BYRW, BYRY, RWRW, RWRY, RYBW, RYBY, RYRW, RYRY (12种).</div>

</div>