
# Description

<div class="content"><p><span style="font-size: medium">Codeforces要举办一场计算机比赛，主办方将所有人安排在一个n*m的网格图的点上（也就是总共有(n+1)*(m+1)个人参加了本次比赛），然后主办方给每个人都配备了一台计算机（也就是说n*m的网格图的每个格点上都有一台计算机，计算机的体积忽略不计）。<br/>
但是主办方由于没钱或者是其它原因，不能给计算机配备挡板（主办方：能准备这么多台计算机就不错了），因此一些人就可以直接看到别人的计算机屏幕（当然肯定会先装作四处看风景然后顺便看看啦2333），一个人要看到其他人的计算机屏幕当且仅当：<br/>
1、这两个人的连线之间没有其它计算机遮挡（这个原因是显然的吧）。<br/>
2、两个人之间的欧氏距离在[l,r]之间，因为如果两个人距离太近，那么一个人看另一个人的计算机屏幕时就很容易被发现，而两个人距离太远的话就看不到了。<br/>
由以上两个条件可以很容易地知道，如果A能看到B的计算机屏幕，那么B也能看到A的计算机屏幕。<br/>
现在主办方想做好反作弊的准备，第一步就是求出满足A和B都能看到对方的计算机屏幕的(A,B)的对数，由于这个结果可能很大，你只需要输出其模mod的值。<br/>
注：(A,B)和(B,A)视为相同。<br/>
搬运工蒟蒻ZLD：我这人比较弱所以copy的题也很弱，各位神犇求轻虐~~~~(&gt;_&lt;)~~~~ </span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行有两个正整数n和m。<br/>
第二行有三个正整数，分别表示l、r和mod。</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">输出1行一个数，表示所求对数模mod的值</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">1 1<br/>
1 2 100<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">【样例解释】<br/><br/>
    样例是一个正方形，距离为1的点对有4个，距离为2的点对有2个。</span></p><br/>
<p><span style="font-size: medium">【数据范围】<br/><br/>
对于100%的数据，n,m&lt;=100000，l,r&lt;=150000，mod&lt;=1000000000</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

