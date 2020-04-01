
# Description

<div class="content"><p>win 世界乒乓球比赛马上要拉开帷幕，你被邀请成为组委会成员，并且负责安排比赛赛程。比赛采取淘汰赛赛制，失败的一方将被直接淘汰。  你手上现在有一份各个队员近期的战况，战况包含任意两名队员的最近一次交手结果。你默认这份对战结果将代表比赛的结果。 现在，你的好友要参加乒乓球比赛，你需要帮好友算一下，你可以安排出多少种淘汰赛赛程使得你的这位好友能够拿到最终的冠军。 当然，介于比赛的公平性，赛程的安排需要遵循这个原则，那就是使得淘汰赛的赛程树高度最低，也就是说，使得每位选手打的比赛数尽量平均。</p></div>

# Input

<div class="content"><p>本题为多组数据，每组数据第一行有两个整数N,M。N表示总共有N位选手参加比赛，M表示你的好友的编号。(2&lt;=N&lt;=16, 1&lt;=M&lt;=N) 接下来一个N*N的矩阵，表示选手两两间交手的胜负。其中第i行，第j列的数Ai,j表示其胜负关系，并且满足0 &lt;= Ai,j &lt;= 1, Ai,j =1 - Aj,i，Ai,i=0，Ai,j为1表示i胜过j，Ai,j为0表示i输过j。 请做到文件底结束</p></div>

# Output

<div class="content"><p>每组数据输出一行。表示有多少种赛程安排可以使你的朋友拿到冠军。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2 1<br/>
0 1<br/>
0 0<br/>
2 1<br/>
0 0<br/>
1 0<br/>
3 3<br/>
0 1 1<br/>
0 0 1<br/>
0 0 0<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
0<br/>
0<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

