
# Description

<div class="content"><div>在一个有障碍点的 n 行 m 列的网格图中，我们用 (x,y) 来表示第 x 行第 y 列的格子。如果该网格图中的回路满足下面两个条件：</div>
<div>不经过任何一个障碍点</div>
<div>回路不自交</div>
<div>则我们称该回路为合法的简单回路。</div>
<div>现在有 Q 个询问，每次询问有多少条合法的简单回路经过了 (x,y) 与 (x+1,y) 之间的边。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行输入三个非负整数 n, m，k，表示 n 行 m 列的网格图中有 k 个障碍点。</div>
<div>接下来 k 行，每行两个正整数x,y (1≤x≤n,1≤y≤m)，表示 (x,y) 为一个障碍点（可能重复）</div>
<div>接下来一个整数 Q，表示 Q 个询问。</div>
<div>接下来 Q 行，每行两个正整数 x,y (1≤x≤n−1,1≤y≤m)，询问有多少条合法的简单回路经过了格子 (x,y) 与 (x+1,y) 之间的边。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出 Q 行，每行对应一组询问。请将答案 mod(1000000000+7) 之后输出。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4 4<br/>
2 2<br/>
2 4<br/>
3 2<br/>
4 4<br/>
4<br/>
1 1<br/>
1 4<br/>
3 3<br/>
2 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
0<br/>
1<br/>
0</span></div>

# Hint

<div class="content"><p></p><div>N&lt;=1000</div><br/>
<div>M&lt;=6</div><br/>
<div>K&lt;=100</div><br/>
<div>Q&lt;=10000</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2015年国家集训队测试">2015年国家集训队测试</a></p></div>

