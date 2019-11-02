<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>《猪国杀》是一种多猪牌类回合制游戏，一共有三种角色：主猪，忠猪，反猪。每局游戏主猪有且只有一只，忠猪和反猪可以有多只，每只猪扮演一种角色。</p><p>游戏目的：</p><p>主猪（<span style="font-family: 'Times New Roman';">MP</span><span style="">）：自己存活的情况下消灭所有的反猪。</span></p><p>忠猪（<span style="font-family: 'Times New Roman';">ZP</span><span style="">）：不惜一切保护主猪，胜利条件与主猪相同。</span></p><p>反猪（<span style="font-family: 'Times New Roman';">AP</span><span style="">）：杀死主猪。</span></p><p>游戏过程：</p><p>游戏开始时候，每个玩家手里都会有<span style="font-family: 'Times New Roman';">4</span><span style="">张牌，且体力上限和初始体力都是</span><span style="font-family: 'Times New Roman';">4</span><span style="">。</span></p><p>开始游戏时，从主猪开始，按照逆时针方向（数据中就是按照编号从<span style="font-family: 'Times New Roman';">1,2,3..n,1..</span><span style="">的顺序）依次行动。</span></p><p>每个玩家自己的回合可以分为<span style="font-family: 'Times New Roman';">4</span><span style="">个阶段：</span></p><p>◎摸牌阶段：从牌堆顶部摸两张牌，依次放到手牌的最右边；</p><p>◎出牌阶段：你可以使用<span style="font-family: 'Times New Roman';">0</span><span style="">张到任意张牌，每次使用牌的时候都使用最靠左的能够使用的牌。当然，要满足如下规则：</span></p><p>1.<span style="">如果没有猪哥连弩，每个出牌阶段只能使用一次&amp;ldquo;杀&amp;rdquo;来攻击；</span></p><p>2.<span style="">任何牌被使用后被弃置（武器是装备上）；</span></p><p>被弃置的牌以后都不能再用，即与游戏无关；</p><p>各种牌介绍：</p><p>每张手牌用一个字母表示，字母代表牌的种类。</p><p>◎基本牌：</p><p>『桃<span style="font-family: 'Times New Roman';">(P)</span><span style="">』：在自己的回合内，如果自己的体力值不等于体力上限，那么使用一个桃可以为自己补充一点体力，否则不能使用桃；桃只能对自己使用；在自己的回合外，如果自己的血变为</span><span style="font-family: 'Times New Roman';">0</span><span style="">或者更低，那么也可以使用；</span></p><p>『杀<span style="font-family: 'Times New Roman';">(K)</span><span style="">』：在自己的回合内，对攻击范围内除自己以外的一名角色使用。如果没有被『闪』抵消，则造成</span><span style="font-family: 'Times New Roman';">1</span><span style="">点伤害。无论有无武器，杀的攻击范围都是</span><span style="font-family: 'Times New Roman';">1</span><span style="">；</span></p><p>『闪<span style="font-family: 'Times New Roman';">(D)</span><span style="">』：当你受到杀的攻击时，可以弃置一张闪来抵消杀的效果；</span> </p><p>◎锦囊牌：</p><p>『决斗<span style="font-family: 'Times New Roman';">(F)</span><span style="">』：出牌阶段，对除自己以外任意一名角色使用，由目标角色先开始，自己和目标角色轮流弃置一张杀，首先没有杀可弃的一方受到</span><span style="font-family: 'Times New Roman';">1</span><span style="">点伤害，另一方视为此伤害的来源；</span></p><p>『南猪入侵<span style="font-family: 'Times New Roman';">(N)</span><span style="">』：出牌阶段，对除你以外所有角色使用，按逆时针顺序从使用者下家开始依次结算，除非弃置一张杀，否则受到</span><span style="font-family: 'Times New Roman';">1</span><span style="">点伤害；</span></p><p>    『万箭齐发<span style="font-family: 'Times New Roman';">(W)</span><span style="">』：和南猪入侵类似，不过要弃置的不是杀而是闪；</span></p><p>『无懈可击<span style="font-family: 'Times New Roman';">(J)</span><span style="">』：在目标锦囊生效前抵消其效果。每次有一张锦囊即将生效时，从使用这张锦囊的猪开始，按照逆时针顺序，依次得到使用无懈可击的机会；</span></p><p>效果：用于决斗时，决斗无效并弃置；用于南猪入侵或万箭齐发时，当结算到某个角色时才能使用，当前角色不需弃置牌并且不会受到伤害（仅对一个角色产生效果）；用于无懈可击时，成为目标的无懈可击被无效。</p><p>◎装备牌：</p><p>     『猪哥连弩<span style="font-family: 'Times New Roman';">(Z)</span><span style="">』：武器，攻击范围</span><span style="font-family: 'Times New Roman';">1</span><span style="">，出牌阶段你可以使用任意张杀；</span></p><p>同一时刻最多只能装一个武器；如果先前已经有了一把武器，那么之后再装武器的话，会弃置以前的武器来装现在的武器；</p><p>特殊事件及概念解释：</p><p>◎伤害来源：杀、南猪入侵、万箭齐发的伤害来源均是使用该牌的猪，决斗的伤害来源如上； </p><p>◎距离：两只猪的距离定义为沿着逆时针方向间隔的猪数＋<span style="font-family: 'Times New Roman';">1</span><span style="">。即初始时</span><span style="font-family: 'Times New Roman';">1</span><span style="">和</span><span style="font-family: 'Times New Roman';">2</span><span style="">的距离为</span><span style="font-family: 'Times New Roman';">1</span><span style="">，但是</span><span style="font-family: 'Times New Roman';">2</span><span style="">和</span><span style="font-family: 'Times New Roman';">1</span><span style="">的距离就是</span><span style="font-family: 'Times New Roman';">n-1</span><span style="">。注意一个角色的死亡会导致一些猪距离的改变；</span></p><p>◎玩家死亡：如果该玩家的体力降到<span style="font-family: 'Times New Roman';">0</span><span style="">或者更低，并且自己手中没有足够的桃使得自己的体力值回到</span><span style="font-family: 'Times New Roman';">1</span><span style="">，那么就死亡了，死亡后所有的牌（装备区，手牌区）被弃置；</span></p><p>◎奖励与惩罚：反猪死亡时，最后一个伤害来源处（即使是反猪）立即摸三张牌。忠猪死亡时，如果最后一个伤害来源是主猪，那么主猪所有装备牌、手牌被弃置； </p><p>◎注意，一旦达成胜利条件，游戏立刻结束，因此即使会摸<span style="font-family: 'Times New Roman';">3</span><span style="">张牌或者还有牌可以用也不用执行了。</span></p><p>现在，我们已经知道每只猪的角色、手牌，还有牌堆初始情况，并且假设每个角色会按照如下的行为准则进行游戏，你需要做的就是告诉小猪<span style="font-family: 'Times New Roman';">iPig</span><span style="">最后的结果。</span></p><p>几种行为：</p><p>◎献殷勤：使用无懈可击挡下南猪入侵、万箭齐发、决斗；使用无懈可击抵消表敌意；</p><p>◎表敌意：对某个角色使用杀、决斗；使用无懈可击抵消献殷勤；</p><p>◎跳忠：即通过行动表示自己是忠猪。跳忠行动就是对主猪或对某只已经跳忠的猪献殷勤，或者对某只已经跳反的猪表敌意；</p><p>◎跳反：即通过行动表示自己是反猪。跳反行动就是对主猪或对某只已经跳忠的猪表敌意，或者对某只已经跳反的猪献殷勤；</p><p>忠猪不会跳反，反猪也不会跳忠；不管是忠猪还是反猪，能够跳必然跳；</p><p>行动准则：</p><p>共性：每个角色如果手里有桃且生命值未满，那么必然吃掉；有南猪入侵、万箭齐发、必然使用；有装备必然装上；受到杀时，有闪必然弃置；响应南猪入侵或者万箭齐发时候，有杀<span style="font-family: 'Times New Roman';">/</span><span style="">闪必然弃置；不会对未表明身份的猪献殷勤（包括自己）；</span></p><p>特性：</p><p>◎主猪：主猪会认为没有跳身份，且用南猪入侵<span style="font-family: 'Times New Roman';">/</span><span style="">万箭齐发对自己造成伤害的猪是&amp;ldquo;类反猪&amp;rdquo;（没伤害到不算，注意&amp;ldquo;类反猪&amp;rdquo;并没有表明身份），如果之后跳了，那么主猪会重新认识这只猪；对于每种表敌意的方式，对逆时针方向能够执行到的第一只&amp;ldquo;类反猪&amp;rdquo;或者已跳反猪表；如果没有，那么就不表敌意；决斗时会不遗余力弃置杀；如果能对已经跳忠的猪或自己献殷勤，那么一定献；如果能够对已经跳反的猪表敌意，那么一定表；</span></p><p>◎忠猪：对于每种表敌意的方式，对逆时针方向能够执行到的第一只已经跳反的猪表，如果没有，那么就不表敌意；决斗时，如果对方是主猪，那么不会弃置杀，否则，会不遗余力弃置杀；如果有机会对主猪或者已经跳忠的猪献殷勤，那么一定献；</p><p>◎反猪：对于每种表敌意的方式，如果有机会则对主猪表，否则，对逆时针方向能够执行到的第一只已经跳忠的猪表，如果没有，那么就不表敌意；决斗时会不遗余力弃置杀；如果有机会对已经跳反的猪献殷勤，那么一定献；</p><p>限于<span style="font-family: 'Times New Roman';">iPig</span><span style="">只会用</span><span style="font-family: 'Times New Roman';">P++</span><span style="">语言写</span><span style="font-family: 'Times New Roman';">A + B</span><span style="">，他请你用</span><span style="font-family: 'Times New Roman';">Pigcal(Pascal)</span><span style="">、</span><span style="font-family: 'Times New Roman';">P(C)</span><span style="">或</span><span style="font-family: 'Times New Roman';">P++(C++)</span><span style="">语言来帮他预测最后的结果。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行包含两个正整数<span style="font-family: 'Times New Roman';">n(2 &lt;= n &lt;= 5) </span><span style="">和</span><span style="font-family: 'Times New Roman';">m( m &lt;= 2000)</span><span style="">，分别代表玩家数和牌堆中牌的数量。数据保证牌的数量够用。</span></p><p>接下来<span style="font-family: 'Times New Roman';">n</span><span style="">行，每行</span><span style="font-family: 'Times New Roman';">5</span><span style="">个字符串，依次表示对第</span><span style="font-family: 'Times New Roman';">i</span><span style="">只猪的角色和初始</span><span style="font-family: 'Times New Roman';">4</span><span style="">张手牌描述。编号为</span><span style="font-family: 'Times New Roman';">1</span><span style="">的肯定是主猪。</span></p><p>再接下来一行，一共<span style="font-family: 'Times New Roman';">m</span><span style="">个字符串，按照从牌堆顶部到牌堆底部的顺序描述每张牌。</span></p><p>所有的相邻的两个字符串都严格用<span style="font-family: 'Times New Roman';">1</span><span style="">个空格隔开，行尾没有多余空格。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出数据第一行包含一个字符串代表游戏结果。如果是主猪胜利，那么输出&amp;ldquo;<span style="font-family: &#39;Times New Roman&#39;;">MP</span><span style="font-family: 宋体;">&amp;rdquo;，否则输出&amp;ldquo;</span><span style="font-family: &#39;Times New Roman&#39;;">FP</span><span style="font-family: 宋体;">&amp;rdquo;。数据保证游戏总会结束。</span></p><p class="p0">接下来<span style="font-family: &#39;Times New Roman&#39;;">n</span><span style="font-family: 宋体;">行，第</span><span style="font-family: &#39;Times New Roman&#39;;">i</span><span style="font-family: 宋体;">行是对第</span><span style="font-family: &#39;Times New Roman&#39;;">i</span><span style="font-family: 宋体;">只猪的手牌描述（注意只需要输出手牌），按照手牌从左往右的顺序输出，相邻两张牌用一个空格隔开，行末尾没有多余空格。如果这只猪已阵亡，那么只要输出&amp;ldquo;</span><span style="font-family: &#39;Times New Roman&#39;;">DEAD</span><span style="font-family: 宋体;">&amp;rdquo;即可。注意如果要输出手牌而没有手牌的话，那么只需输出一个空行。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">3 10</span></p><p>MP D D F F</p><p>ZP N N N D</p><p>FP J J J J</p><p>F F D D J J F F K D</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>FP</p><p>DEAD</p><p>DEAD</p><p>J J J J J D</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例<span style="font-family: 'Times New Roman';">1</span><span style="">说明：第一回合主猪没有目标可以表敌意；接下来忠猪使用了</span><span style="font-family: 'Times New Roman';">3</span><span style="">张南猪入侵，主猪掉了</span><span style="font-family: 'Times New Roman';">3</span><span style="">点体力，并认为该角色为类反猪，</span><span style="font-family: 'Times New Roman';">3</span><span style="">号角色尽管手里有无懈可击，但是因为自己未表明身份，所以同样不能对自己用，乖乖掉</span><span style="font-family: 'Times New Roman';">3</span><span style="">点体力；下一回合反猪无牌可出；接下来主猪对着类反猪爆发，使用</span><span style="font-family: 'Times New Roman';">4</span><span style="">张决斗，忠猪死亡，结果主猪弃掉所有牌；下来反猪摸到一张杀直接杀死主猪获胜。</span></p><p><span style=""><br></span></p><p> </p><p>数据说明：一共<span style="font-family: 'Times New Roman';">20</span><span style="">组测试数据，每个点</span><span style="font-family: 'Times New Roman';">5</span><span style="">分。</span><span style="font-family: 'Times New Roman';">10%</span><span style="">的数据没有锦囊牌，另外</span><span style="font-family: 'Times New Roman';">20%</span><span style="">的数据没有无懈可击。</span></p><p><span style=""><br></span></p>
</div>
</div>