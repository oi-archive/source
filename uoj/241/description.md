# 题目描述

<p>天刚黎明，跳蚤火箭发射场区一片紧张的战斗气氛。跳蚤们盼望已久的 “赛艇一号” 就要发射了，它将带着伏特跳蚤国王和第一批跳蚤大军，奔赴土卫二建造新的基地。各专业的工程技术蚤对火箭起飞前进行了最后的检查和操作，一切准备就绪。跳蚤国万人空巷，满怀激动地等待着发射时刻的到来。可是，谁都没注意到……</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/241/dark.jpg" alt="黑恶势力登场"/></p>
<p>在某个地下会议室内，一群人正盯着显示屏中的地图，听一个屏幕前的黑影介绍跳蚤火箭发射场构造图。</p>
<p>跳蚤火箭发射场由正 $n$ 边形的围墙包围，顶点按顺时针标号为 $1$ 到 $n$。发射台位于该正 $n$ 边形的正中心，可忽略大小视为一个点。</p>
<p>突然，一个士兵匆匆跑进了会议室：“报告阁下，特工已经成功潜入发射场，发射场的每个顶点都已经放置了一个垃鸡。” 垃鸡是一种生物武器，每个拉鸡属于一个种群。在启动攻击后，任意两只相同种群的垃鸡之间会形成一束 “高稳鸡光” 并对所经过的建筑物造成损害。假如 “高稳鸡光” 经过了发射台，或者是经过了围墙，那么阻碍发射的计划便成功了。</p>
<p>“嗯，让我们开始吧。” 坐在重重阴影之下的 BOSS 终于说话了，听不出任何语气。</p>
<p>可 BOSS 不知道的是，由于超高校级的不幸，前线的特工把垃鸡的种群给弄混了，他们并不知道现在在每个顶点的垃鸡是什么种群的，他们只知道他们带了 $m$ 个种群的垃鸡，而且每种垃鸡的数量近乎无限，所以他们只能随意地放置垃鸡。</p>
<p>特工们十分害怕，害怕计划失败后被拿去煲汤，他们现在想知道，有多少种放置情况会使计划失败。两个方案被认为是不同的当且仅当存在一个位置上的垃鸡所属的种群不同。</p>
<p><strong>一句话题意：</strong>长度为 $n$ 的环，每个点染色，有 $m$ 种颜色，要求相邻相对不能同色，求方案数。（定义两个点相对为去掉这两个点后环能被分成相同大小的两段）</p>

# 输入格式


<p>第一行两个正整数 $n,m$，意义如前所述。</p>

# 输出格式


<p>输出一行一个整数，表示能使计划失败的放置情况数模 $998244353$（$7 \times 17 \times 2^{23} + 1$，一个质数） 的值。</p>

# 样例一


<h4>input</h4>
<pre>3 3

</pre>

<h4>output</h4>
<pre>6

</pre>

<h4>explanation</h4>
<p>$6$ 种情况分别是 $\{1,2,3\}, \{1,3,2\}, \{2,1,3\}, \{2,3,1\}, \{3,2,1\}, \{3,1,2\}$。</p>

# 样例二


<h4>input</h4>
<pre>6 2

</pre>

<h4>output</h4>
<pre>2

</pre>

<h4>explanation</h4>
<p>$2$ 种情况分别是 $\{1,2,1,2,1,2\}, \{2,1,2,1,2,1\}$。</p>

# 样例三


<h4>input</h4>
<pre>23333 66666

</pre>

<h4>output</h4>
<pre>768586044

</pre>


# 样例四


<h4>input</h4>
<pre>66666 23333

</pre>

<h4>output</h4>
<pre>137785832

</pre>


# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$m$</th>
</tr></thead><tbody><tr><td>1</td><td>$n \bmod 2=1$ 且 $n \leq 7$</td><td>$m \leq 7$</td></tr><tr><td>2</td><td rowspan="3">$n \bmod 2=1$ 且 $n \leq 11$</td><td>$m \leq 11$</td></tr><tr><td>3</td><td rowspan="8">$m \leq 10^9$</td></tr><tr><td>4</td></tr><tr><td>5</td><td rowspan="4">$n \bmod 2=1$ 且 $n \leq 10^7$</td></tr><tr><td>6</td></tr><tr><td>7</td></tr><tr><td>8</td></tr><tr><td>9</td><td rowspan="2">$n \bmod 2=1$ 且 $n \leq 10^9$</td></tr><tr><td>10</td></tr><tr><td>11</td><td>$n \leq 7$</td><td>$m \leq 7$</td></tr><tr><td>12</td><td rowspan="5">$n \leq 11$</td><td rowspan="2">$m \leq 11$</td></tr><tr><td>13</td></tr><tr><td>14</td><td rowspan="12">$m \leq 10^9$</td></tr><tr><td>15</td></tr><tr><td>16</td></tr><tr><td>17</td><td rowspan="6">$n \leq 10^7$</td></tr><tr><td>18</td></tr><tr><td>19</td></tr><tr><td>20</td></tr><tr><td>21</td></tr><tr><td>22</td></tr><tr><td>23</td><td rowspan="3">$n \leq 10^9$</td></tr><tr><td>24</td></tr><tr><td>25</td></tr></tbody></table></div>

<p>在所有数据中，满足 $3 \leq n \leq 10^9$ 且 $1 \leq m \leq 10^9$。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=241">样例数据下载</a></p>

# 后记


<p>然而再一次因为超高校级的不幸，可怜的特工们终究还是被煲成汤了……</p>
<p>“赛艇一号” 顺利发射，消失在绚丽的朝霞中。</p>
