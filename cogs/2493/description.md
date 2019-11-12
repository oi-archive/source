# 题目描述


<h3>
【题目描述】
</h3>
<p>
</p><center><img alt="" src="/upload/image/20161008/20161008164421_29771.jpg"/></center>
<p></p>
<p style="margin-left:0cm;">
<span style="font-size:10.5pt;color:#231F17;">魔兽世界的西面是红魔军的司令部，东面是蓝魔军的司令部。两个司令部之间是依次排列的若干城市，城市从西向东依次编号为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">1,2,3 .... N ( N &lt;= 20 )</span><span style="font-size:10.5pt;color:#231F17;">。红魔军的司令部算作编号为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">0</span><span style="font-size:10.5pt;color:#231F17;">的城市，蓝魔军的司令部算作编号为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">N+1</span><span style="font-size:10.5pt;color:#231F17;">的城市。司令部有生命元，用于制造武士。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">两军的司令部都会制造武士。武士一共有</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> dragon </span><span style="font-size:10.5pt;color:#231F17;">、</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">ninja</span><span style="font-size:10.5pt;color:#231F17;">、</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">iceman</span><span style="font-size:10.5pt;color:#231F17;">、</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">lion</span><span style="font-size:10.5pt;color:#231F17;">、</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">wolf </span><span style="font-size:10.5pt;color:#231F17;">五种。每种武士都有编号、生命值、攻击力这三种属性。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">双方的武士编号都是从</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">1</span><span style="font-size:10.5pt;color:#231F17;">开始计算。红方制造出来的第</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> n </span><span style="font-size:10.5pt;color:#231F17;">个武士，编号就是</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">n</span><span style="font-size:10.5pt;color:#231F17;">。同样，蓝方制造出来的第</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> n </span><span style="font-size:10.5pt;color:#231F17;">个武士，编号也是</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">n</span><span style="font-size:10.5pt;color:#231F17;">。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">武士在刚降生的时候有一个初始的生命值，生命值在战斗中会发生变化，如果生命值减少到</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">0</span><span style="font-size:10.5pt;color:#231F17;">（生命值变为负数时应当做变为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">0</span><span style="font-size:10.5pt;color:#231F17;">处理），则武士死亡（消失）。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">有的武士可以拥有武器。武器有三种，</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">sword, bomb,</span><span style="font-size:10.5pt;color:#231F17;">和</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">arrow</span><span style="font-size:10.5pt;color:#231F17;">，编号分别为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">0,1,2</span><span style="font-size:10.5pt;color:#231F17;">。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">武士降生后就朝对方司令部走，在经过的城市如果遇到敌人（同一时刻每个城市最多只可能有</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">1</span><span style="font-size:10.5pt;color:#231F17;">个蓝武士和一个红武士），就会发生战斗。每次战斗只有一方发起主动进攻一次。被攻击者生命值会减去进攻者的攻击力值和进攻者手中</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">sword</span><span style="font-size:10.5pt;color:#231F17;">的攻击力值。被进攻者若没死，就会发起反击，被反击者的生命值要减去反击者攻击力值的一半</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">(</span><span style="font-size:10.5pt;color:#231F17;">去尾取整</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">)</span><span style="font-size:10.5pt;color:#231F17;">和反击者手中</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">sword</span><span style="font-size:10.5pt;color:#231F17;">的攻击力值。反击可能致敌人于死地。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">如果武士在战斗中杀死敌人（不论是主动进攻杀死还是反击杀死），则其司令部会立即向其发送</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">8</span><span style="font-size:10.5pt;color:#231F17;">个生命元作为奖励，使其生命值增加</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">8</span><span style="font-size:10.5pt;color:#231F17;">。当然前提是司令部得有</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">8</span><span style="font-size:10.5pt;color:#231F17;">个生命元。如果司令部的生命元不足以奖励所有的武士，则优先奖励距离敌方司令部近的武士。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">如果某武士在某城市的战斗中杀死了敌人，则该武士的司令部立即取得该城市中所有的生命元。注意，司令部总是先完成全部奖励工作，然后才开始从各个打了胜仗的城市回收生命元。对于因司令部生命元不足而领不到奖励的武士，司令部也不会在取得战利品生命元后为其补发奖励。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">如果一次战斗的结果是双方都幸存</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">(</span><span style="font-size:10.5pt;color:#231F17;">平局</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">)</span><span style="font-size:10.5pt;color:#231F17;">，则双方都不能拿走发生战斗的城市的生命元。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">城市可以插旗子，一开始所有城市都没有旗子。在插红旗的城市，以及编号为奇数的无旗城市，由红武士主动发起进攻。在插蓝旗的城市，以及编号为偶数的无旗城市，由蓝武士主动发起进攻。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">当某个城市有连续两场战斗都是同一方的武士杀死敌人</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">(</span><span style="font-size:10.5pt;color:#231F17;">两场战斗之间如果有若干个战斗时刻并没有发生战斗，则这两场战斗仍然算是连续的；但如果中间有平局的战斗，就不算连续了</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">) </span><span style="font-size:10.5pt;color:#231F17;">，那么该城市就会插上胜方的旗帜，若原来插着败方的旗帜，则败方旗帜落下。旗帜一旦插上，就一直插着，直到被敌人更换。一个城市最多只能插一面旗帜，旗帜没被敌人更换前，也不会再次插同颜色的旗。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">各种武器有其特点：</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:&#34;color:#231F17;">sword</span><span style="font-size:10.5pt;color:#231F17;">武器的初始攻击力为拥有它的武士的攻击力的</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">20%</span><span style="font-size:10.5pt;color:#231F17;">（去尾取整）。但是</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">sword</span><span style="font-size:10.5pt;color:#231F17;">每经过一次战斗</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">(</span><span style="font-size:10.5pt;color:#231F17;">不论是主动攻击还是反击</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">)</span><span style="font-size:10.5pt;color:#231F17;">，就会变钝，攻击力变为本次战斗前的</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">80% (</span><span style="font-size:10.5pt;color:#231F17;">去尾取整</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">)</span><span style="font-size:10.5pt;color:#231F17;">。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">sword</span><span style="font-size:10.5pt;color:#231F17;">攻击力变为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">0</span><span style="font-size:10.5pt;color:#231F17;">时，视为武士失去了</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">sword</span><span style="font-size:10.5pt;color:#231F17;">。如果武士降生时得到了一个初始攻击力为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">0</span><span style="font-size:10.5pt;color:#231F17;">的</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">sword</span><span style="font-size:10.5pt;color:#231F17;">，则视为武士没有</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">sword.</span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:&#34;color:#231F17;">arrow</span><span style="font-size:10.5pt;color:#231F17;">有一个攻击力值</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">R</span><span style="font-size:10.5pt;color:#231F17;">。如果下一步要走到的城市有敌人，那么拥有</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">arrow</span><span style="font-size:10.5pt;color:#231F17;">的武士就会放箭攻击下一个城市的敌人（不能攻击对方司令部里的敌人）而不被还击。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">arrow</span><span style="font-size:10.5pt;color:#231F17;">使敌人的生命值减少</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">R</span><span style="font-size:10.5pt;color:#231F17;">，若减至小于等于</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">0</span><span style="font-size:10.5pt;color:#231F17;">，则敌人被杀死。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">arrow</span><span style="font-size:10.5pt;color:#231F17;">使用</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">3</span><span style="font-size:10.5pt;color:#231F17;">次后即被耗尽，武士失去</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">arrow</span><span style="font-size:10.5pt;color:#231F17;">。两个相邻的武士可能同时放箭把对方射死。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">拥有</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">bomb</span><span style="font-size:10.5pt;color:#231F17;">的武士，在战斗开始前如果判断自己将被杀死（不论主动攻击敌人，或者被敌人主动攻击都可能导致自己被杀死，而且假设武士可以知道敌人的攻击力和生命值），那么就会使用</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">bomb</span><span style="font-size:10.5pt;color:#231F17;">和敌人同归于尽。武士不预测对方是否会使用</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">bomb</span><span style="font-size:10.5pt;color:#231F17;">。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">武士使用</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">bomb</span><span style="font-size:10.5pt;color:#231F17;">和敌人同归于尽的情况下，不算是一场战斗，双方都不能拿走城市的生命元，也不影响城市的旗帜。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">不同的武士有不同的特点。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:&#34;color:#231F17;">dragon</span><span style="font-size:10.5pt;color:#231F17;">可以拥有一件武器。编号为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">n</span><span style="font-size:10.5pt;color:#231F17;">的</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">dragon</span><span style="font-size:10.5pt;color:#231F17;">降生时即获得编号为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> n%3 </span><span style="font-size:10.5pt;color:#231F17;">的武器。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">dragon</span><span style="font-size:10.5pt;color:#231F17;">还有</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">“</span><span style="font-size:10.5pt;color:#231F17;">士气</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">”</span><span style="font-size:10.5pt;color:#231F17;">这个属性，是个浮点数，其值为它降生后其司令部剩余生命元的数量除以造</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">dragon</span><span style="font-size:10.5pt;color:#231F17;">所需的生命元数量。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">dragon </span><span style="font-size:10.5pt;color:#231F17;">在一次在它主动进攻的战斗结束后，如果还没有战死，而且士气值大于</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">0.8</span><span style="font-size:10.5pt;color:#231F17;">，就会欢呼。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">dragon</span><span style="font-size:10.5pt;color:#231F17;">每取得一次战斗的胜利</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">(</span><span style="font-size:10.5pt;color:#231F17;">敌人被杀死</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">)</span><span style="font-size:10.5pt;color:#231F17;">，士气就会增加</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">0.2</span><span style="font-size:10.5pt;color:#231F17;">，每经历一次未能获胜的战斗，士气值就会减少</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">0.2</span><span style="font-size:10.5pt;color:#231F17;">。士气增减发生在欢呼之前。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:&#34;color:#231F17;">ninjia</span><span style="font-size:10.5pt;color:#231F17;">可以拥有两件武器。编号为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">n</span><span style="font-size:10.5pt;color:#231F17;">的</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">ninjia</span><span style="font-size:10.5pt;color:#231F17;">降生时即获得编号为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> n%3 </span><span style="font-size:10.5pt;color:#231F17;">和</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> (n+1)%3</span><span style="font-size:10.5pt;color:#231F17;">的武器。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">ninja </span><span style="font-size:10.5pt;color:#231F17;">挨打了也从不反击敌人。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:&#34;color:#231F17;">iceman</span><span style="font-size:10.5pt;color:#231F17;">有一件武器。编号为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">n</span><span style="font-size:10.5pt;color:#231F17;">的</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">iceman</span><span style="font-size:10.5pt;color:#231F17;">降生时即获得编号为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> n%3 </span><span style="font-size:10.5pt;color:#231F17;">的武器。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">iceman </span><span style="font-size:10.5pt;color:#231F17;">每前进两步，在第</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">2</span><span style="font-size:10.5pt;color:#231F17;">步完成的时候，生命值会减少</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">9</span><span style="font-size:10.5pt;color:#231F17;">，攻击力会增加</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">20</span><span style="font-size:10.5pt;color:#231F17;">。但是若生命值减</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">9</span><span style="font-size:10.5pt;color:#231F17;">后会小于等于</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">0</span><span style="font-size:10.5pt;color:#231F17;">，则生命值不减</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">9,</span><span style="font-size:10.5pt;color:#231F17;">而是变为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">1</span><span style="font-size:10.5pt;color:#231F17;">。即</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">iceman</span><span style="font-size:10.5pt;color:#231F17;">不会因走多了而死。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:&#34;color:#231F17;">lion </span><span style="font-size:10.5pt;color:#231F17;">有</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">“</span><span style="font-size:10.5pt;color:#231F17;">忠诚度</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">”</span><span style="font-size:10.5pt;color:#231F17;">这个属性，其初始值等于它降生之后其司令部剩余生命元的数目。每经过一场未能杀死敌人的战斗，忠诚度就降低</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">K</span><span style="font-size:10.5pt;color:#231F17;">。忠诚度降至</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">0</span><span style="font-size:10.5pt;color:#231F17;">或</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">0</span><span style="font-size:10.5pt;color:#231F17;">以下，则该</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">lion</span><span style="font-size:10.5pt;color:#231F17;">逃离战场</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">,</span><span style="font-size:10.5pt;color:#231F17;">永远消失。但是已经到达敌人司令部的</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">lion</span><span style="font-size:10.5pt;color:#231F17;">不会逃跑。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">Lion</span><span style="font-size:10.5pt;color:#231F17;">在己方司令部可能逃跑。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">lion </span><span style="font-size:10.5pt;color:#231F17;">若是战死，则其战斗前的生命值就会转移到对手身上。所谓</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">“</span><span style="font-size:10.5pt;color:#231F17;">战斗前</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">”</span><span style="font-size:10.5pt;color:#231F17;">，就是每个小时的</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">40</span><span style="font-size:10.5pt;color:#231F17;">分前的一瞬间。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:&#34;color:#231F17;">wolf</span><span style="font-size:10.5pt;color:#231F17;">降生时没有武器，但是在战斗中如果获胜（杀死敌人），就会缴获敌人的武器，但自己已有的武器就不缴获了。被缴获的武器当然不能算新的，已经被用到什么样了，就是什么样的。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">以下是不同时间会发生的不同事件：</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">在每个整点，即每个小时的第</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">0</span><span style="font-size:10.5pt;color:#231F17;">分，</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> </span><span style="font-size:10.5pt;color:#231F17;">双方的司令部中各有一个武士降生。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">红方司令部按照</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> iceman</span><span style="font-size:10.5pt;color:#231F17;">、</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">lion</span><span style="font-size:10.5pt;color:#231F17;">、</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">wolf</span><span style="font-size:10.5pt;color:#231F17;">、</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">ninja</span><span style="font-size:10.5pt;color:#231F17;">、</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">dragon </span><span style="font-size:10.5pt;color:#231F17;">的顺序制造武士。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">蓝方司令部按照</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> lion</span><span style="font-size:10.5pt;color:#231F17;">、</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">dragon</span><span style="font-size:10.5pt;color:#231F17;">、</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">ninja</span><span style="font-size:10.5pt;color:#231F17;">、</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">iceman</span><span style="font-size:10.5pt;color:#231F17;">、</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">wolf </span><span style="font-size:10.5pt;color:#231F17;">的顺序制造武士。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">制造武士需要生命元。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">制造一个初始生命值为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> m </span><span style="font-size:10.5pt;color:#231F17;">的武士，司令部中的生命元就要减少</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> m </span><span style="font-size:10.5pt;color:#231F17;">个。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">如果司令部中的生命元不足以制造某武士，那么司令部就等待，直到获得足够生命元后的第一个整点，才制造该武士。例如，在</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">2:00</span><span style="font-size:10.5pt;color:#231F17;">，红方司令部本该制造一个</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> wolf </span><span style="font-size:10.5pt;color:#231F17;">，如果此时生命元不足，那么就会等待，直到生命元足够后的下一个整点，才制造一个</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> wolf</span><span style="font-size:10.5pt;color:#231F17;">。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">在每个小时的第</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">5</span><span style="font-size:10.5pt;color:#231F17;">分，该逃跑的</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">lion</span><span style="font-size:10.5pt;color:#231F17;">就在这一时刻逃跑了。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">在每个小时的第</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">10</span><span style="font-size:10.5pt;color:#231F17;">分：所有的武士朝敌人司令部方向前进一步。即从己方司令部走到相邻城市，或从一个城市走到下一个城市。或从和敌军司令部相邻的城市到达敌军司令部。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">在每个小时的第</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">20</span><span style="font-size:10.5pt;color:#231F17;">分：每个城市产出</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">10</span><span style="font-size:10.5pt;color:#231F17;">个生命元。生命元留在城市，直到被武士取走。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">在每个小时的第</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">30</span><span style="font-size:10.5pt;color:#231F17;">分：如果某个城市中只有一个武士，那么该武士取走该城市中的所有生命元，并立即将这些生命元传送到其所属的司令部。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">在每个小时的第</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">35</span><span style="font-size:10.5pt;color:#231F17;">分，拥有</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">arrow</span><span style="font-size:10.5pt;color:#231F17;">的武士放箭，对敌人造成伤害。放箭事件应算发生在箭发出的城市。注意，放箭不算是战斗，因此放箭的武士不会得到任何好处。武士在没有敌人的城市被箭射死也不影响其所在城市的旗帜更换情况。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">在每个小时的第</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">38</span><span style="font-size:10.5pt;color:#231F17;">分，拥有</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">bomb</span><span style="font-size:10.5pt;color:#231F17;">的武士评估是否应该使用</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">bomb</span><span style="font-size:10.5pt;color:#231F17;">。如果是，就用</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">bomb</span><span style="font-size:10.5pt;color:#231F17;">和敌人同归于尽。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">在每个小时的第</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">40</span><span style="font-size:10.5pt;color:#231F17;">分：在有两个武士的城市，会发生战斗。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> </span><span style="font-size:10.5pt;color:#231F17;">如果敌人在</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">5</span><span style="font-size:10.5pt;color:#231F17;">分钟前已经被飞来的</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">arrow</span><span style="font-size:10.5pt;color:#231F17;">射死，那么仍然视为发生了一场战斗，而且存活者视为获得了战斗的胜利。此情况下不会有</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">“</span><span style="font-size:10.5pt;color:#231F17;">武士主动攻击</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">”</span><span style="font-size:10.5pt;color:#231F17;">，</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">“</span><span style="font-size:10.5pt;color:#231F17;">武士反击</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">”</span><span style="font-size:10.5pt;color:#231F17;">，</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">“</span><span style="font-size:10.5pt;color:#231F17;">武士战死</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">”</span><span style="font-size:10.5pt;color:#231F17;">的事件发生，但战斗胜利后应该发生的事情都会发生。如</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">Wolf</span><span style="font-size:10.5pt;color:#231F17;">一样能缴获武器，旗帜也可能更换，等等。在此情况下</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">,Dragon</span><span style="font-size:10.5pt;color:#231F17;">同样会通过判断是否应该轮到自己主动攻击来决定是否欢呼。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">在每个小时的第</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">50</span><span style="font-size:10.5pt;color:#231F17;">分，司令部报告它拥有的生命元数量。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">在每个小时的第</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">55</span><span style="font-size:10.5pt;color:#231F17;">分，每个武士报告其拥有的武器情况。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">武士到达对方司令部后就算完成任务了，从此就呆在那里无所事事。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">任何一方的司令部里若是出现了</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">2</span><span style="font-size:10.5pt;color:#231F17;">个敌人，则认为该司令部已被敌人占领。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">任何一方的司令部被敌人占领，则战争结束。战争结束之后就不会发生任何事情了。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">给定一个时间，要求你将从</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">0</span><span style="font-size:10.5pt;color:#231F17;">点</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">0</span><span style="font-size:10.5pt;color:#231F17;">分开始到此时间为止的所有事件按顺序输出。事件及其对应的输出样例如下：</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p class="MsoNormal">
<b><span style="font-family:&#34;color:#231F17;">1) </span></b><b><span style="color:#231F17;">武士降生</span></b><b><span style="font-family:&#34;color:#231F17;"></span></b> 
</p>
<p style="margin-left:36.0pt;">
<span style="font-size:10.5pt;color:#231F17;">输出样例：</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> 000:00 blue lion 1 born</span> 
</p>
<p style="margin-left:36.0pt;">
<span style="font-size:10.5pt;color:#231F17;">表示在</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> 0</span><span style="font-size:10.5pt;color:#231F17;">点</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">0</span><span style="font-size:10.5pt;color:#231F17;">分，编号为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">1</span><span style="font-size:10.5pt;color:#231F17;">的蓝魔</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">lion</span><span style="font-size:10.5pt;color:#231F17;">武士降生</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"><br/>
</span><span style="font-size:10.5pt;color:#231F17;">如果造出的是</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">dragon</span><span style="font-size:10.5pt;color:#231F17;">，那么还要多输出一行，例：</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p style="margin-left:36.0pt;">
<span style="font-size:10.5pt;font-family:&#34;color:#231F17;">000:00 blue dragon 1 born<br/>
Its morale is 23.34<br/>
<br/>
</span><span style="font-size:10.5pt;color:#231F17;">表示该该</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">dragon</span><span style="font-size:10.5pt;color:#231F17;">降生时士气是</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">23. 34(</span><span style="font-size:10.5pt;color:#231F17;">四舍五入到小数点后两位</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">)</span> 
</p>
<p style="margin-left:36.0pt;">
<span style="font-size:10.5pt;color:#231F17;">如果造出的是</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">lion</span><span style="font-size:10.5pt;color:#231F17;">，那么还要多输出一行，例</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">:<br/>
000:00 blue lion 1 born<br/>
Its loyalty is 24<br/>
<br/>
</span><span style="font-size:10.5pt;color:#231F17;">表示该</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">lion</span><span style="font-size:10.5pt;color:#231F17;">降生时的忠诚度是</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">24</span> 
</p>
<p class="MsoNormal">
<b><span style="font-family:&#34;color:#231F17;">2) lion</span></b><b><span style="color:#231F17;">逃跑</span></b><b><span style="font-family:&#34;color:#231F17;"></span></b> 
</p>
<p style="margin-left:36.0pt;">
<span style="font-size:10.5pt;color:#231F17;">输出样例：</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> 000:05 blue lion 1 ran away<span class="apple-converted-space"> </span><br/>
</span><span style="font-size:10.5pt;color:#231F17;">表示在</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> 0</span><span style="font-size:10.5pt;color:#231F17;">点</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">5</span><span style="font-size:10.5pt;color:#231F17;">分，编号为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">1</span><span style="font-size:10.5pt;color:#231F17;">的蓝魔</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">lion</span><span style="font-size:10.5pt;color:#231F17;">武士逃走</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p class="MsoNormal">
<b><span style="font-family:&#34;color:#231F17;">3) </span></b><b><span style="color:#231F17;">武士前进到某一城市</span></b><b><span style="font-family:&#34;color:#231F17;"></span></b> 
</p>
<p style="margin-left:36.0pt;">
<span style="font-size:10.5pt;color:#231F17;">输出样例：</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> 000:10 red iceman 1 marched to city 1 with 20 elements and
force 30<br/>
</span><span style="font-size:10.5pt;color:#231F17;">表示在</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> 0</span><span style="font-size:10.5pt;color:#231F17;">点</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">10</span><span style="font-size:10.5pt;color:#231F17;">分，红魔</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">1</span><span style="font-size:10.5pt;color:#231F17;">号武士</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">iceman</span><span style="font-size:10.5pt;color:#231F17;">前进到</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">1</span><span style="font-size:10.5pt;color:#231F17;">号城市，此时他生命值为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">20,</span><span style="font-size:10.5pt;color:#231F17;">攻击力为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">30<br/>
</span><span style="font-size:10.5pt;color:#231F17;">对于</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">iceman,</span><span style="font-size:10.5pt;color:#231F17;">输出的生命值和攻击力应该是变化后的数值</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p class="MsoNormal">
<b><span style="font-family:&#34;color:#231F17;">4)</span></b><b><span style="color:#231F17;">武士放箭</span></b><b><span style="font-family:&#34;color:#231F17;"></span></b> 
</p>
<p style="margin-left:36.0pt;">
<span style="font-size:10.5pt;color:#231F17;">输出样例：</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> 000:35 blue dragon 1 shot<br/>
</span><span style="font-size:10.5pt;color:#231F17;">表示在</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> 0</span><span style="font-size:10.5pt;color:#231F17;">点</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">35</span><span style="font-size:10.5pt;color:#231F17;">分，编号为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">1</span><span style="font-size:10.5pt;color:#231F17;">的蓝魔</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">dragon</span><span style="font-size:10.5pt;color:#231F17;">武士射出一支箭。如果射出的箭杀死了敌人，则应如下输出：</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"><br/>
000:35 blue dragon 1 shot and killed red lion 4<br/>
</span><span style="font-size:10.5pt;color:#231F17;">表示在</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> 0</span><span style="font-size:10.5pt;color:#231F17;">点</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">35</span><span style="font-size:10.5pt;color:#231F17;">分，编号为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">1</span><span style="font-size:10.5pt;color:#231F17;">的蓝魔</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">dragon</span><span style="font-size:10.5pt;color:#231F17;">武士射出一支箭，杀死了编号为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">4</span><span style="font-size:10.5pt;color:#231F17;">的红魔</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">lion</span><span style="font-size:10.5pt;color:#231F17;">。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p class="MsoNormal">
<b><span style="font-family:&#34;color:#231F17;">5)</span></b><b><span style="color:#231F17;">武士使用</span></b><b><span style="font-family:&#34;color:#231F17;">bomb</span></b> 
</p>
<p style="margin-left:36.0pt;">
<span style="font-size:10.5pt;color:#231F17;">输出样例：</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> 000:38 blue dragon 1 used a bomb and killed red lion 7<br/>
</span><span style="font-size:10.5pt;color:#231F17;">表示在</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> 0</span><span style="font-size:10.5pt;color:#231F17;">点</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">38</span><span style="font-size:10.5pt;color:#231F17;">分，编号为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">1</span><span style="font-size:10.5pt;color:#231F17;">的蓝魔</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">dragon</span><span style="font-size:10.5pt;color:#231F17;">武士用炸弹和编号为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">7</span><span style="font-size:10.5pt;color:#231F17;">的红魔</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">lion</span><span style="font-size:10.5pt;color:#231F17;">同归于尽。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p class="MsoNormal">
<b><span style="font-family:&#34;color:#231F17;">6) </span></b><b><span style="color:#231F17;">武士主动进攻</span></b><b><span style="font-family:&#34;color:#231F17;"></span></b> 
</p>
<p style="margin-left:36.0pt;">
<span style="font-size:10.5pt;color:#231F17;">输出样例：</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">000:40 red iceman 1 attacked blue lion 1 in city 1 with 20
elements and force 30<br/>
</span><span style="font-size:10.5pt;color:#231F17;">表示在</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">0</span><span style="font-size:10.5pt;color:#231F17;">点</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">40</span><span style="font-size:10.5pt;color:#231F17;">分，</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">1</span><span style="font-size:10.5pt;color:#231F17;">号城市中，红魔</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">1</span><span style="font-size:10.5pt;color:#231F17;">号武士</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">iceman </span><span style="font-size:10.5pt;color:#231F17;">进攻蓝魔</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">1</span><span style="font-size:10.5pt;color:#231F17;">号武士</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">lion,</span><span style="font-size:10.5pt;color:#231F17;">在发起进攻前，红魔</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">1</span><span style="font-size:10.5pt;color:#231F17;">号武士</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">iceman</span><span style="font-size:10.5pt;color:#231F17;">生命值为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">20</span><span style="font-size:10.5pt;color:#231F17;">，攻击力为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> 30</span> 
</p>
<p class="MsoNormal">
<b><span style="font-family:&#34;color:#231F17;">7) </span></b><b><span style="color:#231F17;">武士反击</span></b><b><span style="font-family:&#34;color:#231F17;"></span></b> 
</p>
<p style="margin-left:36.0pt;">
<span style="font-size:10.5pt;color:#231F17;">输出样例：</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">001:40 blue dragon 2 fought back against red lion 2 in city 1<span class="apple-converted-space"> </span><br/>
</span><span style="font-size:10.5pt;color:#231F17;">表示在</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">1</span><span style="font-size:10.5pt;color:#231F17;">点</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">40</span><span style="font-size:10.5pt;color:#231F17;">分，</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">1</span><span style="font-size:10.5pt;color:#231F17;">号城市中，蓝魔</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">2</span><span style="font-size:10.5pt;color:#231F17;">号武士</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">dragon</span><span style="font-size:10.5pt;color:#231F17;">反击红魔</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">2</span><span style="font-size:10.5pt;color:#231F17;">号武士</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">lion</span> 
</p>
<p class="MsoNormal">
<b><span style="font-family:&#34;color:#231F17;">8) </span></b><b><span style="color:#231F17;">武士战死</span></b><b><span style="font-family:&#34;color:#231F17;"></span></b> 
</p>
<p style="margin-left:36.0pt;">
<span style="font-size:10.5pt;color:#231F17;">输出样例：</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">001:40 red lion 2 was killed in city 1<br/>
</span><span style="font-size:10.5pt;color:#231F17;">被箭射死的武士就不会有这一条输出。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p class="MsoNormal">
<b><span style="font-family:&#34;color:#231F17;">9) </span></b><b><span style="color:#231F17;">武士欢呼</span></b><b><span style="font-family:&#34;color:#231F17;"></span></b> 
</p>
<p style="margin-left:36.0pt;">
<span style="font-size:10.5pt;color:#231F17;">输出样例：</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">003:40 blue dragon 2 yelled in city 4</span> 
</p>
<p class="MsoNormal">
<b><span style="font-family:&#34;color:#231F17;">10) </span></b><b><span style="color:#231F17;">武士获取生命元</span></b><b><span style="font-family:&#34;color:#231F17;">( elements
)</span></b> 
</p>
<p style="margin-left:36.0pt;">
<span style="font-size:10.5pt;color:#231F17;">输出样例：</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">001:40 blue dragon 2 earned 10 elements for his headquarter</span> 
</p>
<p class="MsoNormal">
<b><span style="font-family:&#34;color:#231F17;">11) </span></b><b><span style="color:#231F17;">旗帜升起</span></b><b><span style="font-family:&#34;color:#231F17;"></span></b> 
</p>
<p style="margin-left:36.0pt;">
<span style="font-size:10.5pt;color:#231F17;">输出样例：</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">004:40 blue flag raised in city 4</span> 
</p>
<p class="MsoNormal">
<b><span style="font-family:&#34;color:#231F17;">12) </span></b><b><span style="color:#231F17;">武士抵达敌军司令部</span></b><b><span style="font-family:&#34;color:#231F17;"></span></b> 
</p>
<p style="margin-left:36.0pt;">
<span style="font-size:10.5pt;color:#231F17;">输出样例：</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">001:10 red iceman 1 reached blue headquarter with 20 elements
and force 30<br/>
(</span><span style="font-size:10.5pt;color:#231F17;">此时他生命值为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">20,</span><span style="font-size:10.5pt;color:#231F17;">攻击力为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">30</span><span style="font-size:10.5pt;color:#231F17;">）对于</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">iceman,</span><span style="font-size:10.5pt;color:#231F17;">输出的生命值和攻击力应该是变化后的数值</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p class="MsoNormal">
<b><span style="font-family:&#34;color:#231F17;">13) </span></b><b><span style="color:#231F17;">司令部被占领</span></b><b><span style="font-family:&#34;color:#231F17;"></span></b> 
</p>
<p style="margin-left:36.0pt;">
<span style="font-size:10.5pt;color:#231F17;">输出样例：</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">003:10 blue headquarter was taken</span> 
</p>
<p class="MsoNormal">
<b><span style="font-family:&#34;color:#231F17;">14)</span></b><b><span style="color:#231F17;">司令部报告生命元数量</span></b><b><span style="font-family:&#34;color:#231F17;"></span></b> 
</p>
<p style="margin-left:36.0pt;">
<span style="font-size:10.5pt;font-family:&#34;color:#231F17;">000:50 100 elements in red
headquarter<span class="apple-converted-space"> </span><br/>
000:50 120 elements in blue headquarter<br/>
</span><span style="font-size:10.5pt;color:#231F17;">表示在</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">0</span><span style="font-size:10.5pt;color:#231F17;">点</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">50</span><span style="font-size:10.5pt;color:#231F17;">分，红方司令部有</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">100</span><span style="font-size:10.5pt;color:#231F17;">个生命元，蓝方有</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">120</span><span style="font-size:10.5pt;color:#231F17;">个</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p class="MsoNormal">
<b><span style="font-family:&#34;color:#231F17;">15)</span></b><b><span style="color:#231F17;">武士报告武器情况</span></b><b><span style="font-family:&#34;color:#231F17;"></span></b> 
</p>
<p style="margin-left:36.0pt;">
<span style="font-size:10.5pt;font-family:&#34;color:#231F17;">000:55 blue wolf 2 has
arrow(2),bomb,sword(23)<br/>
000:55 blue wolf 4 has no weapon<br/>
000:55 blue wolf 5 has sword(20)<br/>
</span><span style="font-size:10.5pt;color:#231F17;">表示在</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">0</span><span style="font-size:10.5pt;color:#231F17;">点</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">55</span><span style="font-size:10.5pt;color:#231F17;">分，蓝魔</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">2</span><span style="font-size:10.5pt;color:#231F17;">号武士</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">wolf</span><span style="font-size:10.5pt;color:#231F17;">有一支</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">arrow</span><span style="font-size:10.5pt;color:#231F17;">（这支</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">arrow</span><span style="font-size:10.5pt;color:#231F17;">还可以用</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">2</span><span style="font-size:10.5pt;color:#231F17;">次），一个</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">bomb</span><span style="font-size:10.5pt;color:#231F17;">，还有一支攻击力为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">23</span><span style="font-size:10.5pt;color:#231F17;">的</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">sword</span><span style="font-size:10.5pt;color:#231F17;">。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"><br/>
</span><span style="font-size:10.5pt;color:#231F17;">蓝魔</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">4</span><span style="font-size:10.5pt;color:#231F17;">号武士</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">wolf</span><span style="font-size:10.5pt;color:#231F17;">没武器。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"><br/>
</span><span style="font-size:10.5pt;color:#231F17;">蓝魔</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">5</span><span style="font-size:10.5pt;color:#231F17;">号武士</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">wolf</span><span style="font-size:10.5pt;color:#231F17;">有一支攻击力为</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">20</span><span style="font-size:10.5pt;color:#231F17;">的</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">sword</span><span style="font-size:10.5pt;color:#231F17;">。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"><br/>
</span><span style="font-size:10.5pt;color:#231F17;">交代武器情况时，次序依次是：</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">arrow,bomb,sword</span><span style="font-size:10.5pt;color:#231F17;">。如果没有某种武器，某种武器就不用提。报告时，先按从西向东的顺序所有的红武士报告，然后再从西向东所有的蓝武士报告。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">输出事件时：</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">首先按时间顺序输出；</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">同一时间发生的事件，按发生地点从西向东依次输出</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">. </span><span style="font-size:10.5pt;color:#231F17;">武士前进的事件</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">, </span><span style="font-size:10.5pt;color:#231F17;">算是发生在目的地。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">在一次战斗中有可能发生上面的</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> 6 </span><span style="font-size:10.5pt;color:#231F17;">至</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"> 11 </span><span style="font-size:10.5pt;color:#231F17;">号事件。这些事件都算同时发生，其时间就是战斗开始时间。一次战斗中的这些事件，序号小的应该先输出。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">两个武士同时抵达同一城市，则先输出红武士的前进事件，后输出蓝武士的。</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">显然，</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">13</span><span style="font-size:10.5pt;color:#231F17;">号事件发生之前的一瞬间一定发生了</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">12</span><span style="font-size:10.5pt;color:#231F17;">号事件。输出时，这两件事算同一时间发生，但是应先输出</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;">12</span><span style="font-size:10.5pt;color:#231F17;">号事件</span><span style="font-size:10.5pt;font-family:&#34;color:#231F17;"></span> 
</p>
<p>
<span style="font-size:10.5pt;color:#231F17;">虽然任何一方的司令部被占领之后，就不会有任何事情发生了。但和司令部被占领同时发生的事件，全都要输出。</span> 
</p>
<h3>
【输入格式】
</h3>
<p>
第一行是t,代表测试数据组数
</p>
<p>
每组样例共三行。
</p>
<p>
第一行，五个整数 M,N,R,K, T。其含义为：
</p>
<p>
每个司令部一开始都有M个生命元( 1 &lt;= M &lt;= 10000)
</p>
<p>
两个司令部之间一共有N个城市( 1 &lt;= N &lt;= 20 )
</p>
<p>
arrow的攻击力是R
</p>
<p>
lion每经过一场未能杀死敌人的战斗，忠诚度就降低K。
</p>
<p>
要求输出从0时0分开始，到时间T为止(包括T) 的所有事件。T以分钟为单位，0 &lt;= T &lt;= 5000
</p>
<p>
第二行：五个整数，依次是 dragon 、ninja、iceman、lion、wolf 的初始生命值。它们都大于0小于等于10000
</p>
<p>
第三行：五个整数，依次是 dragon 、ninja、iceman、lion、wolf 的攻击力。它们都大于0小于等于10000
</p>
<h3>
【输出格式】
</h3>
<p>
对每组数据，先输出一行：
</p>
<p>
Case n:
</p>
<p>
如对第一组数据就输出 Case1:
</p>
<p>
然后按恰当的顺序和格式输出到时间T为止发生的所有事件。每个事件都以事件发生的时间开头，时间格式是“时: 分”，“时”有三位，“分”有两位。
</p>
<h3>
【样例输入】
</h3>
<pre>1
20 1 10 10 1000
20 20 30 10 20
5 5 5 5 5
</pre>
<h3>
【样例输出】
</h3>
<pre>Case 1:
000:00 blue lion 1 born
Its loyalty is 10
000:10 blue lion 1 marched to city 1 with 10 elements and force 5
000:30 blue lion 1 earned 10 elements for his headquarter
000:50 20 elements in red headquarter
000:50 20 elements in blue headquarter
000:55 blue lion 1 has no weapon
001:00 blue dragon 2 born
Its morale is 0.00
001:10 blue lion 1 reached red headquarter with 10 elements and force 5
001:10 blue dragon 2 marched to city 1 with 20 elements and force 5
001:30 blue dragon 2 earned 10 elements for his headquarter
001:50 20 elements in red headquarter
001:50 10 elements in blue headquarter
001:55 blue lion 1 has no weapon
001:55 blue dragon 2 has arrow(3)
002:10 blue dragon 2 reached red headquarter with 20 elements and force 5
002:10 red headquarter was taken
</pre>
<h3>
【提示】
</h3>
<p>
听说你们喜欢大模拟
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://cxsjsx.openjudge.cn/2015warpractice/C/">Openjudge-程序设计实习</a> 
</p>
