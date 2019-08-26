
# Description

<div class="content"><div>你是活跃在历史的幕后的一名特工，为了世界的和平而日以继夜地努力着。</div>
<div>这个世界有N个国家，编号为1...N，你的目的是在这N个国家之间建立尽可能多的友好关系。你为了制定一个特工工作的计划，作出了一张当今国际关系的示意图。</div>
<div>你准备了一张非常大的画纸，先画下了代表每个国家的N个点。接下来，为了表示现在的国际关系，画下了M个连接两个国家的有向边，其中从国家a连向国家b的有向边(下面称作“边(a,b)”)表示“现在国家a向国家b派遣了大使”。这样就做出了N个点M条边的当今国际关系示意图。</div>
<div>作为两国友好关系的开端，两国之间需要进行“友好条约缔结会议”(以下简称会议)。如果某两个国家p和q要进行会议，那么需要一个向两国都派遣了大使的国家x作为中介。会议结束后，会议的双方相互向对方的国家派遣大使。换句话说，为了让国p和国q进行会议，必须存在一个国家x满足边(x,p)和边(x,q)都存在，并且在会议后添加两条边(p,q)和(q,p)(如果需要添加的某条边已经存在则不添加)。</div>
<div>你的工作是对于可以进行会议的两国，选择会议的中介并促使会议进行。使用这张图进行工作的模拟的话，世界距离和平还有多远的一个重要的基准就是这张图上的边数。也就是说，你想知道反复进行【选择两个国家使其进行会议】的工作后，图上的边数最多会到达多少。</div>
<div>现在给出国家的个数以及当今国际关系的情报，请你求出反复进行【选择两个国家使其进行会议】的工作后，图上的边数最多会到达多少。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个空格分隔的整数N和M，分别表示世界上国家的个数和图中的边数</div>
<div>接下来M行描述画纸上的有向边的信息，其中第i行(1&lt;=i&lt;=M)有两个空格分隔的整数Ai和Bi，表示图中有一条从Ai到Bi的有向边(即Ai国向Bi国派遣了大使)。</div>
<p></p></div>

# Output

<div class="content"><div>输出一行一个整数，表示能实现的边数的最大值。注意这个边数包括原有的边数和新连接的边数。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 4<br/>
1 2<br/>
1 3<br/>
4 3<br/>
4 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">10</span></div>

# Hint

<div class="content"><p></p><div>按照下面的顺序实现10条边：</div><br/>
<div>以国1为中介，国2与国3进行会议；</div><br/>
<div>以国4为中介，国3与国5进行会议；</div><br/>
<div>以国3为中介，国2与国5进行会议。</div><br/>
<div>1&lt;=N&lt;=10^5</div><br/>
<div>1&lt;=M&lt;=2*10^5</div><br/>
<div>1&lt;=Ai&lt;=N(1&lt;=i&lt;=M)</div><br/>
<div>1&lt;=Bi&lt;=N(1&lt;=i&lt;=M)</div><br/>
<div>Ai≠Bi(1&lt;=i&lt;=M)</div><br/>
<div>(Ai,Bi)≠(Aj,Bj)(1&lt;=i&lt;j&lt;=M)</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=JOI 2013~2014 春季training合宿 竞技2 By PoPoQQQ">JOI 2013~2014 春季training合宿 竞技2 By PoPoQQQ</a></p></div>

