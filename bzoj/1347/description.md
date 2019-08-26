
# Description

<div class="content"><div>在信号处理中，人们有时会对一个给定表达式的最大值感兴趣。这个表达式只含有二进制AND和OR运算，变量都为</div>
<div>整数且有一定的取值范围。请你编写程序，求出一个给定表达式的最大值。为了简化题目，这里只考虑一种特殊的</div>
<div>表达式，它有若干个由AND连接的子表达式构成，而每个子表达式内只含有OR运算。这样，一个表达式可以由它的</div>
<div>子表达式数量和每个表达式内变量的个数唯一确定。</div>
<div>例如，(3,1,2,2)表示的表达式为 E=(v1 OR v2 OR v3) AND (v4) AND (v5 OR v6) and (v7 OR v8)</div></div>

# Input

<div class="content"><div>第一行为两个整数N和P，其中N为变量的个数(1≤N≤100)，P为子表达式的个数(1≤P≤N)。 </div>
<div>第二行为P个整数K1,K2,…,KP，其中Ki表示第i个子表达式的变量个数(Ki≥1，SigmaKi=N(1&lt;=i&lt;=N) 。 </div>
<div>接下来N行，每行两个整数Aj和Bj，表示变量vj的取值范围为[Aj,Bj](0≤Aj≤Bj≤2000000000)。</div></div>

# Output

<div class="content"><p>一个整数，为表达式的最大值。</p></div>

# Sample Input

<div class="content"><span class="sampledata">8 4<br/>
3 1 2 2<br/>
2 4<br/>
1 4<br/>
0 0<br/>
1 7<br/>
1 4<br/>
1 2<br/>
3 4<br/>
2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">6</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

