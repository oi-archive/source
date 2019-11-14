
# Description

<div class="content"><div>JOI 的家里有一个暖炉。JOI 自己耐寒能力比较强，所以他一个人在家里的时候不需要开暖炉，但是有客人的时候</div>
<div>就必须要开暖炉了。这一天，JOI 有 N 个客人，第 i (1≤i≤N) 位客人到达的时间是时刻 Ti，并在时刻 Ti+1 </div>
<div>离开，同时不会有多位客人同时到访。JOI 可以在任何时刻开启暖炉，不过在每次开启暖炉的时候会消耗一根火柴</div>
<div>。JOI 只有 K 根火柴，所以最多只能开启暖炉 K 次。在这一天最开始的时候，暖炉是关着的。暖炉开着的时候需</div>
<div>要燃料，因此 JOI 需要把握好开关暖炉的时间，并且他想最小化暖炉工作的总时间。给出 JOI 的客人们到访的时</div>
<div>间以及 JOI 拥有的火柴根数，你需要编写一个程序计算暖炉最少需要工作多长时间。</div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包括两个整数 N, K，表示有 N 为客人会拜访 JOI，并且 JOI 拥有 K 根火柴。</div>
<div>接下来 N 行，第 i+1 行给出一个整数 Ti，表示第 i 位客人将在时刻 Ti 抵达，并且将在时刻 Ti+1 离开。</div>
<div>1≤N≤100000，1≤K≤N，1≤Ti≤10^9 (1≤i≤N)，Ti&lt;Ti+1 (1≤i≤N-1)。</div>
<div></div>
<div class="panel_content"></div>
<div class="panel_content">
<pre><div style="FONT-FAMILY: Courier New,Courier,monospace"></div></pre>
</div>
<p></p></div>

# Output

<div class="content"><div>输出一行一个整数，表示暖炉工作的最少时间是多少。</div>
<div></div>
<div class="panel_content"></div>
<div class="panel_content">
<pre><div style="font-family: &#39;Courier New&#39;, Courier, monospace;"></div></pre>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2 <br/>
1 <br/>
3 <br/>
6</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
样例说明 1<br/>
在这一天，有三位客人要拜访 JOI。按照下述方法开关暖炉，可以保证每位客人拜访的时候暖炉均是工作的。<br/>
JOI 总共开启两次暖炉，并且暖炉总工作时间为 (4-1)+(7-6)=4。<br/>
JOI 会在时刻 1 即第一位客人抵达的时候开启暖炉，并在时刻 4 即第二位客人离开的时候关闭暖炉。<br/>
JOI 会在时刻 6 即第三位客人抵达的时候开启暖炉，并在时刻 7 即第三位客人离开的时候关闭暖炉。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

