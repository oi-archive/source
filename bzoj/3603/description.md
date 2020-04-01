
# Description

<div class="content"><div>Alice 发现：人在心情不好的时候，便会选择酗酒。这往往与OI 选手比赛胜利后的欢腾庆祝不同，酗酒者喝醉后便会忘记回家的路，然后在大街上无规律地乱走乱逛，同时喊着一些谁也听不懂的话。 </div>
<div>这几天，Bob 因为考试的原因心情很不好，每天晚上都会在城里面找一处酒吧。喝醉后离开酒吧开始在城市街道中无规律乱走，直到某一时刻，若他碰巧遇到了在夜晚出来看星星的Alice，便会被她带回家。 </div>
<div>已知Alice 和Bob 所在的城市街道可以被描绘为一个N 行M 列的格点地图，N 行依次编号为0 到N-1，M 列依次编号为0 到M-1。城市中共有N*M 处路口，每一个路口可以用坐标(i,j)表示。若i对于给定的两个点(u,v)和(s,t)分别为Bob 今晚去的酒吧的位置，和Alice 今晚看星星的位置。Bob 离开酒吧后，对于每一个路口，他会等概率选择其中之一，然后走向下一个路口。 </div>
<div>在走到下一个路口之前，Bob 不会回头。同时Bob 并不会因为之前走过什么道路而影响之后的行走路线。 </div>
<div>具体来说：如果Bob 从(3,4)走到(3,5)，他有可能在抵达(3,5)后立刻折回(3,4)。对于四叉路口，Bob 向每一个方向行走的概率都是1/4，对于三叉路口（这只存在于城市的边界上）则是1/3，对于二叉路口（这只存在于城市的4 个角落）就是1/2。 </div>
<div>Alice 希望知道，从Bob 离开酒吧，Alice 期望情况下还需要等多久才能等到Bob，即对于给定的两个点(u,v)与(s,t)，Bob 从(u,v)走到(s,t)的期望用时是多少？ </div></div>

# Input

<div class="content"><div>第一行N，M。 之后N-1 行，每行M 个正整数，其中第i 行第j 个为p[i][j]。 </div>
<div>之后N 行，每行M-1 个正整数，其中第i 行第j 个为q[i][j]。 </div>
<div>单独一行给出一个整数Q，表示总询问次数。 </div>
<div>之后Q 行，每行有4 个整数u，v，s，t。</div></div>

# Output

<div class="content"><div>一共Q 行，每一行对应一次询问：从(u,v)走到(s,t)的期望距离是多少？你的答案可以保 </div>
<div>留任意多位小数，但只有与正确答案的错误率在0.1%内才算正确。</div></div>

# Sample Input

<div class="content"><span class="sampledata">2 2<br/>
1 2<br/>
3<br/>
4<br/>
4<br/>
0 0 0 1<br/>
1 0 0 1<br/>
1 1 0 1<br/>
0 1 1 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">7.0000<br/>
10.0000<br/>
8.0000<br/>
10.0000</span></div>

# Hint

<div class="content"><p></p><div>对于10%的数据，N*M&lt;=25。 </div><br/>
<div>对于30%的数据，N*M&lt;=625。 </div><br/>
<div>对于50%的数据，N*M&lt;=2500。 </div><br/>
<div>对于100%的数据，N*M&lt;=10000，Q&lt;=100。p[][]和q[][]&lt;=200。 </div><br/>
<div>此外存在10%的数据，min{N,M}&lt;=10。 </div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

