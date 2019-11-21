<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>saffah<span style="">最近迷上了一种叫做“神犇的终极冲刺”（</span><span style="font-family: 'Lucida Console';">the Ultimate Rush of Shen-Bens</span><span style="">，简称</span><span style="font-family: 'Lucida Console';">URSB</span><span style="">）的游戏，其中最复杂的装备系统让玩家们很头疼，因为在浩如烟海的装备中找到真正适合自己的并不容易。</span><span style="font-family: 'Lucida Console';">saffah</span><span style="">决定编程解决这个问题。</span></p>
<p> </p>
<p>URSB<span style="">是一款即时战略类游戏，决定玩家输出能力的属性值主要有</span><span style="font-family: 'Lucida Console';">3</span><span style="">个：攻击力、攻击速度和暴击率。</span></p>
<p> </p>
<p>攻击力为一正整数（如果不是则向下舍去小数），代表着玩家每次攻击所能造成的伤害值，下限为<span style="font-family: 'Lucida Console';">1</span>；攻击速度为保留到<span style="font-family: 'Lucida Console';">3</span><span style="">位小数（也是</span>向下舍去）的正实数，代表着玩家每秒钟能够攻击的次数，下限为<span style="font-family: 'Lucida Console';">0.500</span><span style="">，上限为</span><span style="font-family: 'Lucida Console';">2.500</span><span style="">；暴击率为一个</span>自然数，单位为<span style="font-family: 'Lucida Console';">%</span>，代表着每次攻击有多少概率造成<span style="font-family: 'Lucida Console';">2</span><span style="">倍伤害，上限为</span><span style="font-family: 'Lucida Console';">100</span><span style="">。</span></p>
<p> </p>
<p>玩家的能力值便是在<span style="font-family: 'Lucida Console';">1</span><span style="">秒内攻击造成伤害的期望值，例如，攻击力为</span><span style="font-family: 'Lucida Console';">100</span><span style="">，攻击速度为</span><span style="font-family: 'Lucida Console';">2.000</span><span style="">，暴击率为</span><span style="font-family: 'Lucida Console';">50%</span><span style="">的玩家，每次攻击的期望伤害（</span>保留<span style="font-family: 'Lucida Console';">2</span><span style="">位小数</span>）是<span style="font-family: 'Lucida Console';">150.00</span><span style="">（即</span><span style="font-family: 'Lucida Console';">100+100</span><span style="">×</span><span style="font-family: 'Lucida Console';">0.50</span><span style="">），故能力值（</span>保留<span style="font-family: 'Lucida Console';">5</span><span style="">位小数</span>）为<span style="font-family: 'Lucida Console';">300.00000</span><span style="">（即</span><span style="font-family: 'Lucida Console';">150.00</span><span style="">×</span><span style="font-family: 'Lucida Console';">2.000</span><span style="">）。</span></p>
<p> </p>
<p>现在你身上没有任何装备，攻击力为<span style="font-family: 'Lucida Console';">ATK</span><span style="">，攻击速度为</span><span style="font-family: 'Lucida Console';">SPD</span><span style="">，暴击率为</span><span style="font-family: 'Lucida Console';">CRI</span><span style="">，拥有</span><span style="font-family: 'Lucida Console';">MC</span><span style="">个金钱。每种装备拥有一个价格</span><span style="font-family: 'Lucida Console';">M</span>i，购买后能够增加<span style="font-family: 'Lucida Console';">A</span>i点攻击力，并增加<span style="font-family: 'Lucida Console';">B</span>i%<span style="">的攻击力，增加</span><span style="font-family: 'Lucida Console';">C</span>i点暴击率，增加<span style="font-family: 'Lucida Console';">S</span>i%<span style="">的攻击速度。</span><span style="font-family: 'Lucida Console';">Ps</span><span style="">：</span><span style="font-family: 'Lucida Console';">A</span>i，<span style="font-family: 'Lucida Console';">B</span>i，<span style="font-family: 'Lucida Console';">C</span>i，<span style="font-family: 'Lucida Console';">S</span>i可能是负数。</p>
<p> </p>
<p>如果同时具有按点数增加攻击力与按百分比增加攻击力的效果，则先做加法再做乘法。例如，如果本身攻击力为<span style="font-family: 'Lucida Console';">100</span><span style="">，装备</span><span style="font-family: 'Lucida Console';">A</span><span style="">能够提供</span><span style="font-family: 'Lucida Console';">+18</span><span style="">点攻击力与</span><span style="font-family: 'Lucida Console';">+5%</span><span style="">攻击力，装备</span><span style="font-family: 'Lucida Console';">B</span><span style="">能够提供</span><span style="font-family: 'Lucida Console';">+20</span><span style="">攻击力与</span><span style="font-family: 'Lucida Console';">+12%</span><span style="">攻击力，则最终攻击力为</span><span style="font-family: 'Lucida Console';">(100+18+20)</span><span style="">×</span><span style="font-family: 'Lucida Console';">(1.00+0.05+0.12)=161.46</span><span style="">，但攻击力要向下舍去到整数，故应该为</span><span style="font-family: 'Lucida Console';">161</span><span style="">。</span></p>
<p> </p>
<p>如果两项与百分比有关的效果叠加，则以线性方式简单叠加，例如，未装装备时的攻击速度为1.500<span style="">，装备</span><span style="font-family: 'Lucida Console';">A</span><span style="">提供了</span><span style="font-family: 'Lucida Console';">+10%</span><span style="">攻击速度，装备</span><span style="font-family: 'Lucida Console';">B</span><span style="">提供了</span><span style="font-family: 'Lucida Console';">+20%</span><span style="">攻击速度，则最终攻击速度为</span><span style="font-family: 'Lucida Console';">1.500</span><span style="">×</span><span style="font-family: 'Lucida Console';">(1.00+0.10+0.20)=1.950</span><span style="">。</span></p>
<p> </p>
<p>在购买物品时能力值达到上限或下限时，不会对本身的能力值造成影响，例如，未装装备的暴击率为<span style="font-family: 'Lucida Console';">0%</span><span style="">，装备</span><span style="font-family: 'Lucida Console';">A</span><span style="">提供</span><span style="font-family: 'Lucida Console';">+6%</span><span style="">暴击率，装备</span><span style="font-family: 'Lucida Console';">B</span><span style="">提供</span><span style="font-family: 'Lucida Console';">-8%</span><span style="">暴击率，则无论是先买</span><span style="font-family: 'Lucida Console';">A</span><span style="">还是先买</span><span style="font-family: 'Lucida Console';">B</span><span style="">，最终的暴击率都为</span><span style="font-family: 'Lucida Console';">0%</span><span style="">，</span>不会因为先买<span style="font-family: 'Lucida Console';">B</span><span style="">降到</span><span style="font-family: 'Lucida Console';">0%</span><span style="">而再买</span><span style="font-family: 'Lucida Console';">A</span><span style="">升到</span><span style="font-family: 'Lucida Console';">6%</span><span style="">。</span></p>
<p> </p>
<p>一种装备可以购买多次并可以同时装备多个。有些装备需要通过合成得到，你需要先购买其“子装备”，然后消耗<span style="font-family: 'Lucida Console';">M</span>i的金钱并且让其“子装备”消失，方可得到这件装备。其子装备的列表记为<span style="font-family: 'Lucida Console';">Z</span>i。显然，没有任何两种装备互为子装备。</p>
<p> </p>
<p>现在的问题是，用这些<span style="font-family: 'Lucida Console';">MC</span><span style="">的金钱购买哪些装备，能够使自身的能力值最大。无须输出购买方案，只需输出最大能力值（保留</span><span style="font-family: 'Lucida Console';">5</span><span style="">位小数）。</span></p>
<p><span style=""><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行为<span style="font-family: 'Lucida Console';">4</span><span style="">个数，分别为</span><span style="font-family: 'Lucida Console';">ATK</span><span style="">，</span><span style="font-family: 'Lucida Console';">SPD</span><span style="">，</span><span style="font-family: 'Lucida Console';">CRI</span><span style="">，</span><span style="font-family: 'Lucida Console';">MC</span><span style="">。</span></p>
<p>第二行为<span style="font-family: 'Lucida Console';">1</span><span style="">个自然数</span><span style="font-family: 'Lucida Console';">V</span><span style="">，代表着装备的种类数。</span></p>
<p>接下来<span style="font-family: 'Lucida Console';">V</span><span style="">行中每行表示一个装备，其中第</span><span style="font-family: 'Lucida Console';">i+2</span><span style="">行中依次包含了正整数</span><span style="font-family: 'Lucida Console';">M</span>i，整数<span style="font-family: 'Lucida Console';">A</span>i，整数<span style="font-family: 'Lucida Console';">B</span>i，整数<span style="font-family: 'Lucida Console';">C</span>i，整数<span style="font-family: 'Lucida Console';">S</span>i，序列<span style="font-family: 'Lucida Console';">Z</span>i。其中<span style="font-family: 'Lucida Console';">Z</span>i的表示方法为：依次列出其子装备的序号，最后以<span style="font-family: 'Lucida Console';">0</span><span style="">结尾；如果这个装备没有子装备，则直接为一个</span><span style="font-family: 'Lucida Console';">0</span><span style="">。</span></p>
<p>数据保证，子装备永远在“父装备”之前出现。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件只有一行，包含一个保留<span style="font-family: 'Lucida Console';">5</span><span style="font-family: 宋体;">位小数的正实数，即最大能力值。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>Input1:</p>
<p>100 1.000 0 1000</p>
<p>2</p>
<p>200 10 0 0 0 0</p>
<p>100 30 0 0 0 1 1 0</p>
<p>Input2:</p>
<p>100 2.500 0 10000</p>
<p>1</p>
<p>700 50 0 0 -10 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Output1:</p>
<p>160.00000</p>
<p>Output2:</p>
<p>450.00000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例1的说明：</p>
<p>1<span style="">号装备价格为</span><span style="font-family: 'Lucida Console';">200</span><span style="">，增加</span><span style="font-family: 'Lucida Console';">10</span><span style="">攻击力，</span><span style="font-family: 'Lucida Console';">2</span><span style="">号装备需要两个</span><span style="font-family: 'Lucida Console';">1</span><span style="">号装备与</span><span style="font-family: 'Lucida Console';">100</span><span style="">金钱合成，增加</span><span style="font-family: 'Lucida Console';">30</span><span style="">攻击力。显然，最优方案为，先买</span><span style="font-family: 'Lucida Console';">4</span><span style="">个</span><span style="font-family: 'Lucida Console';">1</span><span style="">号装备花费</span><span style="font-family: 'Lucida Console';">800</span><span style="">金钱，然后再将其两两合成</span><span style="font-family: 'Lucida Console';">2</span><span style="">号装备，共能合成</span><span style="font-family: 'Lucida Console';">2</span><span style="">个，故增加</span><span style="font-family: 'Lucida Console';">60</span><span style="">攻击力，总攻击力为</span><span style="font-family: 'Lucida Console';">160</span><span style="">，故最大能力值为</span><span style="font-family: 'Lucida Console';">160.00000</span><span style="">。</span></p>
<p><span style="">样例2的说明：</span></p>
<p> </p>
<p>最优方案为购买<span style="font-family: 'Lucida Console';">4</span><span style="">个</span><span style="font-family: 'Lucida Console';">1</span><span style="">号装备，多买与少买都会使能力值降低。</span></p>
<p><span style=""><br></span></p>
<p> </p>
<p>对于<span style="font-family: 'Lucida Console';">100%</span><span style="">的数据，最大能力值≤</span><span style="font-family: 'Lucida Console';">16383.50000</span><span style="">，</span><span style="font-family: 'Lucida Console';">ATK</span><span style="">≥</span><span style="font-family: 'Lucida Console';">1</span><span style="">，</span><span style="font-family: 'Lucida Console';">0.500</span><span style="">≤</span><span style="font-family: 'Lucida Console';">SPD</span><span style="">≤</span><span style="font-family: 'Lucida Console';">2.500</span><span style="">，</span><span style="font-family: 'Lucida Console';">0</span><span style="">≤</span><span style="font-family: 'Lucida Console';">CRI</span><span style="">≤</span><span style="font-family: 'Lucida Console';">100,0</span><span style="">≤</span><span style="font-family: 'Lucida Console';">MC</span><span style="">≤</span><span style="font-family: 'Lucida Console';">2</span><span style="">×</span><span style="font-family: 'Lucida Console';">10</span>9，<span style="font-family: 'Lucida Console';">V</span><span style="">≤</span><span style="font-family: 'Lucida Console';">5</span><span style="">。</span></p>
<p> </p>
<p>对于20%<span style="">的数据，</span><span style="font-family: 'Lucida Console';">V</span><span style="">≤</span><span style="font-family: 'Lucida Console';">1</span><span style="">。</span></p>
<p> </p>
<p>以下条件中：①<span style="font-family: 'Lucida Console';">A</span>i，<span style="font-family: 'Lucida Console';">B</span>i，<span style="font-family: 'Lucida Console';">S</span>i≥<span style="font-family: 'Lucida Console';">0</span><span style="">，②</span><span style="font-family: 'Lucida Console';">CRI=C</span>i=0<span style="">，③没有任何一种装备拥有子装备；对于</span><span style="font-family: 'Lucida Console';">20%</span><span style="">的数据，至少满足以上</span><span style="font-family: 'Lucida Console';">3</span><span style="">条；对于</span><span style="font-family: 'Lucida Console';">50%</span><span style="">的数据，至少满足以上</span><span style="font-family: 'Lucida Console';">2</span><span style="">条；对于</span><span style="font-family: 'Lucida Console';">80%</span><span style="">的数据，至少满足以上</span><span style="font-family: 'Lucida Console';">1</span><span style="">条；对于</span><span style="font-family: 'Lucida Console';">100%</span><span style="">的数据，至少满足以上</span><span style="font-family: 'Lucida Console';">0</span><span style="">条。</span></p>
<p><span style=""><br></span></p>
</div>
</div>