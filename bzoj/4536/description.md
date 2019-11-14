
# Description

<div class="content"><p>　　我有一个数列a[1],a[2],…,a[n]，每个a[i]是小于2^m的正整数。显然正整数的二进制表示下至少有一个1，<br/>
现在，我希望您能把每个数仅保留二进制下其中的某一位1，并最大化这个数列中所有数的异或和。例如，5的二进<br/>
制表示为101，那么5就只能变为4（保留从左往右第一个1，即变为100），或者1（保留另一个1，即变为001），11<br/>
的二进制表示为1011，那么它可以变为8（1000）、2（0010）、1（0001）中的某一个。</p></div>

# Input

<div class="content"><p>　　第一行一个正整数T，表示数据组数。对于每组数据：第一行一个正整数n。接下来一行n个正整数，表示a数组<br/>
1 ≤ T ≤ 5, 1 ≤ n ≤ 100, 1 ≤ m ≤ 60, 对所有i，有1 ≤ a[i] ≤ 2^m - 1</p></div>

# Output

<div class="content"><p>　　对于每组数据输出一行一个数，表示最大的异或和</p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
7<br/>
73 4 96 49 4 57 104 <br/>
7<br/>
1 72 104 20 72 104 20 <br/>
7<br/>
68 118 11 1 102 8 8 <br/>
7<br/>
69 32 3 32 64 72 65 <br/>
7<br/>
4 4 83 121 4 4 1 </span></div>

# Sample Output

<div class="content"><span class="sampledata">121<br/>
117<br/>
121<br/>
79<br/>
97</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By matthew99">By matthew99</a></p></div>

