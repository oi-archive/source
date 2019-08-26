
# Description

<div class="content"><p>在一片土地上有N个城市，通过N-1条无向边互相连接，形成一棵树的结构，相邻两个城市的距离为1，其中第i个城市的价值为value[i]。<br/>
不幸的是，这片土地常常发生地震，并且随着时代的发展，城市的价值也往往会发生变动。<br/>
接下来你需要在线处理M次操作：<br/>
0 x k 表示发生了一次地震，震中城市为x，影响范围为k，所有与x距离不超过k的城市都将受到影响，该次地震造成的经济损失为所有受影响城市的价值和。<br/>
1 x y 表示第x个城市的价值变成了y。<br/>
为了体现程序的在线性，操作中的x、y、k都需要异或你程序上一次的输出来解密，如果之前没有输出，则默认上一次的输出为0。</p></div>

# Input

<div class="content"><p>第一行包含两个正整数N和M。<br/>
第二行包含N个正整数，第i个数表示value[i]。<br/>
接下来N-1行，每行包含两个正整数u、v，表示u和v之间有一条无向边。<br/>
接下来M行，每行包含三个数，表示M次操作。</p></div>

# Output

<div class="content"><p>包含若干行，对于每个询问输出一行一个正整数表示答案。</p></div>

# Sample Input

<div class="content"><span class="sampledata">8 1<br/>
1 10 100 1000 10000 100000 1000000 10000000<br/>
1 2<br/>
1 3<br/>
2 4<br/>
2 5<br/>
3 6<br/>
3 7<br/>
3 8<br/>
0 3 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">11100101<br/>
</span></div>

# Hint

<div class="content"><p></p><p>1&lt;=N,M&lt;=100000<br/><br/>
1&lt;=u,v,x&lt;=N<br/><br/>
1&lt;=value[i],y&lt;=10000<br/><br/>
0&lt;=k&lt;=N-1</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

