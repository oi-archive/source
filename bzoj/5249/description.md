
# Description

<div class="content"><div>【题目背景】</div>
<div>Osu听过没？那是Konano最喜欢的一款音乐游戏，而他的梦想就是有一天自己也能做个独特酷炫的音乐游戏。现在</div>
<div>，他在世界知名游戏公司KONMAI内工作，离他的梦想也越来越近了。这款音乐游戏内一般都包含了许多歌曲，歌曲</div>
<div>越多，玩家越不易玩腻。同时，为了使玩家在游戏上氪更多的金钱花更多的时间，游戏一开始一般都不会将所有曲</div>
<div>目公开，有些曲目你需要通关某首特定歌曲才会解锁，而且越晚解锁的曲目难度越高。</div>
<div>【题目描述】</div>
<div>这一天，Konano接到了一个任务，他需要给正在制作中的游戏《IIIDX》安排曲目的解锁顺序。游戏内共有n首曲目</div>
<div>，每首曲目都会有一个难度d，游戏内第i首曲目会在玩家Pass第trunc(i/k)首曲目后解锁（x为下取整符号）若tru</div>
<div>nc(i/k)=0，则说明这首曲目无需解锁。举个例子：当k=2时，第1首曲目是无需解锁的（trunc(1/2)=0），第7首曲</div>
<div>目需要玩家Pass第trunc(7/2)=3首曲目才会被解锁。Konano的工作，便是安排这些曲目的顺序，使得每次解锁出的</div>
<div>曲子的难度不低于作为条件需要玩家通关的曲子的难度，即使得确定顺序后的曲目的难度对于每个i满足Di≥Dtrun</div>
<div>c(i/k)。当然这难不倒曾经在信息学竞赛摸鱼许久的Konano。那假如是你，你会怎么解决这份任务呢</div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div></div>

# Input

<div class="content"><div>第1行1个正整数n和1个小数k，n表示曲目数量，k其含义如题所示。</div>
<div>第2行n个用空格隔开的正整数d，表示这n首曲目的难度。</div>
<div>1 ≤ n ≤ 500000</div>
<div>1 &lt; k ≤ 10^9</div>
<div>1 &lt; d ≤ 10^9</div></div>

# Output

<div class="content"><div>输出1行n个整数，按顺序输出安排完曲目顺序后第i首曲目的难度。</div>
<div>若有多解，则输出d1最大的；若仍有多解，则输出d2最大的，以此类推。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 2.0<br/>
114 514 1919 810<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">114 810 514 1919</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

