
# Description

<div class="content"><p>　　一个叫做立方体大作战的游戏风靡整个Byteotia。这个游戏的规则是相当复杂的，所以我们只介绍他的简单规<br/>
则：给定玩家一个有2n个元素的栈，元素一个叠一个地放置。这些元素拥有n个不同的编号，每个编号正好有两个<br/>
元素。玩家每次可以交换两个相邻的元素。如果在交换之后，两个相邻的元素编号相同，则将他们都从栈中移除，<br/>
所有在他们上面的元素都会掉落下来并且可以导致连锁反应。玩家的目标是用最少的步数将方块全部消除。</p></div>

# Input

<div class="content"><p>　　第一行包含一个正整数n(1&lt;=n&lt;=50000)。接下来2n行每行一个数ai，从上到下描述整个栈，保证每个数出现且<br/>
仅只出现两次(1&lt;=ai&lt;=n)。初始时，没有两个相同元素相邻。并且保证所有数据都能在1000000步以内出解。</p></div>

# Output

<div class="content"><p>　　第一行包含一个数m，表示最少的步数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">样例输入1<br/>
5<br/>
5<br/>
2<br/>
3<br/>
1<br/>
4<br/>
1<br/>
4<br/>
3<br/>
5<br/>
2<br/>
样例输入2<br/>
3<br/>
1<br/>
2<br/>
3<br/>
1<br/>
2<br/>
3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例输出1<br/>
2<br/>
样例输出2<br/>
3</span></div>

# Hint

<div class="content"><p></p><p><img border="0" alt="" src="/source/bzoj/1106/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzExMDZfMS5qcGc=.jpg"/> <img border="0" alt="" src="/source/bzoj/1106/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzExMDZfMi5qcGc=.jpg"/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

