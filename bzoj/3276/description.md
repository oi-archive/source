
# Description

<div class="content"><div>你现在处在一个2维平面中的(x,y)上，并且你的手上有一块磁铁。而在平面内，还有n块磁铁，每块磁铁都可以看</div>
<div>做一个点，你的任务就是得到最多的磁铁。每一块磁铁都有五个属性，x，y，m，p，r，分别表示磁铁的横坐标，</div>
<div>磁铁的纵坐标，磁铁的重量，磁铁的吸引力，磁铁的吸引半径。你手上的某个磁铁a想要把另一块在外面的磁铁b吸</div>
<div>引过来的条件如下：1.磁铁b和磁铁a之间的距离小于等于磁铁a的吸引半径。这里距离计算的是欧几里得距离。2.</div>
<div>磁铁b的重量小于等于磁铁a的吸引力。任何被你吸过来的磁铁都可以用来吸引新的磁铁。每块磁铁可以吸引无数多</div>
<div>次，但是每次只能有一块磁铁在吸引，不能多块同时吸引。同时你也只能呆在(x,y)这个位子上。现在你想要知道</div>
<div>，你最多可以吸引多少散落的磁铁。</div></div>

# Input

<div class="content"><div>第一行有五个整数，x，y，p，r，N</div>
<div>其中x，y，p，r分别表示你的坐标和你一开始拥有的磁铁的吸引力，吸引半径。</div>
<div>N表示散落的磁铁数目。</div>
<div>接下来N行每行5个整数，xi，yi，mi，pi，ri，</div>
<div>依次描述第i块散落的磁铁的横坐标，纵坐标，重量，吸引力，吸引半径。</div>
<div>n&lt;=250000.所有坐标都在-10^9到10^9之间。所有m p r都在1到10^9之间。</div>
<div>输入数据保证不含有任何两块磁铁在同一个位置。</div></div>

# Output

<div class="content"><p>输出一行，包含一个整数，你最多可以吸引的散落的磁铁数目</p></div>

# Sample Input

<div class="content"><span class="sampledata">0 0 5 10 5<br/>
5 4 7 11 5<br/>
-7 1 4 7 8<br/>
0 2 13 5 6<br/>
2 -3 9 3 4<br/>
13 5 1 9 9</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

