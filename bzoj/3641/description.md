
# Description

<div class="content"><p><span style="font-size: medium">saffah所在的国家一共有N个城市，通过N条双向道路连接，使得城市之间两两可以到达。第i条道路连接了A[i]与B[i]，其长度为L[i] km。<br/>
这些道路分为M个等级。第i条道路的等级为X[i]。在第j级道路上行驶，你的限速是V[j] km/h，并且每行驶1小时会收取W[j]元的费用。根据道路分级的意义，V[j]与W[j]都随着j单调变化，即对于1 ≤ j &lt; M，满足V[j] &gt; V[j+1], W[j] &gt; W[j+1]。<br/>
现在有Q辆货车需要运送货物。第k辆货车要从S[k]前往T[k]，并且其最大速度为U[k] km/h。你需要对每辆货车求出其最小运送花费。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行三个整数N, M, Q。<br/>
接下来N行，每行四个整数A[i], B[i], L[i], X[i]，描述了一条道路。<br/>
接下来M行，每行两个整数V[j], W[j]，描述了一个道路等级的限速和费用。<br/>
接下来Q行，每行三个整数S[k], T[k], U[k]，描述了一辆货车。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">输出Q行，即每辆货车的最小运送花费。<br/>
你可以输出任意多位的实数，只要与标准答案的相对或绝对误差不超过0.0001就算正确。</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 2 2<br/>
1 2 50 1<br/>
2 3 50 1<br/>
1 3 50 2<br/>
3 4 50 1<br/>
100 20<br/>
10 10<br/>
1 4 100<br/>
1 4 10<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">30<br/>
150<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">对于所有的数据，1 ≤ N,M,Q ≤ 100,000, 1 ≤ A[i],B[i],S[k],T[k] ≤ N, 1 ≤ X[i] ≤ M, 1 ≤ L[i],V[j],W[j],U[k] ≤ 500,000。<br/><br/>
样例解释：<br/><br/>
第一辆货车应该沿1→2→3→4行驶，共在1级道路上行驶1.5小时，收费30元。<br/><br/>
第二辆货车应该沿1→3→4行驶，在2级道路上行驶5小时，在1级道路上行驶5小时，收费150元。<br/><br/>
</span></p><br/>
<p><span style="color: #ff0000"><span style="font-size: medium">请不要提交，未加SPJ。</span></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By saffah">By saffah</a></p></div>

