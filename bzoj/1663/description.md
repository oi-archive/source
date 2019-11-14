
# Description

<div class="content"><p><span style="font-size: medium">Every year, Farmer John loves to attend the county fair. The fair has N booths (1 &lt;= N &lt;= 400), and each booth i is planning to give away a fabulous prize at a particular time P(i) (0 &lt;= P(i) &lt;= 1,000,000,000) during the day. Farmer John has heard about this and would like to collect as many fabulous prizes as possible to share with the cows. He would like to show up at a maximum possible number of booths at the exact times the prizes are going to be awarded. Farmer John investigated and has determined the time T(i,j) (always in range 1..1,000,000) that it takes him to walk from booth i to booth j. The county fair&#39;s unusual layout means that perhaps FJ could travel from booth i to booth j by a faster route if he were to visit intermediate booths along the way. Being a poor map reader, Farmer John never considers taking such routes -- he will only walk from booth i to booth j in the event that he can actually collect a fabulous prize at booth j, and he never visits intermediate booths along the way. Furthermore, T(i,j) might not have the same value as T(j,i) owing to FJ&#39;s slow walking up hills. Farmer John starts at booth #1 at time 0. Help him collect as many fabulous prizes as possible. </span></p>
<p></p>
<div>每一年，约翰都会带着他的奶牛们去赶集．集会中一共有N(1≤N≤400)个商店，第i个商店会在特定的时间Pi(0≤Pi≤109)对当时在店里的顾客送出一份精美的礼物．约翰当然得到了这个消息，于是他希望能拿到尽量多的礼物送给他的奶牛们．也就是说，他想尽可能多地在某商店发放礼物的时候，正好呆在店里．</div>
<div>    经过一定的调查，约翰弄清楚了从i号商店走到J号商店所需要的时间Ti，J(1≤Ti，J≤1000000)．虽然乡间小路奇特的布局使得从i号商店走到j号商店的最短路不一定是直接连接这两个商店的那条，但约翰并不会选择那些会经过其他商店的路线，只是直接走到目标商店等待礼物的送出．此外，Ti,j并不一定等于Tj，i，由于约翰爬山的速度总是很慢．</div>
<div>    约翰在时间0时于1号商店开始他的旅途．请你帮他设计一条路线来获得尽可能多的礼物．</div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer, N. </span></p>
<p><span style="font-size: medium">* Lines 2..1+N: Line i+1 contains a single integer, P(i). * Lines 2+N..1+N+N^2: These N^2 lines each contain a single integer T(i,j) for each pair (i,j) of booths. The first N of these lines respectively contain T(1,1), T(1,2), ..., T(1,N). The next N lines contain T(2,1), T(2,2), ..., T(2,N), and so on. Each T(i,j) value is in the range 1...1,000,000 except for the diagonals T(1,1), T(2,2), ..., T(N,N), which have the value zero.</span></p>
<div><span style="font-size: medium">  第1行输入一个正整数N．接下来N行每行一个整数Pi．</span></div>
<div><span style="font-size: medium">    接下来N^2行，输入乃，J．先输入T1,1 T1,2 T1,3…T1,N再输入T2,1 T2,2…T2,N依次类推．</span></div>
<p><span style="font-size: medium">   </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer, containing the maximum number of prizes Farmer John can acquire. </span></p>
<p><span style="font-size: medium"> 输出一个整数，即约翰最多能拿到的礼物的个数</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 //有四个收藏品可以去收集,下面四行给出这四个东西下落的时间<br/>
13 //第一个东西，在第一个地点第13分钟掉下来<br/>
9 //第二个东西，在第二个地点第9分钟掉下来<br/>
19 //第三个东西，在第三个地点第19分钟掉下来<br/>
3 //这是第四个东西.<br/>
0 //这下面有4*4行，代表每个点到其它点的要花的时间，自己到自己的时间为0。<br/>
10<br/>
20<br/>
3<br/>
4<br/>
0<br/>
11<br/>
2<br/>
1<br/>
15<br/>
0<br/>
12<br/>
5<br/>
5<br/>
13<br/>
0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
<br/>
Farmer John first walks to booth #4 and arrives at time 3, just in<br/>
time to receive the fabulous prize there. He them walks to booth<br/>
#2 (always walking directly, never using intermediate booths!) and<br/>
arrives at time 8, so after waiting 1 unit of time he receives the<br/>
fabulous prize there. Finally, he walks back to booth #1, arrives<br/>
at time 13, and collects his third fabulous prize.<br/>
</span></div>

# Hint

<div class="content"><p></p><div><span style="font-size: medium">    一共有4家商店．1号商店会在时间13送出一份礼物，2号商店送出礼物的时间为9，3号商店是时间19，4号商店是时间3．    约翰先在时间3走到4号商店，正好拿到送出的礼物．然后他再直接走到2号商店（不经过任何中转商店），在时间8到那儿，然后等待1单位时间，在时间9拿到商店送出的礼物后马上出发去1号商店，又正好能在时间13到达并拿到第3份礼物．</span></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

