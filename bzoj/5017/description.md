
# Description

<div class="content"><div>在一条直线上有 N 个炸弹，每个炸弹的坐标是 Xi，爆炸半径是 Ri，当一个炸弹爆炸时，如果另一个炸弹所在位置 Xj 满足： </div>
<div>Xi−Ri≤Xj≤Xi+Ri,那么，该炸弹也会被引爆。 </div>
<div>现在，请你帮忙计算一下，先把第 i 个炸弹引爆，将引爆多少个炸弹呢？ </div>
<p></p></div>

# Input

<div class="content"><div>第一行，一个数字 N，表示炸弹个数。 </div>
<div>第 2∼N+1行，每行 2 个数字，表示 Xi，Ri，保证 Xi 严格递增。 </div>
<div>N≤500000</div>
<div>−10^18≤Xi≤10^18</div>
<div>0≤Ri≤2×10^18</div>
<p></p></div>

# Output

<div class="content"><div>一个数字，表示Sigma(i*炸弹i能引爆的炸弹个数),1&lt;=i&lt;=N mod10^9+7。 </div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 1<br/>
5 1<br/>
6 5<br/>
15 15</span></div>

# Sample Output

<div class="content"><span class="sampledata">32<br/>
<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

