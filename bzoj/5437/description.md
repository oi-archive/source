
# Description

<div class="content"><div>给定一有向图，边长均为1，求长度小于k的环的个数mod m。</div>
<div>保证有向图中无自环(即g[i,i]=&#39;N&#39;)。</div>
<div>什么样的环属于不同的解，详见样例解释。</div>
<p></p></div>

# Input

<div class="content"><div>第一行n表示节点个数</div>
<div>接下来n行长度为n的字符串,g[i,j]=&#39;Y&#39;表示i到j有一条边，g[i,j]=&#39;N&#39;反之。</div>
<div>最后一行两个整数k，m。</div>
<div> n&lt;=100,  k&lt;=10^6,  m&lt;=10^9</div>
<p></p></div>

# Output

<div class="content"><div>一个整数表示答案.</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
NYNY<br/>
NNYN<br/>
YNNN<br/>
YNNN<br/>
6 100  </span></div>

# Sample Output

<div class="content"><span class="sampledata">12  <br/>
【样例解释】<br/>
12个解分别为：(0,3) ; (3,0) ; (0,1,2) ; (1,2,0) ; (2,0,1);(0,3,0,3) ; <br/>
(3,0,3,0) ; (0,1,2,0,3) ; (0,3,0,1,2) ; (1,2,0,3,0) ; (2,0,3,0,1) ; (3,0,1,2,0)。 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

