
# Description

<div class="content"><div>T64有一个好朋友，叫T128。T128是寄宿生，并且最近被老师叫过去当宿管了。宿管可不是一件很好做的工作，碰</div>
<div>巧T128有一个工作上的问题想请T64帮忙解决。T128的寝室条件不是很好，所以没有很多钱来装修。礼间寝室仅由n</div>
<div>-1条双向道路连接，而且任意两间寝室之间都可以互达。最近，T128被要求对一条路径上的所有寝室进行管理，这</div>
<div>条路径不会重复经过某个点或某条边。但他不记得是哪条路径了。他只记得这条路径上有不少于k个寝室。于是，</div>
<div>他想请T64帮忙数一下，有多少条这样的路径满足条件。嗯…还有一个问题。由于最近有一些熊孩子不准晚上讲话</div>
<div>很不爽，他们决定修筑一条“情报通道”，如果通道建成，寝室就变成了一个N个点N条边的无向图。并且，经过“</div>
<div>情报通道”的路径也是合法的。T128心想：通道建成之前，T64还有一个高效的算法帮我数路径条数，但是通道建</div>
<div>成之后，他还有办法吗？对，T64手忙脚乱，根本数不清有多少条路径。于是他找到了你。</div></div>

# Input

<div class="content"><div>
<div>第一行为三个正整数N，M，K（2 ≤ K ≤ N），代表有n间寝室，m条边连接它们n-1 ≤ m ≤ N；</div>
<div>m= n-1意味着“情报遁道”未被修好；m=n意味着“情报通道”已被修好），以及题目描述中的K。</div>
<div>接下来m行，每行两个正整数z，y，代表第x间寝室与第y间寝室之间有一条双向边。</div>
</div></div>

# Output

<div class="content"><p><font size="4">仅包含一个整数，代表经过至少K间寝室的路径条数。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5 2<br/>
1 3<br/>
2 4<br/>
3 5<br/>
4 1<br/>
5 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">20<br/>
</span></div>

# Hint

<div class="content"><p></p><p><img alt="" src="/source/bzoj/3648/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwNy8xMSgyKS5qcGc=.jpg"/></p><br/>
<p></p><br/>
<p>N≤100000      <br/><br/>
K≤N<br/><br/>
M=N           </p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

