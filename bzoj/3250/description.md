
# Description

<div class="content"><div>
<div>题目简述：给定一有向图，边长均为1，求总长小于k的环的个数mod m，</div>
<div>什么样的环属于不同详见样例。保证无自环(即g[i,i]=&#39;N&#39;)</div>
<div>题目详述：minecraft中有很多可爱的生物，比如creeper（更知名的名字：JJ怪）和各路僵尸。在你没有做好足够</div>
<div>的准备之前，遇见它们的时候只能逃跑，而且你不希望某些怪物在你辛苦建造的房子旁爆炸。所以你决定对附近的</div>
<div>地形进行考察，并设计好一些迂回线路，以同时应对多个怪物。</div>
</div></div>

# Input

<div class="content"><div>第一行n表示节点个数</div>
<div>接下来n行长度为n的字符串,g[i,j]=&#39;Y&#39;表示i到j有一条边，g[i,j]=&#39;N&#39;反之。</div>
<div>最后一行两个整数k，m。</div>
<div>n&lt;=100, k&lt;=10^6, m&lt;=10^9</div></div>

# Output

<div class="content"><p>一个整数表示答案</p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
NYNY<br/>
NNYN<br/>
YNNN<br/>
YNNN<br/>
6 100 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">12 <br/>
//【样例解释】<br/>
12个解分别为：(0,3) ; (3,0) ; (0,1,2) ; (1,2,0) ; <br/>
(2,0,1);(0,3,0,3) ; (3,0,3,0) ; (0,1,2,0,3) ; <br/>
(0,3,0,1,2) ; (1,2,0,3,0) ; (2,0,3,0,1) ; (3,0,1,2,0)。 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

