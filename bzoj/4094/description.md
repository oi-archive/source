
# Description

<div class="content"><div>
<div>
<div>Farmer John最近购买了N(1 &lt;= N &lt;= 40000)台挤奶机，编号为1 ... N，并排成一行。第i台挤奶机每天能够挤M(i</div>
<div>)单位的牛奶 (1 &lt; =M(i) &lt;=100,000)。由于机器间距离太近，使得两台相邻的机器不能在同一天使用。Farmer Jo</div>
<div>hn可以自由选择不同的机器集合在不同的日子进行挤奶。在D(1 &lt; = D &lt; = 50,000)天中，每天Farmer John对某一</div>
<div>台挤奶机进行维护，改变该挤奶机的产量。Farmer John希望设计一个挤奶方案，使得挤奶机能够在D天后获取最多</div>
<div>的牛奶。</div>
</div>
</div>
<p></p></div>

# Input

<div class="content"><div>
<div>第1行：两个整数N和D</div>
<div>第2..N+1行：每台挤奶机的M(i)</div>
<div>第N+2..N+D+1行：两个整数i和m，表示每天对机器i进行维护，机器i的产量为m。</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>
<div>最大产量</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
1<br/>
2<br/>
3<br/>
4<br/>
5<br/>
5 2<br/>
2 7<br/>
1 10</span></div>

# Sample Output

<div class="content"><span class="sampledata">32<br/>
【样例解释】<br/>
第1天，最优方案为2+4=6  ( 方案1+3+2一样)<br/>
第2天，最优方案为7+4=11<br/>
第3天，最优方案为10+3+2=15<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

