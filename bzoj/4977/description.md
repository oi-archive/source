
# Description

<div class="content"><div>小Q最近沉迷于《跳伞求生》游戏。他组建了一支由n名玩家（包括他自己）组成的战队，编号依次为1到n。这个游</div>
<div>戏中，每局游戏开始时，所有玩家都会从飞机上跳伞，选择一个目的地降落，跳伞和降落的时间有早有晚。在某局</div>
<div>游戏降落前，他们在空中观察发现地面上一共有m间房子，编号依次为1到m。其中每间房子恰好有一名敌人早于他</div>
<div>们到达。小Q战队的第i名玩家拥有a_i发子弹，地面上第i间房子里的敌人拥有b_i发子弹，消灭他可以获得c_i点积</div>
<div>分。每名玩家必须且只能选择一间房子降落，然后去消灭里面的敌人。若第i名玩家选择了第j间房子，如果a_i&gt;b_</div>
<div>j，那么他就可以消灭该敌人，获得a_i-b_j+c_j的团队奖励积分，否则他会被敌人消灭。为了防止团灭，小Q不允</div>
<div>许多名玩家选择同一间房子，因此如果某位玩家毫无利用价值，你可以选择让他退出游戏。因为房子之间的距离过</div>
<div>长，你可以认为每名玩家在降落之后不能再去消灭其它房间里的敌人。作为小Q战队的指挥，请制定一套最优的降</div>
<div>落方案，使得最后获得的团队奖励总积分最大</div></div>

# Input

<div class="content"><div>第一行包含两个正整数n,m(1&lt;=n,m&lt;=100000)，分别表示战队的玩家数和地面上的房间数。</div>
<div>第二行包含n个正整数a_1,a_2,...,a_n(1&lt;=a_i&lt;=100000)，分别表示每个玩家的子弹数。</div>
<div>接下来m行，每行两个正整数b_i,c_i(1&lt;=b_i,c_i&lt;=100000)，分别表示每个敌人的子弹数和奖励积分。</div></div>

# Output

<div class="content"><div>输出一行一个整数，即最后获得的团队奖励总积分的最大值。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
4 4 4<br/>
2 3<br/>
1 3<br/>
5 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">11</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=claris原创，本oj版权所有,翻版必究">claris原创，本oj版权所有,翻版必究</a></p></div>

