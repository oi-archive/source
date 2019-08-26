
# Description

<div class="content"><div>Lj最近参加一个选秀比赛，有N个评委参加了这次评分，N是奇数。评委编号为1到N。每位评委给Lj打的分数是一个</div>
<div>整数，评委i(1 ≦ i ≦ N)的打分为Di。这次采用了一种创新的方法计算最后得分，计算规则是：最初N位评委排</div>
<div>成一排，检查队伍排头的3位评委的评分，去掉一个最高分和一个最低分，剩下的一个评委移动到队伍最后，反复</div>
<div>执行以上操作，直到队伍中的评委只剩一位，那么这个评委的打分就是Lj的最后得分。由于有的评委年纪比较大了</div>
<div>，不记得自己的位置了，现在有M(1 ≦ M ≦ N - 2)个评委很快找到了自己的位置，剩下的N-M人找不到位置了，</div>
<div>需要给他们重新安排位置。</div>
<div>由于Lj希望自己的得分尽可能高。请你帮忙计算出LJ最后得分可能的最大值。</div>
<p></p></div>

# Input

<div class="content"><div>第一行为整数N和M，用空格分隔。表示有N位评委，其中M人的初始排列位置已经确定。</div>
<div>接下来M行中第i行(1 ≦ i ≦ M)为两个整数Di和Pi，用空格分隔。</div>
<div>表示第i位评委的评分为Di，初始排列位置为队伍排头开始的第Pi位。</div>
<div>接下来N-M行中第i行(1 ≦ i ≦ N ? M)为整数Di+M，表示评委(i+M)的评分为Di+M。</div>
<div>3 ≦ N ≦ 99 999，</div>
<div>1 ≦ M ≦ N - 2，</div>
<div>1 ≦ Di ≦ 109 (1 ≦ i ≦ N)，</div>
<div>1 ≦ Pi ≦ N (1 ≦ i ≦ M)，</div>
<div>Pi != Pj (1 ≦ i &lt; j ≦ M)。</div>
<p></p></div>

# Output

<div class="content"><div> 输出一行，为1个整数，表示LJ得分的最大值。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 3<br/>
5 2<br/>
5 5<br/>
8 6<br/>
6<br/>
2<br/>
8<br/>
9</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
//最高得分的评分排列：2, 5, 6, 8, 5, 8, 9</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

