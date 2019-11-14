
# Description

<div class="content"><div>n个选手打淘汰赛，当n是2的幂的时候，比赛过程可以如下递归描述：选手被分成等大小的两组，每组分别决出冠</div>
<div>军，然后两个冠军再进行一次比赛，每一个输的选手都会被淘汰出局。当n不是2的幂的时候，后面的一些选手在第</div>
<div>一轮中就不会被安排比赛，所以第二轮比赛中剩余选手数一定是2的幂。</div>
<div><img src="/source/bzoj/5199/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMy8xLmpwZw==.jpg" width="200" height="126" alt=""/></div>
<div>每个选手都有一个力量值r_i，当A对决B时，A的胜率为r_A/(r_A+r_B)，B的胜率同理。</div>
<div>你是1号选手，且你可以安排所有选手第一次的对决情况，请找到一种方式使得你夺冠的概率最大。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含一个正整数n(2&lt;=n&lt;=4096)，表示选手总数。</div>
<div>第二行包含n个正整数r_1,r_2,...,r_n(1&lt;=r_i&lt;=100000)，分别表示每个选手的力量值。</div>
<div></div></div>

# Output

<div class="content"><div>输出一行一个实数，即最大的胜率，绝对或相对误差小于10^{-6}将被接受。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
3<br/>
1<br/>
2<br/>
4</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.364285714</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

