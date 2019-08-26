
# Description

<div class="content"><div><span style="font-size: medium">一棵树上有<i>n</i> 只猴子. 他们从1 到 <i>n</i>编号. 编号为1 的猴子用它的尾巴盘住了一个树枝. 剩下的猴子要么被其他的猴子钩住要么就是自己用手钩住其他的猴子. 每只猴子都可以用两只手去钩其他的猴子,每只手最多只能钩一只. 从0时刻开始, 每一秒都有一只猴子松开它的一只手. 这也许会造成一些猴子掉落到地上, 我们想要知道它们掉落地上的时间(猴子掉落的速度都非常的快,可以忽略掉落的时间).</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行包含两个整数<i>n</i>和 <i>m</i>, 1 &lt;= <i>n</i> &lt;= 200000, 1 &lt;= <i>m</i> &lt;= 400000. 整数 <i>n</i> 代表猴子总数, 数 <i>m</i> 代表我们观察猴子的总时间. 接下来 <i>n</i> 行描述初始的情形. 第 (<i>k</i> + 1) 行 (1 &lt;= <i>k</i> &lt;= <i>n</i>) 有两个整数分别代表猴子<i>k</i>的左手和右手分别抓住了哪两只猴子. -1 代表它的那只手是空的. 接下来<i>m</i>行代表我们观察到的猴子的活动. 第<i>i</i>行有两个整数(1 &lt;= <i>i</i> &lt;= <i>m</i>) 代表在第<i>i</i> – 1时刻放开手的是哪只猴子和它放开的是哪只手(1 – 左, 2 – 右). </span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">输出<i>n</i>个整数每行一个代表每只猴子掉落到地上的时间, 如果没有掉落, 输出-1. </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 2<br/>
<br/>
<br/>
-1 3<br/>
3 -1<br/>
1 2<br/>
1 2<br/>
3 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
-1<br/>
1<br/>
1<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

