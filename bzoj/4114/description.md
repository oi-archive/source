
# Description

<div class="content"><p> 有一艘大小可忽略的轮渡要沿着一条由南向北的穿越线匀速横渡海峡。但是海域中有很多条平行的东西方向的航道。航道上所有的船都按照恒定的速率沿直线行进，每条航道上的船要么都往东开，要么都往西开。现在要找一个最大的时间段，在这个时间段内出发，轮渡可以安全的横渡海峡。安全横渡即意味着在轮渡进入和离开每一条航道的这一段时间里，那条航道上的所有船都不能与穿越线接触。</p></div>

# Input

<div class="content"><p> 第一行包含6个整数：航道的数目n(1≤n≤100,000)，每条航道的宽度w(1≤w≤1000)，船的速度u和轮渡的速度v(1≤u,v≤100)以及轮渡最早出发时间t1和最晚出发时间t2(0≤t1,t2≤1000,000) （长度单位：m，时间单位：s，速度单位：m/s）</p>
<div>接下来n行包含每个航道的信息。每行开头是一个字符“E”或“W”，代表这条航道上的船只的航行方向；接下来是一个整数mi(0≤mi≤100,000)，接着mi对整数lij和pij描述这mi只船的信息(1≤lij≤1000，-1000,000≤pij≤1000,000)：lij代表这艘船的长度而pij代表时刻0时这艘船船头所在的位置。</div>
<div>这里的位置是相对于穿越线而言的，坐标为负则在穿越线的西边，坐标为正则在穿越线的东边。每条航道上的船不会接触或重叠，并且每条航道上的船按坐标的升序给出。相邻航道之间紧邻，并且我们从南到北给出每条航道的信息。我们假定初始时轮渡在第一条航道的南端。所有航道上船的总数m不超过100,000。</div></div>

# Output

<div class="content"><p> 输出一个最大时间间隔d，即存在一个时间s，在[s,s+d]内任意时间出发都能安全的横渡海峡。并且出发时间不能早于t1也不能晚于t2。输出答案与标准答案的绝对误差和相对误差不超过1e-3。我们假定存在这样的时间间隔大于0.1。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 100 5 10 0 100<br/>
E 2 100 -300 50 -100<br/>
W 3 10 60 50 200 200 400<br/>
E 1 100 -300</span></div>

# Sample Output

<div class="content"><span class="sampledata">6.00000000<br/>
</span></div>

# Hint

<div class="content"><p></p><p><img src="/source/bzoj/4114/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwOS8xMS5qcGc=.jpg" width="651" height="268" alt=""/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Phile提供译文">鸣谢Phile提供译文</a></p></div>

