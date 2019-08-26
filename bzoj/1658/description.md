
# Description

<div class="content"><p><span style="font-size: medium; ">It&#39;s a hot summer day, and Farmer John is letting Betsy go to the water park where she intends to ride every single slide. The water park has N (1 &lt;= N &lt;= 10,000) platforms (numbered 1..N) from which to enter the M (1 &lt;= M &lt;= 10,000) water slides. Each water slide starts at the top of some platform and ends at the bottom of some platform (possibly the same one). Some platforms might have more than one slide; some might not have any.  The park is very thin, so the platforms lie along a straight line, each platform at a position Xi (0 &lt;= Xi &lt;= 100,000) meters from one end of the park. One walks from one platform to the next via a sidewalk parallel to the line of platforms.The platforms of the water park are weakly connected; that is, the park cannot be divided into two sets of platforms with no slides running between the two sets. Both the entrance and exit to the park are at platform 1, so Betsy will start and end there.  In order to spend more time on the slides, Betsy wants to walk as little as possible. Find the minimum distance Betsy must travel along the ground in order to try every slide in the park exactly once without repeating.</span></p>
<p></p>
<p class="MsoNormal"><span style="font-size: medium; "><span lang="EN-US">    </span><span style="font-family: 宋体; ">炎热的夏日里，约翰带贝茜去水上乐园滑水．滑水是在一条笔直的人工河里进行的，沿河设有</span><span lang="EN-US">N(1</span><span style="font-family: 宋体; ">≤</span><span lang="EN-US">N</span><span style="font-family: 宋体; ">≤</span><span lang="EN-US">10000)</span><span style="font-family: 宋体; ">个中转站，并开通了</span><span lang="EN-US">M(1</span><span style="font-family: 宋体; ">≤</span><span lang="EN-US">M</span><span style="font-family: 宋体; ">≤</span><span lang="EN-US">10000)</span><span style="font-family: 宋体; ">条滑水路线．路线的起点和终点总在某个中转站上，起点和终点可能相同．有些中转站可能是许多条路线的起点或终点，而有些站则可能没有在任何路线里被用上．贝茜希望能把所有的路线都滑一遍．</span><span lang="EN-US">    </span><span style="font-family: 宋体; ">所有中转站排成一条直线，每个中转站位于离河的源头</span><span lang="EN-US">Xi(0</span><span style="font-family: 宋体; ">≤</span><span lang="EN-US">Xi</span><span style="font-family: 宋体; ">≤</span><span lang="EN-US">100000)</span><span style="font-family: 宋体; ">米处．沿着河边的人行道，贝茜可以从任意位置走到任意一个中转站．</span><span lang="EN-US">    </span><span style="font-family: 宋体; ">中转站与滑水路线的布局满足下述的性质：任意两个中转站之间都有滑水路线直接成间接相连．水上乐园的入口与出口都在</span><span lang="EN-US">1</span><span style="font-family: 宋体; ">号中转站旁，也就是说，贝茜的滑水路线的起点和终点都是</span><span lang="EN-US">1</span><span style="font-family: 宋体; ">号中转站．</span></span></p>
<p class="MsoNormal"><span style="font-size: medium; "><span lang="EN-US">    </span><span style="font-family: 宋体; ">为了更好地享受滑水的快乐，贝茜希望自己花在走路上的时间越少越好．请你帮她计算一</span></span><span style="font-family: 宋体; font-size: medium; ">下，如果按她的计划，把所有的路线都不重复地滑一遍，那她至少要走多少路．</span></p>
<p class="MsoNormal"></p></div>

# Input

<div class="content"><p>* Line 1: Two integers, N and M.</p>
<p>* Lines 2..N+1: Line i+1 contains one integer, Xi, the position of         platform i.  * Lines N+2..M+N+1: Line i+N+1 contains two integers, Si and Di,         respectively the start and end platforms of a slide.</p>
<p><span lang="EN-US" style="font-size: medium; ">    </span><span style="font-size: medium; font-family: 宋体; ">第</span><span lang="EN-US" style="font-size: medium; ">1</span><span style="font-size: medium; font-family: 宋体; ">行：两个整数</span><span lang="EN-US" style="font-size: medium; ">N</span><span style="font-size: medium; font-family: 宋体; ">和</span><span lang="EN-US" style="font-size: medium; ">M</span><span style="font-size: medium; font-family: 宋体; ">，用空格隔开．</span></p>
<p class="MsoNormal"><span style="font-size: medium; "><span lang="EN-US">    </span><span style="font-family: 宋体; ">第</span><span lang="EN-US">2</span><span style="font-family: 宋体; ">到</span><span lang="EN-US">N+1</span><span style="font-family: 宋体; ">行：第</span><span lang="EN-US">i+l</span><span style="font-family: 宋体; ">行包括一个整数</span><span lang="EN-US">Xi</span><span style="font-family: 宋体; ">，表示</span><span lang="EN-US">i</span><span style="font-family: 宋体; ">号中转站距河源头的距离．</span></span></p>
<p class="MsoNormal"><span style="font-size: medium; "><span lang="EN-US">    </span><span style="font-family: 宋体; ">第</span><span lang="EN-US">N+2</span><span style="font-family: 宋体; ">到</span><span lang="EN-US">M+N+1</span><span style="font-family: 宋体; ">行：第</span><span lang="EN-US">i+N+1</span><span style="font-family: 宋体; ">行包括两个整数</span><span lang="EN-US">Si</span><span style="font-family: 宋体; ">和</span><span lang="EN-US">Di</span><span style="font-family: 宋体; ">，分别表示了一条滑水路线的起</span></span><span style="font-family: 宋体; font-size: medium; ">点和终点．</span></p>
<p class="MsoNormal"></p></div>

# Output

<div class="content"><p><span style="font-size: medium; ">* Line 1: One integer, the minimum number of meters Betsy must walk.</span></p>
<p><span style="font-size: medium; "><span lang="EN-US" style="font-family: &#39;Times New Roman&#39;; ">    </span><span style="font-family: 宋体; ">输出一个整数，即贝茜要走的路程长度至少为多少米</span></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 7<br/>
5<br/>
3<br/>
1<br/>
7<br/>
10<br/>
1 2<br/>
1 2<br/>
2 3<br/>
3 1<br/>
4 5<br/>
1 5<br/>
4 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium; "> <span lang="EN-US">  </span><span style="font-family: 宋体; ">贝茜先按</span><span lang="EN-US">1~2~3~1~2</span><span style="font-family: 宋体; ">路径滑水．然后走</span></span><st1:chmetcnv tcsc="0" numbertype="1" negative="False" hasspace="False" sourcevalue="2" unitname="米" w:st="on"><span style="font-size: medium; "><span lang="EN-US">2</span><span style="font-family: 宋体; ">米</span></span></st1:chmetcnv><span style="font-size: medium; "><span style="font-family: 宋体; ">，回到</span><span lang="EN-US">1</span><span style="font-family: 宋体; ">．她再滑行到</span><span lang="EN-US">5</span><span style="font-family: 宋体; ">，走到</span><span lang="EN-US">4</span><span style="font-family: 宋体; ">，滑行</span>  </span></p><br/>
<p class="MsoNormal"><span style="font-size: medium; "><span style="font-family: 宋体; ">到</span><span lang="EN-US">5</span><span style="font-family: 宋体; ">，走到</span><span lang="EN-US">4</span><span style="font-family: 宋体; ">，最后滑回</span><span lang="EN-US">1</span><span style="font-family: 宋体; ">（数字代表中转站号）．</span></span></p><br/>
<p class="MsoNormal"><span style="font-size: medium; "><span lang="EN-US">    </span><span style="font-family: 宋体; ">这样，她所走的总路程为</span></span><st1:chmetcnv tcsc="0" numbertype="1" negative="False" hasspace="False" sourcevalue="8" unitname="米" w:st="on"><span style="font-size: medium; "><span lang="EN-US">8</span><span style="font-family: 宋体; ">米</span></span></st1:chmetcnv><span style="font-size: medium; "><span style="font-family: 宋体; ">．</span></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

