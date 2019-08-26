
# Description

<div class="content"><p><span style="font-size: medium">Description<br/>
给出n个整数X_1,X_2,...X_n，再给出两个正整数a、b，可以进行下面四种操作：<br/>
1. 选择正整数l,r (1&lt;=l&lt;=r&lt;=n)，将X_l,X_{l+1},...,X_r都加上a。<br/>
2. 选择正整数l,r (1&lt;=l&lt;=r&lt;=n)，将X_l,X_{l+1},...,X_r都减去a。<br/>
3. 选择正整数l,r (1&lt;=l&lt;=r&lt;=n)，将X_l,X_{l+1},...,X_r都加上b。<br/>
4. 选择正整数l,r (1&lt;=l&lt;=r&lt;=n)，将X_l,X_{l+1},...,X_r都减去b。<br/>
求最少的操作次数将{X_i}全部变成0</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium"><br/>
第一行三个正整数n,a,b (n&lt;=100,000, a,b&lt;=10^9)。<br/>
第二行n个整数，依次表示X_1,X_2,...X_n (|X_i|&lt;=10^9)。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">一个正整数，表示最少的操作次数。如果不存在方案，输出-1。</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 2 3<br/>
1 2 1 1 -1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">进行下面五次操作将{X_i}全部变成0：<br/><br/>
1. 将X_1,X_2都加上2，变成3 4 1 1 -1。<br/><br/>
2. 将X_1,X_2都减去3，变成0 1 1 1 -1。<br/><br/>
3. 将X_2,X_3,X_4,X_5都加上2，变成0 3 3 3 1。<br/><br/>
4. 将x_5加上2，变成0 3 3 3 3。<br/><br/>
5. 将x_2,x_3,x_4,x_5都减去3，变成0 0 0 0 0。<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢oimaster">鸣谢oimaster</a></p></div>

