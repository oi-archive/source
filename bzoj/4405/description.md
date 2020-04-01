
# Description

<div class="content"><div>小N最近在研究NP完全问题，小O看小N研究得热火朝天，便给他出了一道这样的题目：</div>
<div>有n个球，用整数1到n编号。还有m个筐子，用整数1到m编号。</div>
<div>每个筐子最多能装3个球。</div>
<div>每个球只能放进特定的筐子中。具体有e个条件，第i个条件用两个整数vi和ui描述，表示编号为vi的球可以放进编号为ui的筐子中。</div>
<div>每个球都必须放进一个筐子中。如果一个筐子内有不超过1个球，那么我们称这样的筐子为半空的。</div>
<div>求半空的筐子最多有多少个，以及在最优方案中，每个球分别放在哪个筐子中。</div>
<div>小N看到题目后瞬间没了思路，站在旁边看热闹的小I嘿嘿一笑：“水题！”</div>
<div>然后三言两语道出了一个多项式算法。</div>
<div>小N瞬间就惊呆了，三秒钟后他回过神来一拍桌子：</div>
<div>“不对！这个问题显然是NP完全问题，你算法肯定有错！”</div>
<div>小I浅笑：“所以，等我领图灵奖吧!”</div>
<div>小O只会出题不会做题，所以找到了你——请你对这个问题进行探究，并写一个程序解决此题。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含1个正整数T，表示有T组数据。</div>
<div>对于每组数据，第一行包含3个正整数n,m,e，表示球的个数，筐子的个数和条件的个数。</div>
<div>接下来e行,每行包含2个整数vi,ui，表示编号为vi的球可以放进编号为ui的筐子。</div></div>

# Output

<div class="content"><p> 对于每组数据，先输出一行，包含一个整数，表示半空的筐子最多有多少个。</p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
4 3 6<br/>
1 1<br/>
2 1<br/>
2 2<br/>
3 2<br/>
3 3<br/>
4 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p><p> 对于所有数据，T≤5，1≤n≤3m。保证 1≤vi≤n,1≤ui≤m，且不会出现重复的条件。</p><br/>
<div>保证至少有一种合法方案,使得每个球都放进了筐子,且每个筐子内球的个数不超过 3。</div><br/>
<div>M&lt;=100</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

