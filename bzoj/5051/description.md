
# Description

<div class="content"><div>在这个填字游戏中，有一个n*n的网格图。有些格子是空的，而另外的格子是不可用的。在网格的4个边界上放置着</div>
<div>若干个元件，每个元件上写着一个大写字母。左右边界的元件可以放置到与它们在同一行的空位中；上下边界的元</div>
<div>件可以放置到与它们在同一列的空位中。每个空位必须且只能放置一个元件，且空位数量与元件数量总是相等的。</div>
<div>游戏的目标是将所有元件各自放置到一个空位上，填满所有空位。比如对于下图的游戏，可以这么填放：</div>
<div><img src="/source/bzoj/5051/img/aHR0cDovL2JlZ2luLmx5ZHN5LmNvbS9KdWRnZU9ubGluZS91cGxvYWQvMjI5MS5wbmc=.png" alt=""/></div>
<div>给定一个填字游戏的初始状态，请统计有多少种可行的最终局面。</div>
<div>两种局面被认为相同的，当且仅当对应位置上的字母都相同。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含一个正整数n(4&lt;=n&lt;=13)，表示网格的尺寸。</div>
<div>接下来n+2行，每行n+2个字符，描述初始局面。其中.表示空位，#表示不可用格子，大写字母表示元件。</div>
<div>输入数据保证元件都位于边界上，且不位于角落，且上下边界的字符集与左右边界的字符集交集为空集。</div>
<div></div></div>

# Output

<div class="content"><div>输出一行一个整数，即方案数。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
##ARRR#<br/>
H.#.##S<br/>
Y.....E<br/>
O.#.#.E<br/>
##....E<br/>
###.#.E<br/>
#XNT#A#</span></div>

# Sample Output

<div class="content"><span class="sampledata">768</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获取">本OJ付费获取</a></p></div>

