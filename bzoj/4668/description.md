
# Description

<div class="content"><div>1946 年 3 月 5 日，英国前首相温斯顿·丘吉尔在美国富尔顿发表“铁</div>
<div>幕演说”，正式拉开了冷战序幕。</div>
<div>美国和苏联同为世界上的“超级大国”，为了争夺世界霸权，两国及其</div>
<div>盟国展开了数十年的斗争。在这段时期，虽然分歧和冲突严重，但双方都</div>
<div>尽力避免世界范围的大规模战争（第三次世界大战）爆发，其对抗通常通</div>
<div>过局部代理战争、科技和军备竞赛、太空竞争、外交竞争等“冷”方式进</div>
<div>行，即“相互遏制，不动武力”，因此称之为“冷战”。</div>
<div>Reddington 是美国的海军上将。由于战争局势十分紧张，因此他需要</div>
<div>时刻关注着苏联的各个活动，避免使自己的国家陷入困境。苏联在全球拥</div>
<div>有 N 个军工厂，但由于规划不当，一开始这些军工厂之间是不存在铁路</div>
<div>的，为了使武器制造更快，苏联决定修建若干条道路使得某些军工厂联通。</div>
<div>Reddington 得到了苏联的修建日程表，并且他需要时刻关注着某两个军工</div>
<div>厂是否联通，以及最早在修建哪条道路时会联通。具体而言，现在总共有</div>
<div>M 个操作，操作分为两类：</div>
<div>• 0 u v，这次操作苏联会修建一条连接 u 号军工厂及 v 号军工厂的铁</div>
<div>路，注意铁路都是双向的;</div>
<div>• 1 u v， Reddington 需要知道 u 号军工厂及 v 号军工厂最早在加入第</div>
<div>几条条铁路后会联通，假如到这次操作都没有联通，则输出 0;</div>
<div>作为美国最强科学家， Reddington 需要你帮忙设计一个程序，能满足</div>
<div>他的要求。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数 N, M。</div>
<div>接下来 M 行，每行为 0 u v 或 1 u v 的形式。</div>
<div>数据是经过加密的，对于每次加边或询问，真正的 u, v 都等于读入的</div>
<div>u, v 异或上上一次询问的答案。一开始这个值为 0。</div>
<div>1 ≤ N, M ≤ 500000，解密后的 u, v 满足1 ≤ u, v ≤ N, u不等于v</div></div>

# Output

<div class="content"><div>对于每次 1 操作，输出 u, v 最早在加入哪条边后会联通，若到这个操</div>
<div>作时还没联通，则输出 0。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 9<br/>
0 1 4<br/>
1 2 5<br/>
0 2 4<br/>
0 3 4<br/>
1 3 1<br/>
0 7 0<br/>
0 6 1<br/>
0 1 6<br/>
1 2 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
3<br/>
5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

