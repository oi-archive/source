
# Description

<div class="content"><div>
<div>给定一个长度为n的正整数数列a[i]。</div>
<div>定义2个位置的graze值为两者位置差与数值差的和，即graze(x,y)=|x-y|+|a[x]-a[y]|。</div>
<div>2种操作（k都是正整数）：</div>
<div>1.Modify x k：将第x个数的值修改为k。</div>
<div>2.Query x k：询问有几个i满足graze(x,i)&lt;=k。因为可持久化数据结构的流行，询问不仅要考虑当前数列，还要</div>
<div>考虑任意历史版本，即统计任意位置上出现过的任意数值与当前的a[x]的graze值&lt;=k的对数。（某位置多次修改为</div>
<div>同样的数值，按多次统计）</div>
</div></div>

# Input

<div class="content"><div>第1行两个整数n,q。分别表示数列长度和操作数。</div>
<div>第2行n个正整数，代表初始数列。</div>
<div>第3--q+2行每行一个操作。</div></div>

# Output

<div class="content"><p>对于每次询问操作，输出一个非负整数表示答案</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 5<br/>
2 4 3<br/>
Query 2 2<br/>
Modify 1 3<br/>
Query 2 2<br/>
Modify 1 2<br/>
Query 1 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
3<br/>
3<br/>
</span></div>

# Hint

<div class="content"><p></p><p>N&lt;=60000 修改操作数&lt;=40000 询问&lt;=50000 Max{a[i]}含修改&lt;=100000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

