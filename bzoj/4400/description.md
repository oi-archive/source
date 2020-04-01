
# Description

<div class="content"><p>有n个岛屿，m座桥，每座桥连通两座岛屿，桥上会有一些敌人，玩家只有消灭了桥上的敌人才能通过，与此同时桥上的敌人会对玩家造成一定伤害。而且会有一个大Boss镇守一座桥，以玩家目前的能力，是不可能通过的。而Boss是邪恶的，Boss会镇守某一座使得玩家受到最多的伤害才能从岛屿1到达岛屿n(当然玩家会选择伤害最小的路径)。问，Boss可能镇守桥有哪些。</p></div>

# Input

<div class="content"><p>第一行两个整数n,m<br/>
接下来m行，每行三个整数s,t,c，表示一座连接岛屿s和t的桥上的敌人会对玩家造成c的伤害。</p></div>

# Output

<div class="content"><p>一行，两个整数d,cnt，d表示有Boss的情况下，玩家要受到的伤害，cnt表示Boss有可能镇守的桥的数目。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
1 2 1<br/>
1 2 2<br/>
2 3 1<br/>
2 3 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 1</span></div>

# Hint

<div class="content"><p></p><p>100%的数据，1&lt;=n&lt;=100000，1&lt;=m&lt;=200000，1&lt;=c&lt;=10000，数据保证玩家可以从岛屿1到达岛屿n</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

