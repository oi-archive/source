
# Description

<div class="content"><div>pupil 发现对于一个十进制数，无论怎么将其的数字重新排列，均不影响其是不是333 的倍数。他想研究对于二进</div>
<div>制，是否也有类似的性质。于是他生成了一个长为n 的二进制串，希望你对于这个二进制串的一个子区间，能求出</div>
<div>其有多少位置不同的连续子串，满足在重新排列后（可包含前导0 ）是一个3 的倍数。两个位置不同的子区间指开</div>
<div>始位置不同或结束位置不同。由于他想尝试尽量多的情况，他有时会修改串中的一个位置，并且会进行多次询问。</div></div>

# Input

<div class="content"><div>输入第一行包含一个正整数n ，表示二进制数的长度。</div>
<div>之后一行n 个空格隔开的整数，保证均是0 或1 ，表示该二进制串。</div>
<div>之后一行一个整数m ，表示询问和修改的总次数。</div>
<div>之后m 行每行为1 i，表示pupil 修改了串的第i个位置（0 变成1 或1 变成0 ），或2 l r</div>
<div>表示pupil 询问的子区间是[l,r] 。</div>
<div>串的下标从1 开始。</div>
<div>1≤n,m≤100000</div></div>

# Output

<div class="content"><div>对于每次询问，输出一行一个整数表示对应该询问的结果。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 0 1 0<br/>
3<br/>
2 1 3<br/>
1 3<br/>
2 3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
3<br/>
说明<br/>
样例解释<br/>
对于第一个询问，区间[2,2] 只有数字0 ，是3 的倍数，区间[1,3] <br/>
可以重排成011(2)=3(10)，是3 的倍数，其他区间均不能重排成3 的倍数。<br/>
对于第二个询问，全部三个区间均能重排成3 的倍数（注意00 也是合法的）。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢佚名上传">鸣谢佚名上传</a></p></div>

