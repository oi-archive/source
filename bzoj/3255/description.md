
# Description

<div class="content"><div>
<div>有一个序列，你可以在上面删除符合要求的连续段若干次。每次删除都会得到连续段长度对应的分数。需要符合的</div>
<div>要求为：</div>
<div>1、相邻两个元素相差为1</div>
<div>2、如果某个元素不在连续段的最左或最右，那么这个元素就不能同时小于相邻的左右两个元素。</div>
<div>“1、2、3、4、3” “1、2” “3、2” “3”都符合条件。</div>
<div>显然，删除掉连续段后，这个段的左边和右边并在一起成为相邻元素。</div>
<div>你的任务是对于给出的序列，计算出可能获得的最大总分。</div>
</div></div>

# Input

<div class="content"><div>
<div>第一行一个整数N，表示序列长度</div>
<div>第二行N个数，V1、V2.....VN，代表每个长度对应的分数。</div>
<div>第三行N个数，A1、A2.....AN，代表初始序列的每个元素。</div>
<div>1&lt;=N&lt;=150, -10000&lt;=Vi&lt;=10000,0&lt;=Ai&lt;=1000 000 000.相同的Ai不会超过7个</div>
</div>
<div></div></div>

# Output

<div class="content"><div>一个数，可以获得的最大总分</div></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
-100 5 6 10 0 0<br/>
3 1 2 3 4 10<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">11<br/>
//【样例说明】<br/>
3 1 2 34 10 ---&gt;3 4 10    V3=6<br/>
3 4 10 ---&gt; 10           V2=5<br/>
5+6=11</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

