
# Description

<div class="content"><div>Little Bytie really enjoys watching Formula One races which are held annually on a track between Bytetown and Byteburg. The most exciting moments for him are overtakes. He would like to see as many of them as possible.</div>
<div>Bytie is dreaming of a race in which N Formula One cars compete and the car that started the race at the i-th position (for each 1&lt;i&lt;N) performs Ai overtakes during the race. We assume for simplicity that at each moment of time at most one overtaking takes place, in which exactly two cars participate (that is, one car goes past another car).</div>
<div>Bytie is wondering whether such a race is possible at all. Could you help him figure this out?</div>
<div>
<div>有 n 辆赛车，从 1 到 n 依次出发。比赛结束时，你听说第 i 辆车超了 ai</div>
<div>次车。你想判断是否存在一种超车方案满足他所说的。</div>
<div>我们定义，在任意时刻最多只发生一次超车，即恰好两辆车参与这次超车</div>
<div>（一辆车超上了另一辆车）。不存在多辆车同时超过一辆车的情况。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains one positive integer i that represents the number of test cases that follow.</div>
<div>Each test case is described in two lines. The first line contains one integer N(1&lt;=N&lt;=1000 000): the number of cars that participate in the race. The second line holds a sequence of N integers A1,A2….An(0&lt;=Ai&lt;=10^9)  that gives the number of overtakes performed by the respective cars.</div>
<div>The size of a single input file does not exceed 20MB.</div>
<p></p></div>

# Output

<div class="content"><div>Your program should output T lines containing answers to the respective test cases. Each line should hold a single word TAK (Polish for yes) or NIE (Polish for no) depending on whether the race described by the test case is possible or not.</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
2<br/>
0 1<br/>
3<br/>
0 1 4<br/>
3<br/>
1 1 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK<br/>
NIE<br/>
TAK<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

