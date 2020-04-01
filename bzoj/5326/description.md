
# Description

<div class="content"><div>JSOI 王国的码农JYY 最近沉迷氪金手游无法自拔。由于长期缺少睡眠，他的精神分裂为了善良的JXX 和邪恶的JZZ</div>
<div>，JYY 的人生将何去何从，JXX 和JZZ展开了一场博弈。JYY 的人生共有N个重大事件，按照1,2,…,N编号。如果JX</div>
<div>X 影响了某个事件，JXX 将获得ai的收益，反之如果JZZ 影响了某个事件，JZZ 将获得bi的收益。JXX 和JZZ 面对</div>
<div>这N个事件，将从JXX 开始，轮流选择影响某个事件，这个被选择的事件在以后的回合中将不再能被选择，博弈一</div>
<div>直进行到所有的事件都被某一方影响为止。贪心的JZZ 使用非常简单的策略：每次在剩下的事件中选择bi最大的那</div>
<div>个。bi相同的情况下选择编号i比较小的。善良的JXX 则有更加长远的眼光：他在知道JZZ 的策略情况下，会采用</div>
<div>最优策略最大化他的最终收益减去JZZ 的最终收益的差。现在给出了博弈的初始条件，JYY 想知道最终JXX 的收益</div>
<div>减去JZZ 的收益的差是多少。但使得问题更为困难的是，JXX 会不断修正他对每件事情的估价。JXX 给出了Q 个操</div>
<div>作，每次操作会修改一个事件的ai值，JYY 需要快速计算每次操作后博弈的结果。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含一个正整数N，表示事件的个数。</div>
<div>第二行N 个正整数ai，表示JXX 影响每个事件的初始收益。</div>
<div>第三行N 个正整数bi，表示JZZ 影响每个事件的初始收益。</div>
<div>第四行一个正整数Q，表示修改操作的个数。</div>
<div>之后Q 行每行两个正整数xi和vi，表示将第xi个事件的ai值修改为vi。</div>
<div>1 ≤ N ≤ 10^5, 0 ≤ Q ≤ 10^5, 1 ≤ ai, bi, vi ≤ 10^9。</div>
<div></div></div>

# Output

<div class="content"><div>第一行输出一个正整数，表示在初始情况下JXX 和JZZ 收益的差。</div>
<div>之后Q 行每行一个正整数，表示在第i次修改后JXX 和JZZ 收益的差。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2 3 4 5<br/>
5 1 2 4 3<br/>
2<br/>
1 5<br/>
3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
6<br/>
6</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

