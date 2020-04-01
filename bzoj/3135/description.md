
# Description

<div class="content"><p><span style="font-size: medium">有<code>n</code>个水库，<code>m</code>条管道。Jester会在某些管道中间凿开一个洞，让水流出来或者用水泵把水打进去。保证这个流速是偶数。对于一条管道<code>(u, v)</code>，如果在中间凿开了一个洞让水流出来，流速是<code>2d m^3/s</code>，那么水库<code>u</code>和<code>v</code>失水速度为<code>d m^3/s</code>。同理，如果往一条管道<code>(u, v)</code>注水，流速为<code>2p m^3/s</code>，那么<code>u</code>和<code>v</code>得到水的速度是<code>p m^3/s</code>。</span></p>
<p><span style="font-size: medium">给定图的构造以及每个水库的水流的变化，问每条边的方案是否唯一。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行：水库数量<code>n</code>，管道数量<code>m</code> （<code>1 &lt;= n &lt;= 100 000, 1 &lt;= m &lt;= 500 000</code>）下面<code>n</code>行：第<code>i</code>个水库的变化速度<code>ci</code> （<code>-10^9 &lt;= ci &lt;= 10^9</code>）接下来<code>m</code>行：<code>(u, v)</code>，保证没有重边</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">如果方案唯一，输出方案，每行一个数<code>xi</code>（<code>-10^9 &lt;= xi &lt;= 10^9</code>）表示第<code>i</code>条管道的流量变化。放水为负数，灌水为正数。否则输出<code>0</code>。</span></p>
<h2><span style="font-size: medium">输入样例1</span></h2>
<pre><span style="font-size: medium"><code>4 3
-1
1
-3
1
1 2
1 3
1 4
</code></span></pre>
<h2><span style="font-size: medium">输入样例2</span></h2>
<pre><span style="font-size: medium"><code>4 5
1
2
1
2
1 2
2 3
3 4
4 1
1 3
</code></span></pre>
<h2></h2></div>

# Sample Input

<div class="content"><span class="sampledata"></span></div>

# Sample Output

<div class="content"><span class="sampledata">输出样例1<br/>
2<br/>
-6<br/>
2<br/>
<br/>
输出样例2<br/>
0<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=abcdabcd987提供">abcdabcd987提供</a></p></div>

