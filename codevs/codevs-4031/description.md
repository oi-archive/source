<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    今年的炉石传说中美对抗赛打的可谓是精彩绝伦，扣人心弦<span style="text-decoration: line-through;">以及毫无悬念</span>啊！</p><p>中国队的选手朝神在所有比赛中几乎没有失误，在第三场比赛时连胜7局<span style="text-decoration: line-through;">（<span style="text-decoration: line-through;">毕竟</span>人家清华博士。。然并卵，队友太坑。。）</span>也是创下了纪录。其中有一局朝神使用奴隶战对战美国选手的大王术，朝神在4秒钟内算出3墙26血斩杀，成为了高水平奴隶战的典范。然后……全炉石都在玩奴隶战。。。吓得我赶紧组了一套专杀奴隶战的套牌打上了天梯5级。。然后全金土豪站上了传说。。这是后话。。那么现在问题来了，给你我方的手牌，脸上挂的武器和场上随从的情况，作为一个会编程的人，电脑的运算速度一定比朝神快，所以请你写一个程序在一秒钟内算出最高斩杀线是多少。</p><p><br></p><p>卡牌介绍：</p><p>恐怖的奴隶主（NL）：5费，如果该随从受到伤害后没有死亡，则召唤另外一个恐怖的奴隶主。        攻击力：3     血量：3</p><p>战歌指挥官（ZG）：3费，每当你召唤一个攻击力小于或等于3的随从，使该随从获得冲锋。        攻击力：2     血量：3</p><p>暴乱狂战士（BL）：3费，每当一个随从受到伤害时，便获得+1攻击力。        攻击力：2     血量4</p><p>索瑞森大帝（DD）：6费，回合结束时使你所有手牌的法术消耗-1。        攻击力5    血量5</p><p>旋风斩（XF）：1费，对所有随从造成1点伤害。。</p><p>怒火中烧（NH）：0费，对一个随从造成1点伤害,该随从获得+2攻击力。</p><p>死亡之咬（SY）：4费，攻击力4，耐久度2，亡语：对所有随从造成1点伤害。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包括四个整数N,M,T,K,P。</p><p>第一个整数N表示当前回合你手牌的数量；</p><p>第二个整数M表示你的对手场上随从的数量；</p><p>第三个整数T表示索瑞森大帝曾经在场上存活的回合数（假设索瑞森大帝已经死亡且所有手牌都获得了减费的效果，每张牌的费用不能小于0）；<br></p><p style="">第四个整数K表示当前回合你所能使用的费用；</p><p>第五个整数P表示你脸上武器的耐久度（默认武器为死亡之咬，且取值只可能为0，1或2）。</p><p><br></p><p>第二行 包括N个字符串，分别表示你的各张手牌。</p><p><br></p><p>接下来M行为你的对手场上的随从情况。</p><p>用CF X Y来表示一个随从攻击力为X，血量为Y且带有嘲讽属性（必须先攻击带有嘲讽的随从才能攻击英雄）。</p><p>用BB X Y来表示一个随从攻击力为X，血量为Y且不带有任何特殊属性。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一个非负整数，表示本回合内的斩杀线。</p><p><br/></p><p>斩杀线表示本回合内可以对敌方<span style="color: rgb(255, 0, 0);">英雄</span>造成的最大伤害。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 4 1 10 1</p><p>ZG NL BL XF<br></p><p>CF 2 3</p><p>CF 1 3</p><p>BB 7 5</p><p>BB 7 7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>36</p><p><br></p><p>先召唤出战歌，暴乱，奴隶主。</p><p>奴隶主攻击1-3嘲讽（暴乱+2攻击力，奴隶主生一个仔）</p><p>然后施放旋风斩（暴乱+7攻击力，两个奴隶主各生一个仔）</p><p>还剩2血的奴隶主攻击2-3嘲讽（暴乱+2攻击力，该奴隶主死亡）<br></p><p>死亡之咬砍对面的脸，触发亡语旋风斩效果（暴乱+7攻击力，1血奴隶主死亡，剩下两个奴隶主各生一个仔）</p><p>20攻击力的暴乱打脸    (￣ε(#￣)☆╰╮(￣▽￣///)</p><p>四个奴隶主打脸    (￣ε(#￣)☆╰╮(￣▽￣///)</p><p style=""><br></p><p style="">_(:зゝ∠)_</p><p style="">伤害总值为：20+4*3+4=36点<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>提供一些斩杀的思路：</p><p>    1：战歌+奴隶主 生出来一波奴隶主<br></p><p>    2：战歌+暴乱 累计高伤害一波冲脸<br></p><p>    3：战歌+奴隶主+暴乱 我不想说什么了<br></p><p><br></p><p>以下是几个机制：</p><p>    1.双方场上的随从均不得多于7个。</p><p>    2.死亡之咬在砍完最后一下的时候会自动触发亡语。</p><p>    3.当战歌只剩一点生命值的时候使用旋风斩，战歌会使生出来的奴隶主获得冲锋然后壮烈牺牲。</p><p>    4.本回合入场的随从无法攻击。（也就是说没有战歌指挥官，不论多高的斩杀都打不出来，除了脸上有死亡之咬的时候可以打出4点伤害）。</p><p>    5.奴隶主生仔的判定时间先于死亡结算时间，也就是说如果场上有3个1血的奴隶主和4个2血的奴隶主，施放一发旋风斩之后场上只会有4个1血的奴隶主，每一轮判定或结算只会进行一次。</p><p><br></p><p><br></p><p><br></p><p>空间限制 ： 128 M</p><p>时间限制 ： 1 S</p>
</div>
</div>