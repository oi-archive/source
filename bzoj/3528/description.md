
# Description

<div class="content"><p> 银河历59451年，在银河系有许许多多已被人类殖民的星系。如果想要在行</p>
<div>星系间往来，大家一般使用连接两个行星系的跳跃星门。  一个跳跃星门可以把</div>
<div>物质在它所连接的两个行星系中互相传送。</div>
<div>露露、花花和萱萱被银河系星际联盟调查局任命调查商业巨擘ZeusLeague+</div>
<div>的不正当商业行为。</div>
<div>在银河系有N个已被ZeusLeague+成功打入市场的行星系，不妨标号为</div>
<div>1,2,...,N。而ZeusLeague+在这N个行星系之间还拥有自己的M个跳跃星门。使</div>
<div>用这些跳跃星门，ZeusLeague+的物资就可以在这N个行星系中两两任意互相传</div>
<div>输。由于经费问题，跳跃星门的个数不会超过行星系的个数。</div>
<div>露露在颇费周折之后得到了ZeusLeague+在这N个行星系中的各自的贸易总</div>
<div>额C[i]。</div>
<div>萱萱设计了一个经济学特征指标D[i]来度量这N个行星系的经济学特征。于</div>
<div>是，我们可以用二元组(C[i],D[i])来表示第i个行星系的XP(Xuan&#39;s Position)。现</div>
<div>在假设我们有k个行星系的XPs，把它们放置在二维平面上，然后我们用一条直</div>
<div>线去拟合这些XPs。定义一条直线与XPs的相斥度为这条直线到各个XP的Euclid</div>
<div>距离的平方之和。再令XPs的线性假设相斥度为所有直线与XPs的相斥度中的</div>
<div>最小者。那么，这个值越小，ZeusLeague+在这k个行星系中的相互贸易活动就</div>
<div>越可疑，从而值得进一步调查。花花负责计算许多行星系对(u,v)的非可疑度。一</div>
<div>条跳跃星门航线的非可疑度被定义为它经过的所有行星系（包括起点和终点）的</div>
<div>XPs的线性假设相斥度。而一个行星系对(u,v)的非可疑度则被定义为所有以u为</div>
<div>起点，v为终点的跳跃星门航线的非可疑度中的最小值。一条跳跃星门航线是指</div>
<div>从某个行星系开始，通过跳跃星门依次到达某些行星系，然后终止，并且中途不</div>
<div>重复经过行星系，这样的一个过程。</div>
<div>花花负责计算许多行星系对(u,v)的非可疑度。一条跳跃星门航线的非可疑度</div>
<div>被定义为它经过的所有行星系（包括起点和终点）的XPs的线性假设相斥度。</div>
<div>而一个行星系对(u,v)的非可疑度则被定义为所有以u为起点，v为终点的跳跃星</div>
<div>门航线的非可疑度中的最小值。一条跳跃星门航线是指从某个行星系开始，通过</div>
<div>跳跃星门依次到达某些行星系，然后终止，并且中途不重复经过行星系，这样的</div>
<div>一个过程。</div>
<div>在花花数天夜以继日的工作之后，平行调查组的你——大名鼎鼎的计算机科</div>
<div>学家Hcceleration.Gerk.Gounce不忍心看到她这样不眠不休，于是你在完成了手</div>
<div>头的工作之后决定帮一帮她。</div>
<div></div>
<div></div></div>

# Input

<div class="content"><p> 第一行是N，M，分别表示这个银河系内的行星系的个数</p>
<div>以及跳跃星门的个数。</div>
<div>接下来N行，每行2个正整数C[i], D[i]，表示第i 个行星系的XP(Xuan&#39;s Position)。</div>
<div>接下来的M行来描述跳跃星门，每行2个正整数u[i],v[i]，表示有一个连接</div>
<div>着行星系u[i]和v[i]的跳跃星门。注意这个连接是无向的。不会存在自己连向自</div>
<div>己的情况。也不会存在重复连接的情况。</div>
<div>接下来的一行，有一个正整数Q，表示花花需要计算的非可疑度的行星对数。</div>
<div>接下来的Q行，每行2个正整数s[i], t[i]，表示花花需要计算从s[i]到t[i]的</div>
<div>非可疑度。</div>
<div></div></div>

# Output

<div class="content"><p>总共Q行，每一行一个实数，表示花花第i次需要计算的答</p>
<div>案。你的答案需要和标准答案的差不超过0.01才能得分。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
6 6 <br/>
3 4 <br/>
5 6 <br/>
1 3 <br/>
4 4 <br/>
3 3 <br/>
2 4 <br/>
1 2 <br/>
1 3 <br/>
2 3 <br/>
2 4 <br/>
3 5 <br/>
5 6 <br/>
3 <br/>
3 6 <br/>
2 4 <br/>
4 6 </span></div>

# Sample Output

<div class="content"><span class="sampledata">0.66667 <br/>
0.00000 <br/>
1.67544<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

