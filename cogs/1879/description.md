# 题目描述


<div class="content">
<!--begin main-->
<!-- InstanceBeginEditable name="content" -->
<h3>
【试题来源】
</h3>
<div id="psrc" style="margin-top:20px;display:block;">
<div class="pdcont">
2011中国国家集训队命题答辩
</div>
</div>
<div id="pinputs" style="display:none;">
<div class="pdsec">
输入数据
</div>
<div class="pdcont">
<span class="notice"> 这是一道提交答案的试题，下面给出了该题的输入数据：</span> 
</div>
<div id="inputlist" class="pddata">
</div>
</div>
<div id="pcont1" style="margin-top:20px;display:block;">
<h3>
【问题描述】
</h3>
<div class="pdcont">
有N个点（编号1到N）组成的无向图，已经为你连了M条边。请你再连K条边，使得所有的点的度数都是偶数。求有多少种连的方法。要求你连的K条边中不能有重边，但和已经连好的边可以重。不允许自环的存在。求连边的方法数。我们只关心它模10007的余数。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
输入的第一行有三个自然数，分别表示点数N，已经连好的边数M，和你要连的边数K。保证K≤N(N-1)/2<br/>
接下来M行每行两个整数x,y，描述了一条连接x和y的边。<br/>
30%的数据满足：<br/>
N≤200<br/>
100%的数据满足：<br/>
N≤1000，M≤N，K≤1000，K≤N(N-1)/2
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出一个整数，表示连边的方法数模10007的余数
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
5 1 4<br/>
1 2
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
13
</div>
<h3>
【样例说明】
</h3>
<div class="pdcont">
以下是13种连边的方法（只显示你连的边）：<br/>
{(1,2),(1,3),(1,4),(3,4)}<br/>
{(1,2),(1,3),(1,5),(3,5)}<br/>
{(1,2),(1,4),(1,5),(4,5)}<br/>
{(1,2),(2,3),(2,4),(3,4)}<br/>
{(1,2),(2,3),(2,5),(3,5)}<br/>
{(1,2),(2,4),(2,5),(4,5)}<br/>
{(1,2),(3,4),(3,5),(4,5)}<br/>
{(1,3),(2,4),(3,5),(4,5)}<br/>
{(1,3),(2,5),(3,4),(4,5)}<br/>
{(1,4),(2,3),(3,5),(4,5)}<br/>
{(1,4),(2,5),(3,4),(3,5)}<br/>
{(1,5),(2,3),(3,4),(4,5)}<br/>
{(1,5),(2,4),(3,4),(3,5)}
</div>
</div>
<div id="pcont2" style="margin-top:20px;display:none;">
<p class="NOI0">
<span style="font-size:16px;"><span style="font-family:黑体;">【问题描述】</span><span lang="EN-US"></span></span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;text-decoration:none;">有</span><span style="text-decoration:none;" lang="EN-US">N</span><span style="font-family:宋体;text-decoration:none;">个点（编号</span><span style="text-decoration:none;" lang="EN-US">1</span><span style="font-family:宋体;text-decoration:none;">到</span><span style="text-decoration:none;" lang="EN-US">N</span><span style="font-family:宋体;text-decoration:none;">）组成的无向图，已经为你连了</span><span style="text-decoration:none;" lang="EN-US">M</span><span style="font-family:宋体;text-decoration:none;">条边。请你再连</span><span style="text-decoration:none;" lang="EN-US">K</span><span style="font-family:宋体;text-decoration:none;">条边，使得所有的点的度数都是偶数。求有多少种连的方法。要求</span><u><span style="font-family:宋体;">你连的</span><span lang="EN-US">K</span><span style="font-family:宋体;">条边</span></u><span style="font-family:宋体;text-decoration:none;">中不能有重边，</span><span style="font-family:宋体;"><u>但和已经连好的边可以重</u></span><span style="font-family:宋体;text-decoration:none;">。不允许自环的存在。求连边的方法数。我们只关心它模</span><span style="text-decoration:none;" lang="EN-US">10007</span><span style="font-family:宋体;text-decoration:none;">的余数。</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-size:16px;"><span style="font-family:黑体;">【输入格式】</span><span lang="EN-US"></span></span> 
</p>
<p class="NOI">
<span style="font-family:宋体;">输入的第一行有三个自然数，分别表示点数</span><span lang="EN-US">N</span><span style="font-family:宋体;">，已经连好的边数</span><span lang="EN-US">M</span><span style="font-family:宋体;">，和你要连的边数</span><span lang="EN-US">K</span><span style="font-family:宋体;">。保证</span><span lang="EN-US">K</span><span style="font-family:宋体;">≤</span><span lang="EN-US">N(N-1)/2</span> 
</p>
<p class="NOI">
<span style="font-family:宋体;">接下来</span><span lang="EN-US">M</span><span style="font-family:宋体;">行每行两个整数</span><span lang="EN-US">x,y</span><span style="font-family:宋体;">，描述了一条连接</span><span lang="EN-US">x</span><span style="font-family:宋体;">和</span><span lang="EN-US">y</span><span style="font-family:宋体;">的边。</span><span lang="EN-US"></span> 
</p>
<p class="NOI">
<span lang="EN-US">30%</span><span style="font-family:宋体;">的数据满足：</span><span lang="EN-US"></span> 
</p>
<p class="NOI">
<span lang="EN-US">N</span><span style="font-family:宋体;">≤</span><span lang="EN-US">200</span> 
</p>
<p class="NOI">
<span lang="EN-US">100%</span><span style="font-family:宋体;">的数据满足：</span><span lang="EN-US"></span> 
</p>
<p class="NOI">
<span lang="EN-US">N</span><span style="font-family:宋体;">≤</span><span lang="EN-US">1000</span><span style="font-family:宋体;">，</span><span lang="EN-US">M</span><span style="font-family:宋体;">≤</span><span lang="EN-US">N</span><span style="font-family:宋体;">，</span><span lang="EN-US">K</span><span style="font-family:宋体;">≤</span><span lang="EN-US">1000</span><span style="font-family:宋体;">，</span><span lang="EN-US">K</span><span style="font-family:宋体;">≤</span><span lang="EN-US">N(N-1)/2</span> 
</p>
<p class="NOI0">
<span style="font-size:16px;"><span style="font-family:黑体;">【输出格式】</span><span lang="EN-US"></span></span> 
</p>
<p class="NOI">
<span style="font-family:宋体;">输出一个整数，表示连边的方法数模</span><span lang="EN-US">10007</span><span style="font-family:宋体;">的余数</span><span lang="EN-US"></span> 
</p>
<p class="NOI0">
<span style="font-size:16px;"><span style="font-family:黑体;">【样例输入】</span><span lang="EN-US"></span></span> 
</p>
<p class="NOI2">
<span lang="EN-US">5 1 4</span> 
</p>
<p class="NOI2">
<span lang="EN-US">1 2</span> 
</p>
<p class="NOI0">
<span style="font-size:16px;"><span style="font-family:黑体;">【样例输出】</span><span lang="EN-US"></span></span> 
</p>
<p class="NOI2">
<span lang="EN-US">13</span> 
</p>
<p class="NOI0">
<span style="font-size:16px;"><span style="font-family:黑体;">【样例说明】</span><span lang="EN-US"></span></span> 
</p>
<p class="NOI">
<span style="font-family:宋体;">以下是</span><span lang="EN-US">13</span><span style="font-family:宋体;">种连边的方法（只显示你连的边）：</span><span lang="EN-US"></span> 
</p>
<p class="NOI">
<span lang="EN-US">{(1,2),(1,3),(1,4),(3,4)}</span> 
</p>
<p class="NOI">
<span lang="EN-US">{(1,2),(1,3),(1,5),(3,5)}</span> 
</p>
<p class="NOI">
<span lang="EN-US">{(1,2),(1,4),(1,5),(4,5)}</span> 
</p>
<p class="NOI">
<span lang="EN-US">{(1,2),(2,3),(2,4),(3,4)}</span> 
</p>
<p class="NOI">
<span lang="EN-US">{(1,2),(2,3),(2,5),(3,5)}</span> 
</p>
<p class="NOI">
<span lang="EN-US">{(1,2),(2,4),(2,5),(4,5)}</span> 
</p>
<p class="NOI">
<span lang="EN-US">{(1,2),(3,4),(3,5),(4,5)}</span> 
</p>
<p class="NOI">
<span lang="EN-US">{(1,3),(2,4),(3,5),(4,5)}</span> 
</p>
<p class="NOI">
<span lang="EN-US">{(1,3),(2,5),(3,4),(4,5)}</span> 
</p>
<p class="NOI">
<span lang="EN-US">{(1,4),(2,3),(3,5),(4,5)}</span> 
</p>
<p class="NOI">
<span lang="EN-US">{(1,4),(2,5),(3,4),(3,5)}</span> 
</p>
<p class="NOI">
<span lang="EN-US">{(1,5),(2,3),(3,4),(4,5)}</span> 
</p>
<p class="NOI">
<span lang="EN-US">{(1,5),(2,4),(3,4),(3,5)}</span> 
</p>
</div>
</div>
