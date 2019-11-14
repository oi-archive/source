
# Description

<div class="content"><div>对家庭菜园有兴趣的JOI君每年在自家的田地中种植一种叫做IOI草的植物。JOI君的田地沿东西方向被划分为N个区域，由西到东标号为1~N。IOI草一共有N株，每个区域种植着一株。在第i个区域种植的IOI草，在春天的时候高度会生长至hi，此后便不再生长。</div>
<div>为了观察春天的样子而出行的JOI君注意到了IOI草的配置与预定的不太一样。IOI草是一种非常依靠阳光的植物，如果某个区域的IOI草的东侧和西侧都有比它高的IOI草存在，那么这株IOI草就会在夏天之前枯萎。换句话说，为了不让任何一株IOI草枯萎，需要满足以下条件：</div>
<div>对于任意2&lt;=i&lt;=N-1，以下两个条件至少满足一个：</div>
<div>1.<span class="Apple-tab-span" style="white-space:pre">	</span>对于任意1&lt;=j&lt;=i-1，hj&lt;=hi</div>
<div>2.<span class="Apple-tab-span" style="white-space:pre">	</span>对于任意i+1&lt;=j&lt;=N，hk&lt;=hi</div>
<div>IOI草是非常昂贵的，为了不让IOI草枯萎，JOI君需要调换IOI草的顺序。IOI草非常非常的高大且纤细的植物，因此JOI君每次只能交换相邻两株IOI草。也就是说，JOI君每次需要选择一个整数i(1&lt;=i&lt;=N-1)，然后交换第i株IOI草和第i+1株IOI草。随着夏天临近，IOI草枯萎的可能性越来越大，因此JOI君想知道让所有IOI草都不会枯萎的最少操作次数。</div>
<div>现在给出田地的区域数，以及每株IOI草的高度，请你求出让所有IOI草的不会枯萎的最少操作次数。</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个正整数N，代表田地被分为了N个区域。</div>
<div>接下来N行，第i行(1&lt;=i&lt;=N)一个整数hi，表示第i株植物在春天时的高度</div>
<p></p></div>

# Output

<div class="content"><div>输出一行一个整数，表示最少需要的操作次数</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
2<br/>
8<br/>
4<br/>
5<br/>
3<br/>
6</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p><div>最终的高度序列为2 4 5 8 6 3，共需要操作三次。</div><br/>
<div>3&lt;=N&lt;=3*10^5</div><br/>
<div>1&lt;=hi&lt;=10^9</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=JOI 2013~2014 春季training合宿 竞技1 By PoPoQQQ">JOI 2013~2014 春季training合宿 竞技1 By PoPoQQQ</a></p></div>

