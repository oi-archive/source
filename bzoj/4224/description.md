
# Description

<div class="content"><div>给你一个长度为n的01串，以及一个指针，初始时指针在第i0个字符上。每回合随机一个0到n-1中的数j，如果指针</div>
<div>之前在i上，就花费abs(i-j)的时间把指针从i移动到j上，并且把01串的第j位取反。不停这样随机，直到01串变成</div>
<div>全0或者全1为止，问到终止前期望花费的时间是多少？</div></div>

# Input

<div class="content"><div>第一行两个整数，n，t，表示串长和数据组数，每组数据的串长是相等的</div>
<div>接下来t行，每行一个01串和一个整数，s，i0，表示初始时的串和初始位置，s的长度为n</div>
<div>n&lt;=30 t&lt;=100000 0&lt;=i0&lt;n</div>
<p></p></div>

# Output

<div class="content"><div>t行，每行一个实数表示答案。你的答案被认为是正确的当且仅当，你与标准答案的相对误差小于1e-7</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
1000 0<br/>
0010 1<br/>
0011 2<br/>
1010 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">8.9375<br/>
8.5625<br/>
9.75<br/>
10.25</span></div>

# Hint

<div class="content"><p></p><div></div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

