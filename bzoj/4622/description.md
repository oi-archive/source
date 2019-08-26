
# Description

<div class="content"><div>
<div>B国在耗资百亿元之后终于研究出了新式武器——连环阵（Zenith Protected Linked Hybrid Zone）。传说中，连</div>
<div>环阵是一种永不停滞的自发性智能武器。但经过A国间谍的侦察发现，连环阵其实是由M个编号为1，2，…，M的独</div>
<div>立武器组成的。最初，1号武器发挥着攻击作用，其他武器都处在无敌自卫状态。以后，一旦第i（1&lt;=i&lt; M）号武</div>
<div>器被消灭，1秒种以后第i+1号武器就自动从无敌自卫状态变成攻击状态。当第M号武器被消灭以后，这个造价昂贵</div>
<div>的连环阵就被摧毁了。为了彻底打击B国科学家，A国军事部长打算用最廉价的武器——炸弹来消灭连环阵。经过长</div>
<div>时间的精密探测，A国科学家们掌握了连环阵中M个武器的平面坐标，然后确定了n个炸弹的平面坐标并且安放了炸</div>
<div>弹。每个炸弹持续爆炸时间为5分钟。在引爆时间内，每枚炸弹都可以在瞬间消灭离它平面距离不超过k的、处在攻</div>
<div>击状态的B国武器。和连环阵类似，最初a1号炸弹持续引爆5分钟时间，然后a2号炸弹持续引爆5分钟时间，接着a3</div>
<div>号炸弹引爆……以此类推，直到连环阵被摧毁。显然，不同的序列a1、a2、a3...消灭连环阵的效果也不同。好的</div>
<div>序列可以在仅使用较少炸弹的情况下就将连环阵摧毁；坏的序列可能在使用完所有炸弹后仍无法将连环阵摧毁。现</div>
<div>在，请你决定一个最优序列a1、a2、a3…使得在第ax号炸弹引爆的时间内连环阵被摧毁。这里的x应当尽量小</div>
</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含三个整数：M、n和k（1&lt;=M, n&lt;=100，1&lt;=k&lt;=1000），分别表示B国连环阵由M个武器组成，A国有n个炸</div>
<div>弹可以使用，炸弹攻击范围为k。以下M行，每行由一对整数xi，yi（0&lt;=xi，yi&lt;=10000）组成，表示第i（1&lt;=i&lt;=M</div>
<div>）号武器的平面坐标。再接下来n行，每行由一对整数ui，vi(0&lt;=ui，vi&lt;=10000)组成，表示第i（1&lt;=i&lt;=n）号炸</div>
<div>弹的平面坐标。输入数据保证随机、无误、并且必然有解。</div>
<p></p></div>

# Output

<div class="content"><div>一行包含一个整数x，表示实际使用的炸弹数.</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">Sample Input 1<br/>
4 3 6 <br/>
0 6 <br/>
6 6 <br/>
6 0 <br/>
0 0 <br/>
1 5 <br/>
0 3 <br/>
1 1  <br/>
<br/>
Sample Input 2<br/>
10 10 45 <br/>
41 67 <br/>
34 0 <br/>
69 24 <br/>
78 58 <br/>
62 64 <br/>
5 45 <br/>
81 27 <br/>
61 91 <br/>
95 42 <br/>
27 36 <br/>
91 4 <br/>
2 53 <br/>
92 82 <br/>
21 16 <br/>
18 95 <br/>
47 26 <br/>
71 38 <br/>
69 12 <br/>
67 99 <br/>
35 94 </span></div>

# Sample Output

<div class="content"><span class="sampledata">Sample Output 1<br/>
2<br/>
<br/>
Sample Output 2<br/>
5<br/>
HINT<br/>
输出数据为NOI原数据<br/>
输出数据由楼教主代码制作<br/>
原题有spj 此题去掉spj 只输出最优解</span></div>

# Hint

<div class="content"><p></p><p> NOI2003 Day2 T3  感谢sxb_201上传</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢刘汝佳先生授权使用">鸣谢刘汝佳先生授权使用</a></p></div>

