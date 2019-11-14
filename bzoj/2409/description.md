
# Description

<div class="content"><p>小Y喜欢速度与激情，于是他参加了地下车会。  地下车会设有N 个<br/>
分赛区，M种赛事。每个分赛区有C[i]场比赛。由于地下车会经营者<br/>
想要赚到更多的钱，规定小 Y 必须参加某一些赛区的一些赛事。且<br/>
每个赛区至少参加L[i]场比赛。小Y不想在一个地区逗留太久惹上麻<br/>
烦，所以每个赛区他最多参加P[i]场比赛。可能是因为经营者对新手<br/>
有歧视心理，规定了小 Y 每种赛事最多只能进行 A[i]场比赛。小 Y<br/>
这个月资金有点紧张，他算了算自己最多只能够维护车子跑 K 场比<br/>
赛。由于小 Y 是新手，所以他希望积累更多的经验，也就是跑尽可<br/>
能多的赛事。</p></div>

# Input

<div class="content"><p>第一行三个数N,M,K，用空格隔开。 <br/>
接下来N行，每行第一个数C[i]，接下来 C[i]个数，代表每场比赛的<br/>
种类，种类可能重复。 <br/>
接下来一行一个数F，代表规定条数。 <br/>
接下来 F 行，每行两个数 A，B，代表小 Y 必须参加 A 赛区的 B 种<br/>
赛事一次及以上。一种规定只会出现一次。 <br/>
接下来一行M个数，代表A[i]。 <br/>
接下来N行，每行两个数P[i],L[i]。</p></div>

# Output

<div class="content"><p>第一行一个数ans，表示小Y最多能跑几场赛事。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5 15 <br/>
5 1 1 2 2 3 <br/>
6 2 2 3 4 5 5 <br/>
3 1 2 3 <br/>
6 1 2 3 4 5 5 <br/>
4 3 3 4 4 <br/>
3 <br/>
1 2 <br/>
2 5 <br/>
5 3 <br/>
2 2 3 2 3 <br/>
4 2 <br/>
4 2 <br/>
2 1 <br/>
5 3 <br/>
3 1 </span></div>

# Sample Output

<div class="content"><span class="sampledata">12</span></div>

# Hint

<div class="content"><p></p><p>前 100% 的数据， 1&lt;=N&lt;=500 ， 1&lt;=M&lt;=500 ， 1&lt;=C[i]&lt;=500 ，<br/><br/>
1&lt;=F&lt;=100000 <br/><br/>
【友情提示】 <br/><br/>
对于所有的数据， 1&lt;=L[i]&lt;=P[i]&lt;=C[i]， 1&lt;=A[i]&lt;=10^4， K&lt;= 200000，<br/><br/>
数据保证合法。 <br/><br/>
 </p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

