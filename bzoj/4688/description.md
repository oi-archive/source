
# Description

<div class="content"><div>考虑一个含有 N 个细胞的一维细胞自动机。细胞从 0 到 N-1 标号。每个细胞有一个被表示成一个小于 M 的非负</div>
<div>整数的状态。细胞的状态会在每个整数时刻发生骤变。我们定义 S(i,t)  表示第 i 个细胞在时刻 t 的状态。在</div>
<div>时刻 t+1 的状态被表示为 S(i,t+1)=(A×S(i-1,t)+B×S(i,t)+C×S(i+1,t) )  mod M ，其中 A,B,C 是给定的非</div>
<div>负整数。对于 i&lt;0 或 N≤i ，我们定义 S(i,t)=0 。给定一个自动机的定义和其细胞在时刻 0 的初始状态，你的</div>
<div>任务是计算时刻 T 时每个细胞的状态。</div>
<p></p></div>

# Input

<div class="content"><div>输入包含多组测试数据。每组数据的第一行包含六个整数 N,M,A,B,C,T ，满足 0&lt;N≤50,0&lt;M≤1000,0≤A,B,C&lt;M,0</div>
<div>≤T≤〖10〗^9  。第二行包含 N 个小于 M 的非负整数，依次表示每个细胞在时刻 0 的状态。输入以六个零作为</div>
<div>结束。</div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据，输出N个小于M的非负整数，每两个相邻的数字之间用一个空格隔开，表示每个细胞在时刻T的状态。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 4 1 3 2 0<br/>
0 1 2 0 1<br/>
5 7 1 3 2 1<br/>
0 1 2 0 1<br/>
5 13 1 3 2 11<br/>
0 1 2 0 1<br/>
5 5 2 0 1 100<br/>
0 1 2 0 1<br/>
6 6 0 2 3 1000<br/>
0 1 2 0 1 4<br/>
20 1000 0 2 3 1000000000<br/>
0 1 2 0 1 0 1 2 0 1 0 1 2 0 1 0 1 2 0 1<br/>
30 2 1 0 1 1000000000<br/>
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 0 0 0 0 0 0 0 0 0 0 0 0 0<br/>
30 2 1 1 1 1000000000<br/>
1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0<br/>
30 5 2 3 1 1000000000<br/>
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 0 0 0 0 0 0 0 0 0 0 0 0 0<br/>
0 0 0 0 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 1 2 0 1<br/>
2 0 0 4 3<br/>
2 12 10 9 11<br/>
3 0 4 2 1<br/>
0 4 2 0 4 4<br/>
0 376 752 0 376 0 376 752 0 376 0 376 752 0 376 0 376 752 0 376<br/>
1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 0<br/>
1 0 0 0 0 0 0 0 0 0 0 0 0 0 1 0 1 0 0 0 0 0 0 0 0 0 0 0 0 0<br/>
1 1 3 2 2 2 3 3 1 4 3 1 2 3 0 4 3 3 0 4 2 2 2 2 1 1 2 1 3 0<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供试题">鸣谢Tangjz提供试题</a></p></div>

