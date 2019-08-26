
# Description

<div class="content"><div>在大学里，体育课有很多门，每个人都可以选自己最喜欢的项目。King这学期选的是篮球，因为篮球课的老师是一</div>
<div>个十分有趣的人。上课的第一天，老师宣布了这门课的评分规则：有n个篮球(n≥m)，老师事先在每个球上写了一</div>
<div>个整数(不一定相同，绝对值小于10000)。有m个篮，每个篮板上有一个计分器，显示一个整数。一个学生开始考核</div>
<div>前先将所有计分器显示值赋为1。每个学生考核时要进行n次投篮：选择任意一个篮球投向任意一个篮。最后他必须</div>
<div>将所有球全部投出且每个球恰好投出一次，要求每个篮至少被投进过一次。如果学生将一个写有整数x的篮球投进</div>
<div>了某个计分器显示为y的篮，则该篮板上的计分器显示值将从y变成y×x。一个学生的原始得分S定义为m个计分器的</div>
<div>显示值之和，如果S越大则老师给这个学生的最终打分越高（事实上，老师根据名次按照正态分布给分，但此超出</div>
<div>本题了讨论范围）。King是一个神投手，他保证能将n个球全都投进。但是King的数学十分糟糕，他不知道该如何</div>
<div>安排投篮，才能使得自己的原始得分最大，你能帮帮他吗？</div></div>

# Input

<div class="content"><div>
<div>输入有多组数据，</div>
<div>每组数据有两行：第一行两个整数n,m。第二行n个整数，用一个空格分开，表示老师在n个篮球上分别写下的整数。</div>
<div>文件以0 0结尾。一个文件中最多只有10组数据。</div>
<div>1≤ m≤n≤ 2000</div>
</div>
<div></div></div>

# Output

<div class="content"><div>每组数据一行，包含一个整数Smax，表示最大可能的原始得分。</div>
<div>提示：Smax可能超过任何基本整数类型。Smax也可能比0小。</div></div>

# Sample Input

<div class="content"><span class="sampledata">10 2<br/>
0 -1 -2 0 1 2 3 2 10 1<br/>
10 3<br/>
0 -1 -2 0 1 2 3 2 10 1<br/>
0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">240<br/>
241</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

