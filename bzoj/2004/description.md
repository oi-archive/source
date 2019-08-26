
# Description

<div class="content"><div>小Z所在的城市有N个公交车站，排列在一条长(N-1)km的直线上，从左到右依次编号为1到N，相邻公交车站间的距</div>
<div>离均为1km。 作为公交车线路的规划者，小Z调查了市民的需求，决定按下述规则设计线路：</div>
<div>1.设共K辆公交车，则1到K号站作为始发站，N-K+1到N号台作为终点站。</div>
<div>2.每个车站必须被一辆且仅一辆公交车经过（始发站和</div>
<div>终点站也算被经过）。 </div>
<div>3.公交车只能从编号较小的站台驶往编号较大的站台。 </div>
<div>4.一辆公交车经过的相邻两个</div>
<div>站台间距离不得超过Pkm。 在最终设计线路之前，小Z想知道有多少种满足要求的方案。由于答案可能很大，你只</div>
<div>需求出答案对30031取模的结果。</div></div>

# Input

<div class="content"><div>仅一行包含三个正整数N K P，分别表示公交车站数，公交车数，相邻站台的距离限制。</div>
<div>N&lt;=10^9，1&lt;P&lt;=10，K&lt;N，1&lt;K&lt;=P</div></div>

# Output

<div class="content"><p>仅包含一个整数，表示满足要求的方案数对30031取模的结果。</p></div>

# Sample Input

<div class="content"><span class="sampledata">样例一：10 3 3				   <br/>
样例二：5 2 3				   <br/>
样例三：10 2 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
3<br/>
81</span></div>

# Hint

<div class="content"><p></p><div>【样例说明】</div><br/>
<div>样例一的可行方案如下： (1,4,7,10)，(2,5,8)，(3,6,9)</div><br/>
<div>样例二的可行方案如下： (1,3,5)，(2,4) (1,3,4)，(2,5) (1,4)，(2,3,5) </div><br/>
<div>P&lt;=10 , K &lt;=8</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

