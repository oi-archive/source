<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　某RPG游戏中，最后一战是主角单挑Boss，将其简化后如下：<br/>
　　主角的气血值上限为<i>HP</i>，魔法值上限为<i>MP</i>，愤怒值上限为<i>SP</i>；Boss仅有气血值，其上限为<i>M</i>。<br/>
　　现在共有<i>N</i>回合，每回合都是主角先行动，主角可做如下选择之一：<br/>
　　1.      普通攻击：减少对方<i>X</i>的气血值，并增加自身<i>D<sub>SP</sub></i>的愤怒值。（不超过上限）<br/>
　　2.      法术攻击：共有<i>N</i><sub>1</sub>种法术，第<i>i</i>种消耗<i>B<sub>i</sub></i>的魔法值，减少对方<i>Y<sub>i</sub></i>的气血值。（使用时要保证<i>MP</i>不小于<i>B<sub>i</sub></i>）<br/>
　　3.      特技攻击：共有<i>N</i><sub>2</sub>种特技，第<i>i</i>种消耗<i>C<sub>i</sub></i>的愤怒值，减少对方<i>Z<sub>i</sub></i>的气血值。（使用时要保证<i>SP</i>不小于<i>C<sub>i</sub></i>）<br/>
　　4.      使用HP药水：增加自身<i>D<sub>HP</sub></i>的气血值。（不超过上限）<br/>
　　5.      使用MP药水：增加自身<i>D<sub>MP</sub></i>的魔法值。（不超过上限）<br/>
　　之后Boss会攻击主角，在第<i>i</i>回合减少主角<i>A<sub>i</sub></i>的气血值。<br/>
　　刚开始时气血值，魔法值，愤怒值都是满的。当气血值小于等于0时死亡。<br/>
　　如果主角能在这<i>N</i>个回合内杀死Boss，那么先输出“Yes”，之后在同一行输出最早能在第几回合杀死Boss。（用一个空格隔开）<br/>
　　如果主角一定会被Boss杀死，那么输出“No”。<br/>
　　其它情况，输出“Tie”。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含一个整数T，为测试数据组数。<br/>
　　接下来T部分，每部分按如下规则输入：<br/>
　　第一行九个整数<i>N, M, HP, MP, SP, D<sub>HP</sub>, D<sub>MP</sub>, D<sub>SP</sub>, X</i>。<br/>
　　第二行<i>N</i>个整数<i>A<sub>i</sub></i>。<br/>
　　第三行第一个整数<i>N</i><sub>1</sub>，接下来包含<i>N</i><sub>1</sub>对整数<i>B<sub>i</sub></i>, <i>Y<sub>i</sub></i>。<br/>
　　第四行第一个整数<i>N</i><sub>2</sub>，接下来包含<i>N</i><sub>2</sub>对整数<i>C<sub>i</sub>, Z<sub>i</sub></i>。</div>
# 输出格式

<div class="pdcont">　　输出共包含T行，每行依次对应输出一个答案。</div>
# 样例输入

<div class="pddata">2<br/>
5 100 100 100 100 50 50 50 20<br/>
50 50 30 30 30<br/>
1 100 40<br/>
1 100 40<br/>
5 100 100 100 100 50 50 50 10<br/>
50 50 30 30 30<br/>
1 100 40<br/>
1 100 40</div>
# 样例输出

<div class="pddata">Yes 4<br/>
Tie</div>
# 样例说明

<div class="pdcont">　　对于第一个样例，主角的策略是：第一回合法术攻击，第二回合使用HP药水，第三回合特技攻击，第四回合普通攻击。</div>
# 数据规模和约定

<div class="pdcont">　　对于10%的数据：<i>N</i> ≤ 10，<i>N</i><sub>1 </sub>= <i>N</i><sub>2 </sub>= 0。<br/>
　　对于30%的数据：<i>N</i> ≤ 10，<i>N</i><sub>1</sub><i> = N</i><sub>2</sub><i> = </i>1。<br/>
　　对于60%的数据：<i>N</i> ≤ 100，M ≤ 10000，<i>HP,MP,SP</i> ≤ 70。<br/>
　　对于100%的数据：1 ≤ <i>N </i>≤ 1000，1 ≤ <i>M</i> ≤ 1000000，1 ≤ <i>HP,MP,SP</i> ≤ 1000，<i>N</i><sub>1</sub><i>,N</i><sub>2</sub> ≤ 10，<i>D<sub>HP</sub>,A<sub>i</sub></i> ≤ <i>HP</i>，<i>D<sub>MP</sub>,B<sub>i</sub> </i>≤ <i>MP</i>，<i>D<sub>SP</sub>,C<sub>i</sub></i> ≤ SP，<i>X,Y<sub>i</sub>,Z<sub>i</sub></i> ≤ 10000，1 ≤ T ≤ 10。</div>

</div>