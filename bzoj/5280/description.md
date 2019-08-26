
# Description

<div class="content"><div>
<div>Farmer John的N头奶牛（1≤N≤105），仍然编号为1…N，正好闲得发慌。因此，她们发展了一个与Farmer John每</div>
<div>天早上为她们挤牛奶的时候的排队顺序相关的复杂的社会阶层。经过若干周的研究，Farmer John对他的奶牛的社</div>
<div>会结构总计进行了M次观察（1≤M≤50,000）。每个观察结果都是他的某些奶牛的一个有序序列，表示这些奶牛应</div>
<div>该以与她们在序列中出现的顺序相同的顺序进行挤奶。比方说，如果Farmer John的一次观察结果是序列2、5、1，</div>
<div>Farmer John应该在给奶牛5挤奶之前的某个时刻给奶牛2挤奶，在给奶牛1挤奶之前的某个时刻给奶牛5挤奶。Farme</div>
<div>r John的观察结果是按优先级排列的，所以他的目标是最大化X的值，使得他的挤奶顺序能够符合前X个观察结果描</div>
<div>述的状态。当多种挤奶顺序都能符合前X个状态时，Farmer John相信一个长期以来的传统——编号较小的奶牛的地</div>
<div>位高于编号较大的奶牛，所以他会最先给编号最小的奶牛挤奶。更加正式地说，如果有多个挤奶顺序符合这些状态</div>
<div>，Farmer John会采用字典序最小的那一个。挤奶顺序x的字典序比挤奶顺序y要小，如果对于某个j，xi=yi对所有i</div>
<div>&lt;j成立，并且xj&lt;yj（也就是说，这两个挤奶顺序到某个位置之前都是完全相同的，在这个位置上x比y要小）。请</div>
<div>帮助Farmer John求出为奶牛挤奶的最佳顺序。</div>
<div></div>
</div>
<div></div></div>

# Input

<div class="content"><div>
<div>第一行包含N和M。</div>
<div>接下来的M行，每行描述了一个观察结果。</div>
<div>第i+1行描述了观察结果i，第一个数是观察结果中的奶牛数量mi，后面是一列mi个整数，给出这次观察中奶牛的顺序。</div>
<div>所有mi的和至多为200,000</div>
<div></div>
</div>
<div></div></div>

# Output

<div class="content"><div>
<div>输出N个空格分隔的整数，给出一个1…N的排列，为Farmer John给他的奶牛们挤奶应该采用的的顺序。</div>
<div></div>
</div>
<div>
<div></div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
3 1 2 3<br/>
2 4 2<br/>
3 3 4 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 4 2 3<br/>
<br/>
这里，Farmer John有四头奶牛，他的挤奶顺序应该是奶牛1在奶牛2之前、奶牛2在奶牛3之前（第一个观察结果）<br/>
，奶牛4在奶牛2之前（第二个观察结果），奶牛3在奶牛4之前、奶牛4在奶牛1之前（第三个观察结果）。前两个观<br/>
察结果可以同时被满足，但是Farmer John不能同时满足所有的规则，因为这样的话会要求奶牛1在奶牛3之前，同<br/>
时奶牛3在奶牛1之前。这意味着总共有两种可能的挤奶顺序：1 4 2 3和4 1 2 3，第一种是字典序较小的。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

