
# Description

<div class="content"><div>可怜有一个长度为n的正整数序列Ai，其中相同的正整数代表着相同的颜色。</div>
<div>现在可怜觉得这个序列太长了，于是她决定选择一些颜色把这些颜色的所有位置都删去。</div>
<div>删除颜色i可以定义为把所有满足Aj=i的位置j都从序列中删去。</div>
<div>然而有些时候删去之后，整个序列变成了好几段，可怜不喜欢这样，于是她想要知道有多</div>
<div>少种删去颜色的方案使得最后剩下来的序列非空且连续。</div>
<div>例如颜色序列{1,2,3,4,5}，删除颜色3后序列变成了{1,2}和{4,5}两段，不满足条件。</div>
<div>而删除颜色1后序列变成了{2,3,4,5}，满足条件。</div>
<div>两个方案不同当且仅当至少存在一个颜色i只在其中一个方案中被删去。</div>
<div></div>
<div></div>
<div> 。</div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行输入一个整数T表示数据组数。</div>
<div>每组数据第一行输入一个整数n表示数列长度。</div>
<div>第二行输入n个整数描述颜色序列。</div>
<div>1 ≤ T, ∑ n ≤ 3 × 10^5, 1 ≤ Ai ≤ n</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据输出一个整数表示答案</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
5<br/>
1 3 2 4 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
//满足条件的删颜色方案有 {1}, {1, 3}, {1, 2, 3}, {1, 3, 4}, {2, 3, 4}, ∅</span></div>

# Hint

<div class="content"><p></p><p>为试题的完整性，下面给出Jxoi2017题面及前两题数据<a href="http://www.lydsy.com/JudgeOnline/upload/jxoi2017.rar">www.lydsy.com/JudgeOnline/upload/jxoi2017.rar</a></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

