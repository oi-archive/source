
# Description

<div class="content"><div>【题目背景】</div>
<div>We could have had it all. . . . . .</div>
<div>我们本该，拥有一切</div>
<div>Counting on a tree. . . . . .</div>
<div>何至于此，数数树上</div>
<div>Counting on a Tree（ CoaT）即是本题的英文名称。</div>
<div>【题目描述】</div>
<div>AccessGlobe最近正在玩一款战略游戏。在游戏中，他操控的角色是一名C国士兵。他的任务就是服从指挥官的指令</div>
<div>参加战斗，并在战斗中取胜。C国即将向D国发动一场秘密袭击。作战计划是这样的：选择D国的s个城市，派出C国</div>
<div>战绩最高的s个士兵分别秘密潜入这些城市。每个城市都有一个危险程度di，C国指挥官会派遣战绩最高的士兵潜入</div>
<div>所选择的城市中危险程度最高的城市，派遣战绩第二高的士兵潜入所选择的城市中危险程度次高的城市，以此类推</div>
<div>（即派遣战绩第i高的士兵潜入所选择城市中危险程度第i高的城市）。D国有n个城市，n-1条双向道路连接着这些</div>
<div>城市，使得这些城市两两之间都可以互相到达。为了任务执行顺利，C国选出的s个城市中，任意两个所选的城市，</div>
<div>都可以不经过未被选择的城市互相到达。AccessGlobe操控的士兵的战绩是第k高，他希望能估计出最终自己潜入的</div>
<div>城市的危险程度。AccessGlobe假设C国是以等概率选出任意满足条件的城市集合S，他希望你帮他求出所有可能的</div>
<div>城市集合中，AccessGlobe操控的士兵潜入城市的危险程度之和。如果选择的城市不足k个，那么AccessGlobe不会</div>
<div>被派出，这种情况下危险程度为0。当然，你并不想帮他解决这个问题，你也不打算告诉他这个值除以998,244,353</div>
<div>的余数，你只打算告诉他这个值除以64,123的余数。</div></div>

# Input

<div class="content"><div>
<div>第1行包含3个整数n、k、W</div>
<div>表示D国城市的个数、AccessGlobe所操控士兵潜入的城市战绩排名以及D国的所有城市中最大的危险程度；</div>
<div>第2行包含n个1到W之间的整数d1,d2,...,dn，表示每个城市的危险程度；</div>
<div>第3行到第n+1行，每行两个整数xi,yi，表示D国存在一条连接城市xi和城市yi的双向道路</div>
<div>1 ≤ k ≤ n,， 1 ≤ di ≤ W， n, k, W ≤ 1, 666。</div>
</div></div>

# Output

<div class="content"><div>
<div>输出一个整数，表示所有可行的城市集合中</div>
<div>AccessGlobe操控的士兵潜入城市的危险程度之和除以64,123的余数。</div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">5 3 3<br/>
2 1 1 2 3<br/>
1 2<br/>
2 3<br/>
1 4<br/>
1 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">11</span></div>

# Hint

<div class="content"><p></p><p> 请不要提交，原题空间限制为1G,单点时限5s.请下载数据自行测评.数据如下:https://begin.lydsy.com/JudgeOnline/upload/5240.rar</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

