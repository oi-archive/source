
# Description

<div class="content"><p><span style="font-size: medium">有N个未知数x[1..n]和N个等式组成的同余方程组：<br/>
x[i]=k[i]*x[p[i]]+b[i] mod 10007<br/>
其中，k[i],b[i],x[i]∈[0,10007)∩Z<br/>
你要应付Q个事务，每个是两种情况之一：<br/>
一.询问当前x[a]的解<br/>
A a<br/>
无解输出-1<br/>
x[a]有多解输出-2<br/>
否则输出x[a]<br/>
二.修改一个等式<br/>
C a k[a] p[a] b[a]<br/>
<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">N<br/>
下面N行，每行三个整数k[i] p[i] b[i]<br/>
Q<br/>
下面Q行，每行一个事务，格式见题目描述<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">对每个询问，输出一行一个整数。<br/>
对100%的数据，1≤N≤30000，0≤Q≤100000，时限2秒，其中询问事务约占总数的80%<br/>
<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
2 2 1<br/>
2 3 2<br/>
2 4 3<br/>
2 5 4<br/>
2 3 5<br/>
5<br/>
A 1<br/>
A 2<br/>
C 5 3 1 1<br/>
A 4<br/>
A 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4276<br/>
7141<br/>
4256<br/>
2126<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 范浩强">By 范浩强</a></p></div>

