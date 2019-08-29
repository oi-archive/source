<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　杰杰是魔法界的一名传奇人物。他对魔法具有深刻的洞察力，惊人的领悟力，以及令人叹为观止的创造力。自从他从事魔法竞赛以来，短短几年时间，就已经成为世界公认的实力最强的魔法选手之一。更让人惊叹的是，他几乎没有借助外界力量，完全凭借自己的努力达到了普通人难以企及的高度。在最近的世界魔法奥林匹克竞赛上，他使用高超的魔法本领，一路过关斩将，在最后时刻一举击败了前冠军“旅行者”，获得了魔法界最高的荣耀：女神奖杯！女神奖杯可不是一个普通的奖杯，她能够帮杰杰实现一个愿望。<br/>
　　杰杰本着实事求是的态度，审时度势，向女神奖杯提出了自己的愿望：想要一个女性朋友。<br/>
<br/>
　　杰杰的愿望实现了，可是女性朋友却和他不在一个城市。杰杰想要知道：如果要到达女性朋友的所在城市，有多少种方案供他选择？<br/>
　　杰杰所在的世界有n个城市，从1到n进行编号。任意两个城市都通过有向道路连接。每个城市u有k个入点权：in[u][1],in[u][2]...in[u][k]，有k个出点权：ou[u][1],ou[u][2]...ou[u][k]。对于任意两个城市(u,v)（u可以等于v），u到v的道路条数为(ou[u][1]*in[v][1]+ou[u][2]*in[v][2]+...+ou[u][k]*in[v][k])条。杰杰有m次询问，每次询问由三元组(u,v,d)构成，询问从u城市通过不超过d条道路到达v城市的方案数。<br/>
　　为了温柔的杰杰和他的女性朋友的美好未来，帮助他解答这个问题吧。</div>
# 输入格式

<div class="pdcont">　　第一行读入两个正整数n，k，含义如题所示。<br/>
<br/>
　　接下来n行每行2k个整数，第i行代表第i个城市，前k个整数代表i号城市的出点权，后k个整数代表i号城市的入点权：<br/>
　　ou[i][1],ou[i][2],…,ou[i][k],in[i][1],in[i][2],…,in[i][k]<br/>
　　接下来一个整数m，表示m个询问。<br/>
　　接下来m行，每行三个整数:u,v,d，询问从u城市通过不超过d条道路到达v城市的方案数。<br/>
　　将每个方案所经过的道路，按顺序写成一个序列（序列可以为空）。两个方案不同，当且仅当他们的道路序列不完全相同。</div>
# 输出格式

<div class="pdcont">　　对于每个询问，输出一个方案数。由于答案可能太大，输出其除以1000000007后的余数。</div>
# 样例输入

<div class="pddata">5 2<br/>
2 5 4 3<br/>
7 9 2 4<br/>
0 1 5 2<br/>
6 3 9 2<br/>
2147483647 1000000001 233522 788488<br/>
10<br/>
1 1 0<br/>
2 2 1<br/>
2 4 5<br/>
4 3 10<br/>
3 4 50<br/>
1 5 1000<br/>
3 5 1000000000<br/>
1 2 500000000<br/>
4 5 2147483647<br/>
3 1 2147483647</div>
# 样例输出

<div class="pddata">1<br/>
51<br/>
170107227<br/>
271772358<br/>
34562176<br/>
890241289<br/>
8516097<br/>
383966304<br/>
432287042<br/>
326522835<b>   </b></div>
# 数据规模和约定

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">测试点<br/>
</td><td valign="top" style="border:solid 1.0pt">n<br/>
</td><td valign="top" style="border:solid 1.0pt">k<br/>
</td><td valign="top" style="border:solid 1.0pt">m<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">1-3<br/>
</td><td valign="top" style="border:solid 1.0pt">20<br/>
</td><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">19<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">1000<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">45<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">5-7<br/>
</td><td valign="top" style="border:solid 1.0pt">50<br/>
</td><td valign="top" style="border:solid 1.0pt">20<br/>
</td><td valign="top" style="border:solid 1.0pt">45<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">8-10<br/>
</td><td valign="top" style="border:solid 1.0pt">1000<br/>
</td><td valign="top" style="border:solid 1.0pt">20<br/>
</td><td valign="top" style="border:solid 1.0pt">50<br/>
</td></tr></tbody></table><br/>
　　保证1&lt;=u, v&lt;=n, 其它所有读入为不超过2147483647的非负整数</div>

</div>