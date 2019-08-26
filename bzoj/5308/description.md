
# Description

<div class="content"><div>Cedyks是九条可怜的好朋友（可能这场比赛公开以后就不是了），也是这题的主人公。</div>
<div>Cedyks是一个富有的男孩子。他住在著名的ThePLace（宫殿）中。</div>
<div>Cedyks是一个努力的男孩子。他每天都做着不一样的题来锻炼他的The SaLt（灵魂）。</div>
<div>这天，他打算在他的宫殿外围修筑一道城墙，城墙上有n座瞭望塔。</div>
<div>你可以把城墙看做一条线段，瞭望塔是线段上的n个点，其中1和n分别为城墙的两个端点。</div>
<div>其中第i座瞭望塔和第i+1座瞭望塔的距离为wi，他们之间的道路是双向的。</div>
<div>城墙很快就修建好了，现在Cedyks开始计划修筑他的宫殿到城墙的道路。</div>
<div>因为这题的题目名称,</div>
<div>Cedyks打算用他的宫殿到每一个瞭望塔的最短道路之和来衡量一个修建计划。</div>
<div>现在Cedyks手上有m个设计方案，第k个设计方案会在宫殿和瞭望塔之间修建Tk条双向道路，</div>
<div>第i条道路连接着瞭望塔ai，长度为Li。</div>
<div>计算到每一个瞭望塔的最短路之和是一个繁重的工程，本来Cedyks想用广为流传的SPFA算法</div>
<div>来求解，但是因为他的butter（缓冲区）实在是太小了，他只能转而用原始的贝尔福特曼算法</div>
<div>来计算，算法的流程大概如下：</div>
<div></div>
<div>1:定义宫殿是0号点，第i个瞭望塔是i号点，双向边(ui,vi,Li)为一条连接ui和vi的双向道路。</div>
<div>令d为距离数组，最开始d<sub>0</sub>=0,d<sub>i</sub>=10^18(i∈[1,n])。</div>
<div></div>
<div>2:令辅助数组c=d。依次对于每一条边(u<sub>i</sub>,v<sub>i</sub>,w<sub>i</sub>)进行增广，</div>
<div>c<sub>ui</sub>=min(c<sub>ui</sub>,d<sub>vi</sub>+w<sub>i</sub>)，</div>
<div>c<sub>vi</sub>=min(c<sub>vi</sub>,dui+w<sub>i</sub>)。</div>
<div>3:令t为c和d中不一样的位置个数，即令S={i|c<sub>i</sub>!=d<sub>i</sub>}，则t=S。若t=0，说明d</div>
<div>就是最终的最短路，算法结束。否则令d=c，回到第二步。</div>
<div></div>
<div>因为需要计算的设计方案实在是太多了，所以Cedyks雇佣了一些人来帮他进行计算。</div>
<div>为了避免这些人用捏造出来的数据偷懒，他定义一个设计方案的校验值为在这个方案</div>
<div>上运行贝尔福特曼算法每一次进入第三步t的和。他会让好几个雇佣来的人计算同样</div>
<div>的设计方案，并比对每一个人给出的校验值。</div>
<div></div>
<div>你是Cedyks雇佣来的苦力之一，聪明的你发现在这个情形下计算最短路的长度的和</div>
<div>是一件非常简单的事情。但是寄人篱下不得不低头，你不得不再计算出每一个方案</div>
<div>的校验值来交差。</div>
<div></div></div>

# Input

<div class="content"><div>第一行输入两个整数n,m，表示瞭望塔个数和设计方案个数。</div>
<div>接下来一行n-1个数wi，表示瞭望塔i和i+1之间道路的长度。</div>
<div>接下来m行，每行描述一个设计方案。</div>
<div>第一个整数K表示设计方案中的道路数量，</div>
<div>接下来K个数对(ai,Li)为一条宫殿到瞭望塔的边。</div>
<div>1 &lt;= wi, li &lt;= 109, 1 &lt;= ∑ K &lt;= 2 × 10^5</div>
<div>N,M&lt;=2*10^5</div></div>

# Output

<div class="content"><p>对于每一个设计方案，输出一行一个整数表示校验值。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
2 3 1 4<br/>
1 2 2<br/>
2 1 1 4 10<br/>
3 1 1 3 1 5 1<br/>
3 1 10 2 100 5 1<br/>
5 1 1 2 1 3 1 4 1 5 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
8<br/>
5<br/>
8<br/>
5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

