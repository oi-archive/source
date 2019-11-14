
# Description

<div class="content"><div style="text-indent: 20.25pt"><span style="font-size: medium">给出平面上的<i>M</i>条平行于坐标轴的线段，问有多少个正方形。</span></div>
<div style="text-indent: 20.25pt"><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div style="text-indent: 20.25pt"><span style="font-size: medium">第1行为两个正整数<i>N</i>，<i>M</i>。</span></div>
<div style="text-indent: 20.25pt"><span style="font-size: medium">接下来<i>M</i>行，每行4个非负整数<i>x</i><sub>1</sub>，<i>y</i><sub>1</sub>，<i>x</i><sub>2</sub>，<i>y</i><sub>2</sub>（0≤<i>x</i><sub>1</sub>≤<i>x</i><sub>2</sub>≤<i>N</i>，0≤<i>y</i><sub>1</sub>≤<i>y</i><sub>2</sub>≤<i>N</i>），描述了线段的两个端点。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div style="text-indent: 20.25pt"><span style="font-size: medium">仅包括一个正整数，为平面上正方形的个数。</span></div>
<div style="text-indent: 20.25pt"><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 8<br/>
0 0 0 3<br/>
1 0 1 3<br/>
2 0 2 2<br/>
3 0 3 3<br/>
0 0 3 0<br/>
0 1 3 1<br/>
0 2 3 2<br/>
0 3 3 3<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">11<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p>【样例说明】<br/><br/>
样例对应了如下一张图<br/><br/>
其中边长为1的正方形有7个，边长为2的正方形有3个，边长为3的正方形有1个。<br/><br/>
所以答案为7+3+1=11。<br/><br/>
 <br/><br/>
【数据规模】<br/><br/>
对于20%的数据，有N≤30；<br/><br/>
对于40%的数据，有N≤100；<br/><br/>
对于60%的数据，有N≤800； <br/><br/>
对于100%的数据，有N≤1000，M≤400000，并保证任意两条线段没有重合部分。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2011福建集训">2011福建集训</a></p></div>

