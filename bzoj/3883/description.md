
# Description

<div class="content"><p> <img width="0" height="0" src="/source/bzoj/3883/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwMi8xMTEuanBn.jpg" alt=""/><img width="1176" height="782" alt="" src="/source/bzoj/3883/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwMy8xMTEuanBn.jpg"/></p></div>

# Input

<div class="content"><p><img width="412" height="92" alt="" src="/source/bzoj/3883/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwMy8yMjIuUE5H.PNG"/></p></div>

# Output

<div class="content"><p> <img width="0" height="0" src="/source/bzoj/3883/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwMi8zMzMuUE5H.PNG" alt=""/><img width="1164" height="85" alt="" src="/source/bzoj/3883/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwMy8zMzMuUE5H.PNG"/></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2 4 1<br/>
0 1 2 2 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">001<br/>
010<br/>
1110</span></div>

# Hint

<div class="content"><p></p><p>样例输入等价于如下代码<br/><br/>
y[] = 0000 input x[0..n-1] y[0..n-1] = x[0..n-1] y[0] = (not (y[1] and y[2])) xor y[2] xor y[2] output y[0]<br/><br/>
其中 x[0..n-1] 表示 01 串 x 的第 0 位到第 n−1 位。<br/><br/>
在这段代码中，每一种输入对应的输出如下：<br/><br/>
input     000     001     010     011     100     101     110     111<br/><br/>
output     1     1     1     0     1     1     1     0<br/><br/>
样例输出是一种破解方案，等价于如下代码：<br/><br/>
input x[0..n-1] z[0] = x[2] z[1] = x[1] output h(z[])<br/><br/>
h 函数的输入和输出有如下对应关系：<br/><br/>
z[]     00     01     10     11<br/><br/>
h(z[])     1     1     1     0<br/><br/>
可以发现，对于每一种输入，破解版算法和混淆版算法的输出是相同的。<br/><br/>
对于所有的数据，1≤n≤64，1≤L≤256，1≤Q≤1024，0≤p≤0.01，0≤u,v,s,d,e&lt;L（注意，输入中并没有把 p 的值给你）。<br/><br/>
<br/><br/>
提示<br/><br/>
使用位运算一次在多个输入上求出函数值可以极大的加速你的程序。<br/><br/>
数据范围<br/><br/>
1&lt;=N&lt;=64,1&lt;=L&lt;=256,1&lt;=Q&lt;=1024,0&lt;=P&lt;=0.01,0&lt;=U,V,S,D,E&lt;=L</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

