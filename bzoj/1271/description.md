
# Description

<div class="content"><div>在秦腾进入北京大学学习的第一个学期，就不幸遇到了前所未有的教学评估。在教学评估期间，同学们被要求八点</div>
<div>起床，十一点回宿舍睡觉，不准旷课，上课不准迟到，上课不准睡觉……甚至连著名的北大三角地也在教学评估期</div>
<div>间被以影响校容的理由被拆除。这些“变态”规定令习惯了自由自在随性生活学习的北大同学叫苦不迭。这一天又</div>
<div>到了星期五，一大早就是秦腾最不喜欢的高等代数课。可是因为是教学评估时期，不能迟到，于是他在八点五分的</div>
<div>时候挣扎着爬出了宿舍，希望能赶快混进在八点钟已经上课了的教室。可是，刚一出宿舍楼门他就傻眼了:从宿舍</div>
<div>到教学楼的路上已经站满了教学评估团的成员。他们的目的就是抓住像他这样迟到的学生，扣除学校的分数。秦腾</div>
<div>当然不能让评估团得逞。他经过观察发现，整个评估团分成了N个小组，每个小组的成员都分布在从宿舍楼到教学</div>
<div>楼的路上的某一段，并且同一小组的成员间的距离是相等的。于是，我们可以用三个整数S,E,D来描述评估团的小</div>
<div>组:既该小组的成员在从宿舍到教学楼的路上的:S,S+D,S+2D,…,S+KD(K∈Z,S+KD≤E,S+(K+1)D&gt;E)位置。观察到了</div>
<div>教学评估团的这一特点，又经过了认真的思考，秦腾想出了对策:如果在路上的某一位置有奇数个教学评估团成员</div>
<div>，他就可以运用调虎离山，声东击西，隔山打牛，暗度陈仓……等方法，以这一地点为突破口到达教学楼。但是由</div>
<div>于教学评估团的成员的十分狡猾，成员位置安排的设计极其精妙，导致在整条路上几乎没有这样的位置出现。即使</div>
<div>由于安排不慎重出现了这样的位置，最多也仅有一个。现在秦腾观察出了所有小组的安排，但是由于整个教学评估</div>
<div>团的人数太多，他实在看不出这样的位置是否存在。现在，你的任务是写一个程序，帮助他做出判断。</div></div>

# Input

<div class="content"><div>第一行为T代表测试数据组数</div>
<div>每组第一行为N</div>
<div>接下来N行，每行三个整数Si,Ei,Di</div>
<div>N&lt;=200000</div>
<div>0&lt;=Si,Ei,Di&lt;=2^31-1</div>
<div>输入文件不大于2048K</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据如果所求位置不存在，则输出Poor Qin Teng:(</div>
<div>否则输出两个整数Posi,Count,代表在唯一位置Posi,有Count个教学评估图的成员</div>
<div>Count为奇数,注意输出的所有符号为英文半号</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
2<br/>
1 10 1<br/>
2 10 1<br/>
2<br/>
1 10 1<br/>
1 10 1<br/>
4<br/>
1 10 1<br/>
4 4 1<br/>
1 5 1<br/>
6 10 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 1<br/>
Poor QIN Teng:(<br/>
4 3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

