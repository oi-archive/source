
# Description

<div class="content"><div>水题嘉年华温暖节最盛大的活动，而主办方为了缓解大部分OIer常年把不到妹的问题，特别设置了一个有趣的活动</div>
<div>“脱单连连看”。规则是这样的，有M 个OIer和 M个妹子参加这个节目，主持人在黑板上按照某个顺序写下这N=2M</div>
<div> 个人的名字，然后请水题嘉年华的特邀嘉宾Lyra将OIer和妹子配对。具体来说，这M 个名字排成水平的一行，Lyr</div>
<div>a要画 M条折线，每条折线不能跨越名字所在的水平线，且必须连接一个OIer和一个妹子，任意两条折线不能相交</div>
<div>。举一个合法例子：</div>
<div> <img src="/source/bzoj/4694/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwOS8xMS5wbmc=.png" width="649" height="147" alt=""/></div>
<div>然而，很多OIer其实已经暗地里脱团了，于是每个OIer其实都带来了自己的妹子，只不过想借助这个活动来正大光</div>
<div>明的公布恋情。方便起见我们给每个人一个 0到 M-1的编号，一个OIer和他的妹子编号相同。Lyra的任务就是在合</div>
<div>法条件下连接每个OIer和他的妹子。现在 N个位置中某些位置的人已经确定了，剩下的由Lyra任意填写，Lyra想知</div>
<div>道，是否存在一种填写剩下位置的姓名的方式，使得她能在保证合法的前提下连接每个OIer和他的妹子。填写姓名</div>
<div>要保证0 到 M-1每个编号出现且只出现两次。</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个整数 ，以下T 组数据，对于每组数据：</div>
<div>第一行一个整数 表示OIer和妹子的总数目。</div>
<div>第二行 N个整数表示每个位置已经确定的姓名的编号， -1表示这个位置还没有确定。</div>
<div>输入保证 N为偶数且每个编号出现两次或零次。</div>
<div>T&lt;=30,N&lt;=50</div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据，若Lyra可以安排剩余的姓名并连接每个OIer和他的妹子</div>
<div>输出”POSSIBLE”，否则输出”IMPOSSIBLE”。（不含引号）</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
6<br/>
-1 0 -1 -1 0 -1<br/>
6<br/>
1 -1 2 1 -1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">POSSIBLE<br/>
IMPOSSIBLE<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

