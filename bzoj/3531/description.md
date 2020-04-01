
# Description

<div class="content"><p><span style="font-size: medium"> S国有N个城市，编号从1到N。城市间用N-1条双向道路连接，满足<br/>
从一个城市出发可以到达其它所有城市。每个城市信仰不同的宗教，如飞天面条神教、隐形独角兽教、绝地教都是常见的信仰。为了方便，我们用不同的正整数代表各种宗教，  S国的居民常常旅行。旅行时他们总会走最短路，并且为了避免麻烦，只在信仰和他们相同的城市留宿。当然旅程的终点也是信仰与他相同的城市。S国政府为每个城市标定了不同的旅行评级，旅行者们常会记下途中（包括起点和终点）留宿过的城市的评级总和或最大值。<br/>
    在S国的历史上常会发生以下几种事件：<br/>
”CC x c”：城市x的居民全体改信了c教；<br/>
”CW x w”：城市x的评级调整为w;<br/>
”QS x y”：一位旅行者从城市x出发，到城市y，并记下了途中留宿过的城市的评级总和；<br/>
”QM x y”：一位旅行者从城市x出发，到城市y，并记下了途中留宿过<br/>
的城市的评级最大值。<br/>
    由于年代久远，旅行者记下的数字已经遗失了，但记录开始之前每座城市的信仰与评级，还有事件记录本身是完好的。请根据这些信息，还原旅行者记下的数字。    为了方便，我们认为事件之间的间隔足够长，以致在任意一次旅行中，所有城市的评级和信仰保持不变。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">    输入的第一行包含整数N，Q依次表示城市数和事件数。<br/>
    接下来N行，第i+l行两个整数Wi，Ci依次表示记录开始之前，城市i的<br/>
评级和信仰。<br/>
    接下来N-1行每行两个整数x，y表示一条双向道路。<br/>
    接下来Q行，每行一个操作，格式如上所述。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">    对每个QS和QM事件，输出一行，表示旅行者记下的数字。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">    5 6<br/>
    3 1<br/>
    2 3<br/>
    1 2<br/>
    3 3<br/>
    5 1<br/>
    1 2<br/>
    1 3<br/>
    3 4<br/>
    3 5<br/>
    QS 1 5<br/>
    CC 3 1<br/>
    QS 1 5<br/>
    CW 3 3<br/>
    QS 1 5<br/>
    QM 2 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">    8<br/>
    9<br/>
    11<br/>
    3</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">N，Q &lt; =10^5    ， C &lt; =10^5 </span></p><br/>
<p><span style="font-size: medium"> 数据保证对所有QS和QM事件，起点和终点城市的信仰相同；在任意时<br/><br/>
刻，城市的评级总是不大于10^4的正整数，且宗教值不大于C。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round 1 Day 1">Round 1 Day 1</a></p></div>

