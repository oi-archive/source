
# Description

<div class="content"><div>
<div>给出一棵N 个点的树，每个点有两层，每层有权值和颜色（黑白） 。要求支持以下操作。 </div>
<div>1. Cover s t color 将s到t的路径上的点的两层的颜色全部置为 color(0 白1 黑)</div>
<div>2. CVal index layer val 将index号点的 layer 层的权值修改为 val</div>
<div>3. CColor index layer color 将 index号点的 layer 层的颜色修改为 color</div>
<div>4. QMax s t 询问s到 t的路径上的白色最大权值和路径的权值（任意白色层为起点，每</div>
<div>次只能往相同点不同层或者相邻点同一层上移动，每个点的每一层最多走一次，路径经</div>
<div>过的层必须都是白色） ，若 s到 t上的路径没有白点则输出[Bad Request.]</div>
<div>5. QLen s t 询问s到t的路径上的白色最大权值和路径的长度，若 s到 t的路径上没有白</div>
<div>点则输出0</div>
<div>初始树上权值均为 1，颜色均为白色。</div>
<div>N&lt;=5W,Q&lt;=5W,1&lt;=val&lt;=1K,0&lt;=color,layer&lt;=1 所有数据不超过longint范围。 .</div>
</div>
<div></div></div>

# Input

<div class="content"><div>第一行一个数N，接下来N*2-2个数s，t，代表s与t之间有连边。第N+1行一个数Q，表示操作数。接下来Q行每行一个操作。</div></div>

# Output

<div class="content"><div>对于每次 QMax，QLen输出对应答案，用换行符分隔。</div></div>

# Sample Input

<div class="content"><span class="sampledata">6 <br/>
1 2 2 4 2 5 1 3 3 6 <br/>
7 <br/>
CVal 1 0 5 <br/>
CVal 1 1 3 <br/>
CColor 1 0 1 <br/>
CVal 2 0 5 <br/>
CVal 3 0 3 <br/>
QMax 5 6 <br/>
QLen 5 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">17<br/>
9</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

