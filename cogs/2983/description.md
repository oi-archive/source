# 题目描述


<span style="font-family:宋体;font-size:10.5000pt;"><span></span></span><span class="15" style="font-family:宋体;font-weight:normal;"></span> 
<h3>
【题目描述】
</h3>
<p class="MsoNormal">
<span style="font-family:宋体;font-size:10.5000pt;"> </span> 
</p>
<p>
CCCTATKKK在徐大师帮助下，得到了对聂病毒。为了防止TAT传播病毒，NTZ对TAT使用了他的祖传能力——传送，想把TAT传送到自家马桶里杀死。但由于HF将要上映，NTZ过于睾兴，导致施法时用力过猛，错误将TAT传送到了无限剑制空间。虽然TAT保住一命，但是，为了逃出，TAT就必须找到对界宝具。
</p>
<p>
-----------------------------------------------------分鸽线--------------------------------------------------------
</p>
<p>
这个空间里有n个剑制点（0~n-1），在它们之间有m个连接（无向），每个连接都有一个通过时间，在剑制点中有k个点存在光芒。已知你被传送到了0节点，想要逃离该空间，必须至少点亮一个剑制点上的光芒。以获得对界宝具，为了防止TAT逃出，当TAT处于某个剑制点时，NTZ会把不超过
</p>
<p>
d 个以这个点为一端的连接断开。断开连接是随机的，TAT多次处于同一个剑制点时，
</p>
<p>
断开的连接可能会有所不同。TAT也想看HF，请你告诉他，在最坏情况下，逃出的最短用时为多少，好让他知道他能不能来得及。
</p>
<p>
<br/>
</p>
<span style="font-family:宋体;font-size:10.5000pt;"><span></span></span> 
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p class="MsoNormal">
<span style="font-family:&#39;Times New Roman&#39;;font-size:10.5000pt;"><span>第一行为4个正整数n,m,k,d 接下来m行，每行三个正整数u,v,dis，描述一个连接，dis表示通过时间，最后一行有k个整数，为k个光芒点。</span></span><span style="font-family:宋体;font-size:10.5000pt;"><span></span></span><span style="font-family:宋体;font-size:10.5000pt;"></span> 
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
一行一个整数，表示最坏情况下逃出该空间的最短用时。如果最坏情况下 逃不出该空间，输出-1
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<p>
<br/>
</p>
<p>
3 4 1 1
</p>
<p>
0 1 1
</p>
<p>
0 1 2
</p>
<p>
1 2 1
</p>
<p>
1 2 2
</p>
<p>
1
</p>
<p>
<br/>
</p>
<h3>
【样例输出】
</h3>
<p>
2
</p>
<h3>
【提示】
</h3>
<h3>
对于50%的数据，满足m=n-1，且剑制点互相之间至少能够间接连接。
</h3>
<h3>
对于100%的数据，满足k&lt;=n&lt;=1000,m&lt;=50000 ，d&lt;=6,且连接的通过用时均为正整数。
</h3>
<h3>
保证最短用时不超过10^4<br/>
</h3>
