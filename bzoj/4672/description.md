
# Description

<div class="content"><div>Alice和Bob在用n张牌玩一个游戏,这n张牌的编号为1到n,在游戏的一开始,每张牌</div>
<div>会被随机地分配给Alice或Bob.</div>
<div>这个游戏由若干回合组成,在每一回合,我们会随机选两张不相同的牌x和y.然后编号大</div>
<div>的牌将会被拿给编号小的牌的主人.</div>
<div>举个例子,如果Alice拥有编号为1的牌,而Bob拥有编号为2的牌,并且我们在当前回合</div>
<div>随机到的数为1和2,那么2将会被拿给Alice.</div>
<div>有一个叫Carol的人观看了游戏的全过程.在整个游戏开始前,Carol钦点了一个状态,并</div>
<div>且说,如果在游戏开始时,或者在任一回合结束时,当前牌的分布和他钦点的状态是一致的,那</div>
<div>么他就会吃一颗豆子.</div>
<div>如果在某一回合结束后,所有牌都属于同一个人,那么游戏将结束.</div>
<div>不妨假设Carol要吃的豆子数的期望为p/q,Carol感兴趣的是满足x·q≡p(mod10^9+7)</div>
<div>的x.请你输出x.</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行为一个整数n,表示牌的数量.</div>
<div>接下来为一个长度为n的字符串,表示Carol钦点的状态.其中第i个字符为A,表示在</div>
<div>Carol钦点的状态中,第i张牌要属于Alice,为B则表示这张牌要属于Bob.</div>
<div>1≤n≤10^5</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出一行一个整数,表示答案</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
BAB</span></div>

# Sample Output

<div class="content"><span class="sampledata">375000003</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

