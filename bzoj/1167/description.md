
# Description

<div class="content"><div>在Moldova王国有N个用双向道路连接着的城市，编号为1到N。为了节约开支，政府建了N-1条双向道路连接这些城</div>
<div>市，使得任意两个城市之间可以互相到达。因为一条法令，这N个城市各自有着非负数的美化指数比如第i个城市的</div>
<div>美化指数等于ai。不同的城市可能有着相同的美化指数。Gigel来到了Moldova王国，且现在在第1个城市。他早就</div>
<div>迫不及待地想要参观这些美丽的城市，但是因为时间有限，他犹豫着无法决定去哪些城市。他将在Moldova王国停</div>
<div>留K天，每天他可以去参观一些城市。在第i天，他将会从前一天停留的城市x开始（如果i=1,则x=1)，前往另一个</div>
<div>城市y，而城市y是最大化ay-d(x,y)的城市（x不等于y)。其中d(x,y)是从城市x到城市y所需经过的最少的道路条数</div>
<div>。如果有多个城市同时取得最大值，则选定编号最小的城市。然后第i天他会在城市y停留一整天。第二天他又会重</div>
<div>复这一进程。Gigel想要知道第K天他会在哪个城市停留一整天，于是他来请求你的帮助。</div>
<div></div></div>

# Input

<div class="content"><p>第一行包含两个数字，城市的数量N，和Gigel参观城市的天数K。</p>
<div>第二行包含N个用空格隔开的N个数字ai,ai表示第i个城市的美化指数。</div>
<div>接下来的N-1行，每行包括两个数字ui,vi,表示城市ui和城市vi之间有一条双向道路直接相连。</div>
<div>1 &lt;= N &lt;= 3*10^5</div>
<div>1 &lt;= K &lt;= 10^18</div>
<div>0 &lt;= ai &lt;= 10^9</div>
<div>保证城市间是联通的</div>
<div></div></div>

# Output

<div class="content"><div>输出第K天Gigel停留了一整天的城市编号。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 4<br/>
1 1 3 2 4<br/>
1 2<br/>
1 3<br/>
2 4<br/>
2 5</span></div>

# Sample Output

<div class="content"><span class="sampledata"> 5<br/>
样例解释<br/>
第一天，Gigel将会离开城市1前往城市3<br/>
第二天，他将会离开城市3前往城市5<br/>
第三天，他将会离开城市5前往城市2<br/>
第四天，他将会离开城市2前往城市5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

