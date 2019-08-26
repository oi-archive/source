
# Description

<div class="content"><div>Winning the election was simpler than you expected: it was enough to promise to finally build </div>
<div>a good quality, country-wide road infrastructure, of course without crippling the budget_ Your </div>
<div>happiness did not last long, however: it seems, that the citizens have found a way to actually </div>
<div>hold you accountable for your promise! </div>
<div>There are n major cities in your country. The Ministry of Transport has prepared a detailed </div>
<div>map, outlining m possible highway connections, together with their costs. The Quality Assurance </div>
<div>Committee will not let you build a highway cheaper than l, and the National Spendings </div>
<div>Regulatory Committee will not let you build a highway more expensive than h. To claim a </div>
<div>&#34;country-wide&#34; network, you have to connect (possibly indirectly) as many pairs of cities, as it is </div>
<div>possible within these two constraints. You have to find the cheapest way to do it, and you have </div>
<div>to find it quickly! Of all networks that meet the constraints and connect the most pairs of cities, </div>
<div>compute the cost of the cheapest one. </div>
<div>To make things worse, both committees are heavily influenced by your angry competitors: </div>
<div>each time you publish your hard-prepared plan, they immediatelv change their rulings l and矗， </div>
<div>and vou are forced to start from scratch. </div>
<div>有N个点，M条无向虚边（边还未连接上去），Q组询问，询问格式如下： </div>
<div>对于第一个询问输入2个数L1,H1,表示你要用满足权值L1&lt;=Ai&lt;=H1的所有边来连接点使得能互相通达的点的数量最多。在此条件下，输出最小的权值和C1. 对于第i个询问(1 </div>
<div>N&lt;=1000, M&lt;=100000, Q&lt;=1000000 </div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains the number of test cases T. The descriptions of the test cases </div>
<div>
<div>follow: </div>
<div>The first line of each test case contains integers n and m (1≤ n≤ 1000; 0≤ rn≤ 100 000) - </div>
<div>the number of cities in the country, and of possible direct connections, respectively. </div>
<div>Each of the following m lines contains three integers x,y,w (1 &lt; x≠ y &lt; n; I≤ w≤ </div>
<div>1000 000), denoting that the cities x and y can be connected by a bidirectional highway at cost </div>
<div>w. There might be many ways to connect a single pair of cities. </div>
<div>The following line contains an integer q (1《 q &lt; 1 000 000) - the number of rulings of the </div>
<div>committees. Each of the following q lines contains two integers. The first of the lines contains </div>
<div>the initial rulings 21, hi, given directly. The rest of the rulings are encoded. The numbers in the </div>
<div>j-th of the lines for j &gt; I are lj + Cj_i and hj + cj_i, where lj and hj are the actual rulings and </div>
<div>cj-l is the correct answer for the preceding rulings /j_i and hj_i. </div>
<div>All rulings satisfv I≤ tj≤ hj &lt; 1000 000. </div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>For each test case, output q lines, one for </div>
<div>cost cj of building a highway network which </div>
<div>the maximum number of connected pairs of </div>
<div>each ruling. In the j-th of them, output the minimal </div>
<div>adheres to the committees7 constraints, and creates </div>
<div>cities.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
5 7<br/>
1 2 2<br/>
2 3 4<br/>
3 4 3<br/>
4 5 1<br/>
5 1 3<br/>
2 5 4<br/>
1 4 5<br/>
5<br/>
1 2<br/>
4 7<br/>
11 12<br/>
11 13<br/>
18 19<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
9<br/>
8<br/>
14<br/>
13</span></div>

# Hint

<div class="content"><p></p><div>样例解释： </div><br/>
<div>第一组询问1 2，连接1 2 2和4 5 1两条边，总权值为3.因为没有其他边的权值范围在[1,2]了 </div><br/>
<div>第二组询问4 7，实际询问为4-3=1和7-3=4，即[1,4]，最终连接1 2 2, 3 4 3, 4 5 1, 5 1 3, 其余满足条件的边都是冗余的，总权值为9. </div><br/>
<div>以下同理。 </div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

