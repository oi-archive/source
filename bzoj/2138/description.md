
# Description

<div class="content"><div>话说Nan在海边等人，预计还要等上M分钟。为了打发时间，他玩起了石子。Nan搬来了N堆石子，编号为1到N，每堆</div>
<div>包含Ai颗石子。每1分钟，Nan会在编号在[Li,Ri]之间的石堆中挑出任意Ki颗扔向大海（好疼的玩法），如果[Li,R</div>
<div>i]剩下石子不够Ki颗，则取尽量地多。为了保留扔石子的新鲜感，Nan保证任意两个区间[Li,Ri]和[Lj,Rj]，不会</div>
<div>存在Li&lt;=Lj&amp;Rj&lt;=Ri的情况，即任意两段区间不存在包含关系。可是，如果选择不当，可能无法扔出最多的石子，</div>
<div>这时NN就会不高兴了。所以他希望制定一个计划，他告诉你他m分钟打算扔的区间[Li,Ri]以及Ki。现在他想你告诉</div>
<div>他，在满足前i-1分钟都取到你回答的颗数的情况下，第i分钟最多能取多少个石子。</div></div>

# Input

<div class="content"><div>第一行正整数N，表示石子的堆数；</div>
<div>第二行正整数x,y,z,P，(1&lt;=x,y,z&lt;=N;P&lt;=500) </div>
<div>有等式A[i]=[(i-x)^2+(i-y)^2+(i-z)^2] mod P；</div>
<div>第三行正整数M，表示有M分钟；</div>
<div>第四行正整数K[1],K[2],x,y,z,P，(x,y,z&lt;=1000;P&lt;=10000) </div>
<div>有等式K[i]=(x*K[i-1]+y*K[i-2]+z)mod P。</div>
<div>接下来M行，每行两个正整数L[i],R[i]。</div>
<div>N&lt;=40000   M&lt;=N   1&lt;=L[i]&lt;=R[i]&lt;=N   A[i]&lt;=500</div></div>

# Output

<div class="content"><p>有M行，第i行表示第i分钟最多能取多少石子。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
3 2 4 7<br/>
3<br/>
2 5 2 6 4 9<br/>
2 4<br/>
1 2<br/>
3 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
5<br/>
5<br/>
【样例说明】<br/>
石子每堆个数分别为0,5,2,5,0。<br/>
第1分钟，从第2到第4堆中选2个；<br/>
第2分钟，从第1到第2堆中选5个；<br/>
第3分钟，从第3到第5堆中选8个，但最多只能选5个。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

