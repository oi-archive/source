<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    炉石传说是暴雪公司的一款卡牌类游戏，平衡性很好<span style="text-decoration: none;">（</span><span style="text-decoration: line-through;">人家法师是暴雪亲女儿</span><span style="text-decoration: none;">）</span><span style="text-decoration: none;">，然而，有一种极其猥琐而又让人无力吐槽的卡组叫做T7猎（快攻卡组，抢血很快），由于每个人的卡组都不一样，在这里我们简化卡组，且<span style="text-decoration: none;">每张牌数量不限</span>，卡组里只有动物伙伴（HB），狼骑兵（LQ），鹰角弓（YJ），关门放狗（FG），火车王·艾诺里（HCW）以及</span>小精灵（JL）,暴龙王（BL）（<span style="text-decoration: line-through;">你跟我说哪个T7猎带这两个</span>），每张牌的属性将一一为大家介绍。</p><p><br></p><p><span style="text-decoration: none;"><br></span></p><p>先介绍几个机制：</p><p>每个英雄最多可以控制7个随从，英雄生命值小于1时视为死亡(<span style="text-decoration: line-through;">别跟我说骑士大宝剑砍猎人触发爆炸陷阱然后奶回来</span>)；</p><p>每个随从入场后需要休息一个回合才能攻击；</p><p>每个角色（随从+英雄）每回合只能攻击一次（<span style="text-decoration: line-through;">别跟我说风怒，这里不考虑</span>）；</p><p>当一个随从攻击另一个随从时双方的血量分别扣除对方的攻击力；<br></p><p>当一个随从的血量降低到1以下，则视为死亡。</p><p>英雄（YX）：玩家；</p><p>随从（SC）：小怪；</p><p>法力水晶（SJ）：开局有一个法力水晶，每回合获得一个法力水晶并充满所有空的法力水晶，最多拥有10个法力水晶，如果已经拥有10个法力水晶，每回合只充满所有空的法力水晶）；</p><p>英雄技能（JN）：消耗两点法力水晶，对敌方英雄造成2点伤害，每回合限用一次（假设对方没有英雄技能）；</p><p>冲锋（CFG）：入场时可以直接攻击；</p><p>战吼（ZH）：入场时发动效果；</p><p>嘲讽（CF）：对方必须攻击这个随从；</p><p>白板（BB）：没有任何特效，只有攻击力和血量；</p><p><span style="text-decoration: none;"><br></span></p><p><span style="text-decoration: none;"><br></span></p><p><span style="text-decoration: none;">再介绍几个随从：</span></p><p><span style="text-decoration: none;">小精灵（JL）：消耗0点法力水晶，攻击力1，血量1，白板；输入格式：JL</span></p><p><span style="text-decoration: none;">动物伙伴（HB）：消耗三点法力水晶，随机召唤一只动物伙伴（米莎 MS ，大野菊 YJ，雷欧克 OK）；输入格式：HB MS 或 HB YJ 或 HB OK；</span></p><p><span style="text-decoration: none;">米莎（MS）：嘲讽，攻击力4，血量4；输入格式：HB MS；</span></p><p><span style="text-decoration: none;">大野菊（YJ）：冲锋，攻击力4，血量2；输入格式：HB YJ;</span></p><p><span style="text-decoration: none;">雷欧克（OK）：在场时使所有友方随从加1点攻击力，攻击力2，血量4；输入格式：HB OK;</span></p><p><span style="text-decoration: none;">狼骑兵（LQ）：消耗三点法力水晶，攻击力3，血量1，冲锋；输入格式：LQ；</span></p><p><span style="text-decoration: none;">鹰角弓（YJG）：消耗三点法力水晶，武器（英雄使用），攻击力3，耐久2（一共可以攻击两次）；输入格式：YJG</span></p><p><span style="text-decoration: none;">关门放狗（FG）：消耗三点法力水晶，对方每有一个随从，召唤一条野狗；输入格式：FG</span></p><p>火车王·艾诺里（HCW)：消耗五点法力水晶，冲锋，战吼：为对方召唤两只雏龙；输入格式：HCW；</p><p>暴龙王（BL）：消耗9点法力水晶，冲锋，攻击力8，血量8；</p><p>雏龙：白板，攻击力1，血量1；</p><p>野狗：冲锋，攻击力1，血量1；<br></p><p><br></p><p><br></p><p>现在给你一个初始状态,以后每回合的抽牌情况和对手召唤随从的情况(对手每回合一定会在攻击前召唤一个随从，如果该随从生命值为0，则入场直接死亡,如果对方场上已经有7个随从了，则不论本回合召唤的随从的生命值是否为0，直接死亡），请你写程序预测在限定的回合数 N 内我方的T7猎能否把对方击杀,假设我方的T7猎的操作永远不会出现破绽。</p><p>为了降低难度，我们假设对方只有嘲讽和白板随从，对方只会攻击你的英雄或者是嘲讽随从，对方的随从总是非嘲讽的先攻击，攻击力高的先攻击，如果有多个随从攻击力相同，则血量高的先攻击，如果你场上有多个嘲讽随从，对方会优先攻击你场上攻击力较高的嘲讽随从，如果有多个嘲讽随从攻击力相同，对方会优先攻击血量低的嘲讽随从。</p><p>如果可以击杀对方则输出"You will be my prey!"</p><p>如果不能击杀对方则输出"Well done,I throw in the towel."</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是一个整数 N 表示给定的回合数</p><p><br></p><p>第二行描述我方初始状态，第一个整数表示我方生命值，第二个整数表示当前回合的法力水晶数目，第三个数字表示我方场上的随从数量。（起始状态我方不装备武器,场上无野狗和雏龙）</p><p><br></p><p>比如：</p><p>30 3 2</p><p>OK</p><p>OK</p><p>这组输入表示我方英雄有30点生命，当前回合有3点法力水晶，场上有2个随从，都是雷欧克。</p><p><br></p><p>再比如：</p><p>8 9 5 </p><p>BL </p><p>MS </p><p>YJ </p><p>HCW </p><p>OK</p><p>这组数据表示我方英雄有8点生命，当前回合有9点法力水晶，场上5个随从，分别是暴龙王，米莎，大野菊，火车王·艾诺里，雷欧克</p><p><br></p><p>第三行描述敌方初始状态，第一个整数为对方生命值，第二个整数表示对方随从数量，以下若干行为敌方随从的情况，比如：</p><p>26 4</p><p>BB 4 7</p><p>CF 1 2</p><p>CF 0 2</p><p>CF 8 8</p><p>表示敌方英雄有26点生命，场上4个随从，4-7白板，1-2嘲讽，0-2嘲讽，8-8嘲讽</p><p>（a-b XX 表示攻击力为a，血量为b，附带属性为XX的随从)</p><p><br></p><p>之后N行 每行两组数据，分别表示我方初始状态之后第i个回合抽到的牌（每回合只能抽一张牌）和对方这一回合召唤的随从（只会有白板和嘲讽）；</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共两行，</p><p>第一行</p><p>如果可以击杀对方输出&quot;You will be my prey!&quot;</p><p>如果不能击杀对方输出&quot;Well done,I throw in the towel.&quot;</p><p>第二行</p><p>如果可以击杀对方，输出击杀对方的最小回合数(不包括初始状态之前的回合)。</p><p>如果不能击杀对方，输出能对敌方英雄造成的最大伤害。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p><p>30 1 0</p><p>30 2</p><p>CF 6 5</p><p>CF 5 2</p><p>HB MS BB 0 2</p><p>YJG BB 2 2</p><p>FG CF 0 2</p><p>HCW CF 8 8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Well done,I throw in the towel.</p><p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于回合数 N 保证在int范围内，这里不考虑疲劳作战抽牌扣血。</p><p><br></p><p>温馨提示1：注意一些COMBO，比如手牌有火车王·艾诺里和关门放狗，先使用火车王·艾诺里再使用关门放狗可以多召唤两只野狗（火车王·艾诺里的战吼使对方场上多两个雏龙）。再比如手牌有雷欧克，先召唤雷欧克再攻击可以打出更多伤害。</p><p><br></p><p>温馨提示2：每一方场上最多只能有7个随从，如果场上已经铺满了随从，则不会再召唤任何随从。比如我方场上有6个随从，对方场上有3个随从，这时候使用关门放狗只会召唤1条野狗。<br></p><p><br></p><p>温馨提示3：不能击杀对方包括被对方击杀的情况（<span style="text-decoration: line-through;">玩T7猎玩成这样也是醉了</span>）。</p><p><br></p><p>温馨提示4：注意每张牌的优先级（这个就要靠大家自己理解了，这个说出来就没意思了),优先级高的不一定会先入场（参见温馨提示1）。</p><p><br></p><p>温馨提示5：请务必注意可以攻击对面的随从消除掉自己场上的随从，留出空位来召唤更强大的随从。</p><p><br></p><p>温馨提示6：起始状态算作已经结束的回合，且不包括在N个回合内。</p><p><br></p><p>温馨提示7：如果有法力水晶剩余，不要忘了使用英雄技能。</p><p><br></p><p>温馨提示8：每回合都是对方先行动。</p><p><br></p><p>温馨提示9：你的随从每回合不一定要攻击，对方的随从一定会攻击。</p><p><br></p><p>温馨提示10：你可以在某些回合不出牌。</p><p><br></p><p><span style="text-decoration: line-through;">温馨提示11：有了这个题目，大家是不是就有理由在做题的时候玩炉石了呢O(∩_∩)O~。</span></p><p><br></p><p>时间限制：10 S</p><p>空间限制：256 MB</p><p><br></p><p>PS：本人已连夜写出了可以通过的非骗分程序，程序量较大，效率偏低，if语句写的手软，(⊙﹏⊙)，共491行，不是纯模拟，算法及程序暂不公开，等到有10人通过此题（非骗分）时，将会公开我的算法和程序。（再次加强了数据。。。但是数据仍然不是很强。。。）</p>
</div>
</div>