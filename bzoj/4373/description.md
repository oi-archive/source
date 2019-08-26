
# Description

<div class="content"><p>算术天才⑨非常喜欢和等差数列玩耍。<br/>
有一天，他给了你一个长度为n的序列，其中第i个数为a[i]。<br/>
他想考考你，每次他会给出询问l,r,k，问区间[l,r]内的数从小到大排序后能否形成公差为k的等差数列。<br/>
当然，他还会不断修改其中的某一项。<br/>
为了不被他鄙视，你必须要快速并正确地回答完所有问题。<br/>
注意：只有一个数的数列也是等差数列。</p></div>

# Input

<div class="content"><p>第一行包含两个正整数n,m(1&lt;=n,m&lt;=300000)，分别表示序列的长度和操作的次数。<br/>
第二行包含n个整数，依次表示序列中的每个数a[i](0&lt;=a[i]&lt;=10^9)。<br/>
接下来m行，每行一开始为一个数op，<br/>
若op=1，则接下来两个整数x,y(1&lt;=x&lt;=n，0&lt;=y&lt;=10^9)，表示把a[x]修改为y。<br/>
若op=2，则接下来三个整数l,r,k(1&lt;=l&lt;=r&lt;=n，0&lt;=k&lt;=10^9)，表示一个询问。<br/>
在本题中，x,y,l,r,k都是经过加密的，都需要异或你之前输出的Yes的个数来进行解密。</p></div>

# Output

<div class="content"><p>输出若干行，对于每个询问，如果可以形成等差数列，那么输出Yes，否则输出No。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
1 3 2 5 6<br/>
2 1 5 1<br/>
1 5 4<br/>
2 1 5 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">No<br/>
Yes</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

