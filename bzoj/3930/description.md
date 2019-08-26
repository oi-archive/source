
# Description

<div class="content"><p> 我们知道，从区间[L,H]（L和H为整数）中选取N个整数，总共有(H-L+1)^N种方案。小z很好奇这样选出的数的最大公约数的规律，他决定对每种方案选出的N个整数都求一次最大公约数，以便进一步研究。然而他很快发现工作量太大了，于是向你寻求帮助。你的任务很简单，小z会告诉你一个整数K，你需要回答他最大公约数刚好为K的选取方案有多少个。由于方案数较大，你只需要输出其除以1000000007的余数即可。</p>
<div></div></div>

# Input

<div class="content"><p>输入一行，包含4个空格分开的正整数，依次为N，K，L和H。</p>
<div></div></div>

# Output

<div class="content"><p>输出一个整数，为所求方案数。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">2 2 2 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p><p> 样例解释</p><br/>
<div>所有可能的选择方案：(2, 2), (2, 3), (2, 4), (3, 2), (3, 3), (3, 4), (4, 2), (4, 3), (4, 4)</div><br/>
<div>其中最大公约数等于2的只有3组：(2, 2), (2, 4), (4, 2)</div><br/>
<div>对于100%的数据，1≤N,K≤10^9，1≤L≤H≤10^9，H-L≤10^5</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

