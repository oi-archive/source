
# Description

<div class="content"><div>n=3^m个人在玩石头剪刀布，一共有t轮游戏，每轮有m次石头剪刀布。</div>
<div>在同一轮的m次游戏中，每个人的决策必须是提前确定的，也就是说不能采用随机策略，也不能根据前若干局的结果决定下一局的决策；这样，显然一共有n=3^m种决策。</div>
<div>这n=3^m个人会采取两两不同的决策。为了方便表达，对于第x（0≤x&lt;n）个人，将x转换成三进制得到一个m位的数。其中0表示剪刀，1表示石头，2表示布。就得到了第x个人采取的策略。</div>
<div>由于编号是固定的，因此每个人在不同轮的m次游戏中都会采取同一套决策。</div>
<div>第x个人在最初时有一个分数f<sub>0,x</sub>。</div>
<div>在第i轮中，他将和另一个人y进行m次的石头剪刀布的比赛。</div>
<div>我们用W(x,y)表示x在和y的m次比赛中赢的次数；用L(x,y)表示x在和y的m次比赛中输的次数。</div>
<div>在第i轮结束之后，第x个人分数是：</div>
<div>fi,x=∑f<sub>i−1,y</sub>b<sub>u,v</sub>(0≤y&lt;n)</div>
<div>其中u=W(x,y)=L(y,x),v=L(x,y)=W(y,x)，平局不计入次数；bu,v则是一个给定的评分数组。</div>
<div>注意即使y和x一样（自己转移到自己）也会乘上一个系数b0,0（即自己跟自己打全为平局）。</div>
<div>显然随着轮数越来越多，分数也会越来越大，这个计分系统和我们平时用的计算机一样，也会溢出。当要储存的分数f大于等于p的时候，就会变成f mod p。</div>
<div>B君想知道t轮之后所有人的分数，也就是f<sub>t,0</sub>,f<sub>t,1</sub>,…,f<sub>t,n−1</sub>。</div>
<div>G君：「诶，我发现这个数p有特殊的性质诶！不存在两个正整数，使得他们倒数的和等于3/p」</div>
<div>B君：「G君好棒！不过这个题怎么做呢？」</div>
<div></div></div>

# Input

<div class="content"><div>第一行三个整数，表示m,t,p。保证0≤m≤12，0≤t≤1000000000，1≤p≤1000000000。</div>
<div>第二行有n=3m个整数，表示f<sub>0,0</sub>,f<sub>0,1</sub>,…,f<sub>0,n−1</sub>。保证0≤f<sub>0,i</sub>&lt;p。</div>
<div>接下来的部分是一个数组b，第1行m+1个数，第2行m个数……第m+1行1个数。</div>
<div>其中第i行的第j个数为b<sub>i−1,j−1</sub>（i,j≥1,i+j−2≤m），保证0≤b<sub>i,j</sub>&lt;p。</div>
<div>不存在两个正整数，使得他们倒数的和等于3/p。即不存在正整数x,y&gt;0，使得1/x+1/y=3/p。</div>
<div>m&lt;=12,T&lt;=10^9</div>
<div></div></div>

# Output

<div class="content"><div>输出n=3^m行，每行一个整数，表示每个人最终的得分。</div>
<div>其中第i行表示第i个人的得分f<sub>t,i</sub>。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">1 1 10009<br/>
10 100 1000<br/>
2 3<br/>
4</span></div>

# Sample Output

<div class="content"><span class="sampledata">4320<br/>
3240<br/>
2430</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

