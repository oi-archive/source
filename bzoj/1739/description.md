
# Description

<div class="content"><p><span style="font-size: medium">The cows are going to space! They plan to achieve orbit by building a sort of space elevator: a giant tower of blocks. They have K (1 &lt;= K &lt;= 400) different types of blocks with which to build the tower. Each block of type i has height h_i (1 &lt;= h_i &lt;= 100) and is available in quantity c_i (1 &lt;= c_i &lt;= 10). Due to possible damage caused by cosmic rays, no part of a block of type i can exceed a maximum altitude a_i (1 &lt;= a_i &lt;= 40000). Help the cows build the tallest space elevator possible by stacking blocks on top of each other according to the rules. </span></p>
<div><span style="font-size: medium">牛们要到太空去了！他们打算建造一座太空电梯来送他们进入轨道．</span></div>
<div><span style="font-size: medium">有K(1≤K≤400)神方块，第i种有一个特定的高度hi(l≤hi≤100)，一定的存量ci(l≤ci≤10).为防宇宙射线的破坏，第i种方块的任何部分不能超过高度ai(l≤ai≤40000)．</span><span style="font-size: medium"> 请用这些方块堆出最高的太空电梯．</span></div></div>

# Input

<div class="content"><p>* Line 1: A single integer, K * Lines 2..K+1: Each line contains three space-separated integers: h_i, a_i, and c_i. Line i+1 describes block type i.</p>
<div> </div>
<div><span style="font-size: medium">    第1行输入一个整数K.</span></div>
<div><span style="font-size: medium">    接下来K行，每行输入三个整数hi，ai，ci．</span></div></div>

# Output

<div class="content"><p>* Line 1: A single integer H, the maximum height of a tower that can be built</p>
<div> </div>
<div><span style="font-size: medium">    一个整数，表示最大高度．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
7 40 3<br/>
5 23 8<br/>
2 52 6<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">48<br/>
从底部开始，先放3个方块2，之后3个方块1，接下来6个方块3．不能把3个方块1堆到4个方<br/>
块2上，因为这样最高的方块1的顶部高度超过了40.<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

