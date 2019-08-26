
# Description

<div class="content"><p>对于两个长度为n的整数数组A=(a[1],a[2],…,a[n]),B=(b[1],b[2],…,b[n])，定义它们的距离为d(A,B)=abs(a[1]-b[1])+abs(a[2]-b[2])+…+abs(a[n]-b[n])，其中abs表示取绝对值。<br/>
给定k个整数数组A_1,A_2,…,A_k，定义它们的中心是这样一个整数组成的数组B，使得max{d(A_i,B):i=1,2,…,k}尽可能小</p></div>

# Input

<div class="content"><p>第一行两个整数n,k(2&lt;=n&lt;=100000,2&lt;=k&lt;=5)。n表示数组长度，k表示数组个数。<br/>
接下来k行，每行为一个长度为n的数组。数组内整数的绝对值均不超过10^9。</p></div>

# Output

<div class="content"><p>输出一行空格隔开的n个整数，为所求的中心。答案可能有多个，你只需任意输出其中一个。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
1 -1 2 -1 2<br/>
1 2 2 1 2<br/>
2 2 -1 1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 2 2 1 2 <br/>
<br/>
样例解释：<br/>
中心到各个数组的距离分别为5,0,5，最大值是5。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Jcvb">鸣谢Jcvb</a></p></div>

