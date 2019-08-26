
# Description

<div class="content"><div>小N最近在研究NP完全问题，小O看小N研究得热火朝天，便给他出了一道这样的题目：</div>
<div>有 n 个球，用整数 1 到 n 编号。还有 m 个筐子，用整数1到m编号。</div>
<div>每个球只能放进特定的两个筐子之一，第 i 个球可以放进的筐子记为 Ai 和 Bi 。</div>
<div>每个球都必须放进一个筐子中。</div>
<div>如果一个筐子内有奇数个球，那么我们称这样的筐子为半空的。</div>
<div>求半空的筐子最少有多少个。</div>
<div>小N看到题目后瞬间没了思路，站在旁边看热闹的小I嘿嘿一笑：&#34;水题！&#34;</div>
<div>然后三言两语道出了一个多项式算法。</div>
<div>小N瞬间就惊呆了，三秒钟后他回过神来一拍桌子：</div>
<div>&#34;不对！这个问题显然是NP完全问题，你算法肯定有错！&#34;</div>
<div>小I浅笑：&#34;所以，等我领图灵奖吧!&#34;</div>
<div>小O只会出题不会做题，所以找到了你--请你对这个问题进行探究，并写一个程序解决此题。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数 n，m</div>
<div>接下来 n 行，第 i + 1 行有两个整数 Ai ， Bi ，表示第 i 个球可以放的两个筐子。保证 Ai 不等于 Bi</div>
<div>1 &lt;= n，m &lt;= 2 * 10^5，1 &lt;= Ai，Bi &lt;= m</div>
<p></p></div>

# Output

<div class="content"><div>第一行一个整数表示半空的筐子的最小值。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
1 2<br/>
2 3<br/>
1 3<br/>
1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
1，3 号球都放在 1 号筐子，2，4 号球都放在 2 号筐子。</span></div>

# Hint

<div class="content"><p></p><p>各位不妨考虑下，如果要求输出方案应该怎么写.</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

