
# Description

<div class="content"><div>有n个人来参加比赛，要求进行恰好m轮，要你规划比赛方式。</div>
<div>允许出现m轮后有多人胜利的情况，即我们并不需要决出冠军。但是</div>
<div>我们不允许m轮里出现不战而胜的情况。</div>
<div>一轮比赛可以这么理解：假设当前还剩n个人，我们把n个人分成若</div>
<div>干份，但不允许某一份只有一个人（因为不能不战而胜），然后每一份的人</div>
<div>就会进行比赛，最后只会留下一个人晋级。</div>
<div>那么给定n,m，要你求合法的比赛过程的方案数，故与晋级的人无关</div>
<div>至于比赛流程有关。</div>
<div>由于你最近学了原根，对质数有与原根这一性质感兴趣，你想知道答</div>
<div>案对998244353(7*17*2^23+1)取模的结果，这个模数是一个质数。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>两个数n,k，如题意。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><p>一个数表示答案。</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">样例输入 1<br/>
6<br/>
2<br/>
输入样例 2<br/>
8<br/>
3</span></div>

# Sample Output

<div class="content"><span class="sampledata">输出样例 1<br/>
4<br/>
输出样例 2<br/>
1<br/>
</span></div>

# Hint

<div class="content"><p></p><div>第一个点：称6个人分别是A,B,C,D,E,F。A,B,C,D打一场，EF</div><br/>
<div>打一场，取胜的人打一场；ABC打一场，DEF打一场，取胜的人打一</div><br/>
<div>场；AB打一场，CD打一场，EF打一场，然后胜者打一场；AB打一场，</div><br/>
<div>CDEF打一场，然后打一场。</div><br/>
<div>第二个点：由于8=23，显然只可能是AB打一场，CD打一场，EF</div><br/>
<div>打一场，GH打一场；然后胜者看做ABCD，AB打一场，CD打一场；</div><br/>
<div>然后胜者打一场。</div><br/>
<div><br/>
<div>对于100%的数据，保证n&lt;=1015</div><br/>
<div>保证m&lt;=6</div><br/>
</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

