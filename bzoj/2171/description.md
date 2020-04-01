
# Description

<div class="content"><p>一个序列的第1,3,5...项被称作奇数项，第2,4,6...项被称作偶数项。一个序列A[1..n]被称作ZigZag序列当且仅当以下两个条件中的一个（或两个）成立： 1）除了首项，所有的奇数项都比它的前项小且所有的偶数项都比它的前项大。 2）除了首项，所有的奇数项都比它的前项大且所有的偶数项都比它的前项小。一个序列A[1..n]被称作K凹凸序列当且仅当它的最长ZigZag子序列（不一定是连续子序列）的长度不超过K。现在有一个序列A[1..n]，每次可以花费1的代价使得A中的某一项增加或减少1。我们的目的是花费最少的代价让它成为K凹凸序列。</p></div>

# Input

<div class="content"><p>输入的第一行包含两个正整数，分别表示数列A[1..N]的长度N和K。接下来的N行每行一个自然整数，依次表示数列的项。前1个测试点满足：K=1，N≤20000 第2~8个测试点满足：K=2，N≤20000 第9~15个测试点满足：K=3，N≤20000 第16~20个测试点满足：K≤10，N≤1000 所有测试点满足：A[i]≤50000</p></div>

# Output

<div class="content"><p>输出一个整数，表示最小代价。</p></div>

# Sample Input

<div class="content"><span class="sampledata">9 3<br/>
1<br/>
2<br/>
3<br/>
6<br/>
9<br/>
8<br/>
7<br/>
4<br/>
5</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
【样例说明】<br/>
把最后一项减小1，得到序列<br/>
1 2 3 6 9 8 7 4 4<br/>
它的最长ZigZag子序列之一是<br/>
1 9 4<br/>
长度为3，符合要求</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=版权所有者：范浩强">版权所有者：范浩强</a></p></div>

