
# Description

<div class="content"><div>由乃在自己的农田边散步，她突然发现田里的一排玉米非常的不美。这排玉米一共有N株，它们的高度参差不齐。</div>
<div>由乃认为玉米田不美，所以她决定出个数据结构题</div>
<div> </div>
<div>这个题是这样的：</div>
<div>给你一个序列a，长度为n，有m次操作，每次询问一个区间是否可以选出两个数它们的差为x，或者询问一个区间是</div>
<div>否可以选出两个数它们的和为x，或者询问一个区间是否可以选出两个数它们的乘积为x ，这三个操作分别为操作1</div>
<div>,2,3选出的这两个数可以是同一个位置的数</div>
<div><img src="/source/bzoj/4810/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwNC92djEoNCkuanBn.jpg" width="363" height="655" alt=""/></div>
<p></p></div>

# Input

<div class="content"><div>第一行两个数n,m</div>
<div>后面一行n个数表示ai</div>
<div>后面m行每行四个数opt l r x</div>
<div>opt表示这个是第几种操作，l,r表示操作的区间，x表示这次操作的x</div>
<div>定义c为每次的x和ai中的最大值，ai &gt;= 0，每次的x&gt;=2n,m,c &lt;= 100000</div>
<p></p></div>

# Output

<div class="content"><div>对于每个询问，如果可以，输出yuno，否则输出yumi</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
1 1 2 3 4<br/>
2 1 1 2<br/>
1 1 2 2<br/>
3 1 1 1<br/>
3 5 5 16<br/>
1 2 3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">yuno<br/>
yumi<br/>
yuno<br/>
yuno<br/>
yumi<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名提供">By 佚名提供</a></p></div>

