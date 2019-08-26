
# Description

<div class="content"><div>响应主旋律的号召，大家决定让这个班级充满爱，现在班级里面有 n 个男生。</div>
<div>如果 a 爱着 b，那么就相当于 a 和 b 之间有一条 a→b 的有向边。如果这 n 个点的图是强联通的，那么就认为这个班级是充满爱的。</div>
<div>不幸的是，有一些不好的事情发生了，现在每一条边都可能被摧毁。我作为爱的使者，想知道有多少种摧毁的方式，使得这个班级任然充满爱呢？（说人话就是有多少边的子集删去之后整个图仍然强联通。）</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个数 n 和 m，表示班级里的男生数和爱的关系数。</div>
<div>接下来 m 行，每行两个数 a 和 b，表示男生 a 爱着男生 b。同时 a 不等于 b。</div>
<div>所有男生从 1 到 n 标号。</div>
<div>同一条边不会出现两遍，但可能出现 a 爱着 b，b 也爱着 a 的情况，这是两条不同的边。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出一行一个整数,表示对 109+7 取模后的答案。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 15<br/>
4 3<br/>
4 2<br/>
2 5<br/>
2 1<br/>
1 2<br/>
5 1<br/>
3 2<br/>
4 1<br/>
1 4<br/>
5 4<br/>
3 4<br/>
5 3<br/>
2 3<br/>
1 5<br/>
3 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">9390</span></div>

# Hint

<div class="content"><p></p><div>对于 100% 的数据满足: n≤15,0≤m≤n(n−1)。</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2015年国家集训队测试">2015年国家集训队测试</a></p></div>

