
# Description

<div class="content"><div>给出一棵n个点的树，每个点有两层，每层有权值和颜色（黑白）。要</div>
<div>求支持以下操作。</div>
<div>1. Cover s t color，将 s 到 t 的路径上的点的两层的颜色全部置为 color(0</div>
<div>白 1 黑)</div>
<div>2. CVal index layer val 将 index 号点的 layer 层的权值修改为 val</div>
<div>3. CColor index layer color 将 index 号点的 layer 层的颜色修改为 color</div>
<div>4. QMax s t 询问 s 到 t 的路径上的白色最大权值和路径的权值（任意</div>
<div>白色层为起点，每次只能往相同点不同层或者相邻点同一层上移动，</div>
<div>每个点的每一层最多走一次，路径经过的层必须都是白色），若 s 到</div>
<div>t 上的路径没有白点则输出”Bad Request.”</div>
<div>5. QLen s t 询问 s 到 t 的路径上的白色最大权值和路径的最大长度，若</div>
<div>s 到 t 的路径上没有白点则输出 0</div>
<div>初始树上权值均为1，颜色均为白色。</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个整数n表示树的点数</div>
<div>接下来n−1行每行两个数s,t表示s,t有边相连</div>
<div>接下来一行一个数Q表示操作数</div>
<div>接下来Q行表示一个操作</div>
<div>n, Q ≤ 50000, val ≤ 1000</div>
<p></p></div>

# Output

<div class="content"><div>对于每个 Qmax QLen 输出一行表示答案</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
6<br/>
1 2<br/>
2 4<br/>
2 5<br/>
1 3<br/>
3 6<br/>
7<br/>
CVal 1 0 5<br/>
CVal 1 1 3<br/>
CColor 1 0 1<br/>
CVal 2 0 5<br/>
CVal 3 0 3<br/>
QMax 5 6<br/>
QLen 5 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">17<br/>
9</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

