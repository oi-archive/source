
# Description

<div class="content"><div>有一个长度为m的，由1到9之间的数构成的未知数列a。</div>
<div>你现在有n个线索，每个线索都是用如下方式生成的：</div>
<div>（1）选择序列a的某一个位置p作为开始；</div>
<div>（2）选择某个方向（向左或向右）；</div>
<div>（3）从p出发往你选择的方向走，每遇到一个之前未出现的数就将它加到线索中。</div>
<div>现在你需要求出满足所有线索的长度最小的序列的长度。</div>
<p></p></div>

# Input

<div class="content"><div>输入文件的第一行为一个整数n，表示线索的数量。</div>
<div>接下来n行，每行有若干个以0结尾的整数，表示一条线索。保证一条线索中的数在[1,9]中且不会出现相同的数。</div>
<div>对于20%的数据，答案不超过10。</div>
<div>对于另外40%的数据，保证存在一个最优解，使得所有线索都可以通过向右遍历得到。</div>
<div>对于100%的数据，1≤n≤10。</div>
<p></p></div>

# Output

<div class="content"><div>如果无解请输出-1，否则输出可能的最小长度。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2 0<br/>
3 4 0<br/>
1 4 3 0<br/>
3 1 4 2 0<br/>
1 2 4 3 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">7</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

