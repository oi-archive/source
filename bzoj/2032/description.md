
# Description

<div class="content"><p>Lambda受任于某情报站，他的工作是获取敌人情报。一次他在破解密码系统时，得到了一个N位B进制数φ ，满足φ≡V (mod M)。他发现组成φ的数字很奇特。为了验证φ的特殊性，他将所有模M为V的N位B进制数，按照各数位构成的集合分类，并想知道每一类数各有多少个。</p></div>

# Input

<div class="content"><p>共一行，包含四个整数N, B, M, V。</p></div>

# Output

<div class="content"><p>共2B-1行，每行包含一个集合S和整数Ans[S]，以单个空格隔开。集合S用其所有元素的递减序列表示，如{2, 0, 1}表示为“210”。Ans[S]表示数位集合为S的满足以上性质的数的数目。集合按照字典序输出，每个集合只输出一次。由于Ans[S]可能很大，只需输出它除以10007的余数即可。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3 4 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 0<br/>
1 1<br/>
10 1<br/>
2 0<br/>
20 0<br/>
21 2<br/>
210 1<br/>
【样例说明】<br/>
在所有三位三进制数（1003~2223）中，模4为1的数为1003, 1113, 1223, 2103, 2213。数位集合为{1}的有1个（1113）<br/>
，数位集合为{1, 0}的有1个（1003），数位集合为{2, 1}的有2个（1223, 2213），数位集合为{2, 1, 0}的有1个（2103）。<br/>
</span></div>

# Hint

<div class="content"><p></p><p>N&lt; = 10 ^ 9 B&lt; = 10 M&lt; = 40</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=版权所有者： 赖陆航">版权所有者： 赖陆航</a></p></div>

