
# Description

<div class="content"><div>你正在评估一些关于一个巨型飞机仓库的建设计划。飞机仓库的地面可以表示为n行n列的网格图，其中每个格子要</div>
<div>么是空的，要么有障碍物。行从上到下依次被编号为1到n，列从左到右依次被编号为1到n。存放飞机零件的大型集</div>
<div>装箱能在飞机仓库的地面上自由移动是很重要的。我们可以将每个集装箱看作一个以某个格子为中心的边平行于坐</div>
<div>标轴的正方形。对于一个奇数k，一个尺寸为k的集装箱是一个包含k行k列的正方形。一个集装箱的坐标为其中心格</div>
<div>子的坐标。集装箱可以向上下左右移动，但不能碰到障碍物，且不能移出仓库的边界。给定q对格子A_k和B_k，对</div>
<div>于每对格子，请找到能从A_k移动到B_k的集装箱的最大尺寸，注意这个尺寸也要是一个奇数。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含一个正整数n(2&lt;=n&lt;=1000)，表示仓库的尺寸。</div>
<div>接下来n行，每行n个字符，描述整个仓库，其中“.”表示空格子，“#”表示障碍物。</div>
<div>接下来一行包含一个正整数q(1&lt;=q&lt;=300000)，表示询问的个数。</div>
<div>接下来q行，每行4个正整数r_A,c_A,r_B,c_B(1&lt;=r_A,c_A,r_B,c_B&lt;=n)，分别表示A和B的坐标。</div>
<div>输入数据保证A和B是不同的空格子。</div>
<div></div></div>

# Output

<div class="content"><div>输出q行，每行一个整数，对于每个询问输出最大尺寸，如果不存在解，那么输出0。</div>
<div>
<div></div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
7<br/>
.....#.<br/>
...#.#.<br/>
....#..<br/>
....###<br/>
....#..<br/>
#......<br/>
.......<br/>
5<br/>
2 5 5 2<br/>
2 5 3 6<br/>
2 2 6 3<br/>
2 2 6 6<br/>
1 1 7 7</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
0<br/>
3<br/>
1<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

