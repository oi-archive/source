
# Description

<div class="content"><div>小A有一棵N个点的带边权的树，树的每个节点有重量w_i和价值v_i。现在小A要从中选出若干个节点形成一个集合S</div>
<div>，满足这些节点重量之和≤M并且构成一个连通块。小A是一个完美主义者，因此他只会选择节点价值之和最大的那</div>
<div>些S。我们称这样的集合S为完美的集合。现在小A要从所有完美的集合中选出K个，并对这K个完美的集合分别进行</div>
<div>测试。在这K次测试开始前，小A首先需要一个点x来放置他的测试装置，这个测试装置的最大功率为Max。接下来的</div>
<div>每次测试，小A会对测试对象S中的所有点进行一次能量传输，对一个点y进行能量传输需要的功率为dist(x,y)×vy</div>
<div>，其中dist(x,y)表示点x,y在树上的最短路长度。因此，如果S中存在一个点y，满足dist(x,y)×vy&gt;Max，测试就</div>
<div>会失败。同时，为了保证能量传输的稳定性，测试装置所在的点x需要在集合S中，否则测试也会失败。现在小A想</div>
<div>知道，有多少种从所有完美的集合选出K个的方法，使得他能找到一个放置测试装置的点，来完成他的测试呢？你</div>
<div>只需要输出方案数对11920928955078125取模的结果。</div>
<p></p></div>

# Input

<div class="content"><div>第一行四个正整数，表示N,M,K,Max。</div>
<div>接下来一行N个正整数，表示w1,…,wN。</div>
<div>接下来一行N个非负整数，表示v1,…,vN。</div>
<div>接下来N?1行，每行三个正整数A_i,B_i,C_i，</div>
<div>表示树上存在一条长度为C_i的边连接节点A_i,B_i。</div>
<div>N≤60,M≤10000,Ci≤10000,K,wi,vi≤10^9,Max≤10^18。</div>
<p></p></div>

# Output

<div class="content"><div>一个数，表示方案数第11920928955078125取模的结果。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 3 2 4<br/>
1 1 2 2 1 2 2<br/>
1 1 1 2 1 2 2<br/>
1 2 1<br/>
1 3 2<br/>
1 4 2<br/>
2 5 1<br/>
2 6 2<br/>
4 7 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
样例解释<br/>
完美的集合有 {1,2,5},{1,4},{2,6}。<br/>
从中选出K个且能完成测试的方案为选择 {1,2,5},{1,4} 或选择 {1,2,5},{2,6}。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=day1">day1</a></p></div>

