
# Description

<div class="content"><p><span style="font-size: medium"><br/>
Neverland是个神奇的地方，它由一些岛屿环形排列组成，每个岛上都生活着之中与众不同的物种。但是这些物种都有一个共同的生活习性：对于同一个岛上的任意两个生物，他们有且仅有一个公共朋友，即对同一岛上的任意两个生物a和b有且仅有一个生物c既是a的朋友也是b的朋友，当然某些岛上也可能会只有一个生物孤单地生活着。这一习性有一个明显的好处，当两个生物发生矛盾的时候，他们可以请那个唯一的公共朋友来裁决谁对谁错。</span></p>
<p><span style="font-size: medium">另外，岛与岛之间也有交流，具体来说，每个岛都会挑选出一个最聪明的生物做代表，然后这个生物与他相邻的两个岛的代表成为朋友。</span></p>
<p><span style="font-size: medium">不行的是，A世界准备入侵Neverland，作为Neverland的守护者，Lostmonkey想知道在一种比较坏的情况下Never的战斗力。因为和朋友并肩作战，能力会得到提升，所以Lostmonkey想知道在不选出一对朋友的情况下Neverland的最大战斗力。即选出一些生物，且没有一对生物是朋友，并且要求它们的战斗力之和最大。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行包含用空格隔开的两个整数n和m，分别表示Neverland的生物种数和朋友对数。接下来的m行描述所有朋友对，具体来说，每行包含用空格隔开的两个整数a和b，表示生物a和生物b是朋友（每对朋友只出现一次）。第m+2行包含用空格隔开的n个整数，其中第i个整数表示生物i的战斗力Ai。输入数据保证4&lt;=n&lt;=100000，1&lt;=a,b&lt;=n，1&lt;=m&lt;=200000，-1000&lt;=Ai&lt;=1000.</span></p>
<p></p></div>

# Output

<div class="content"><p> </p>
<p><span style="font-size: medium">仅包含一个整数，表示满足条件的最大战斗力。</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
<br/>
6 7<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 1<br/>
3 6<br/>
3 5<br/>
5 6<br/>
20 10 30 15 20 10<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
50<br/>
<br/>
【样例说明】<br/>
<br/>
有四个岛，生物1在1号岛，生物2在2号岛，生物3、5、6在3号岛，生物4在4号岛。<br/>
</span></div>

# Hint

<div class="content"><p></p><p>NeverLand这个单词在“小飞侠彼得潘”中译为梦幻岛，在这却成为无归岛，真是汗啊.</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

