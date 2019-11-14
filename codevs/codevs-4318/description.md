<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">LOI_M</span><span style="">是LOI大家庭里的一只神犇，然而他一直深爱着一款名叫Yo Gi Oh!的桌游。</span></p><p><span style="">    LOI_M</span><span style="">发现原来LOI里也有喜欢Yo Gi Oh的神犇—LOI_dc！于是LOI_M就与dc开始了游戏。</span></p><p><span style="">    LOI_imcy</span><span style="">想要知道LOI_M是否能赢，能赢得话，最少用几个回合，不能的话，最多能坚持几个回合。LOI_imcy已经事先得到了双方摸牌的规律(不要问我怎么知道的！)，LOI_M和LOI_dc的实力不相上下，他们都会采用最佳的方案出牌（最佳方案见“附”），也就是说，早已知道了摸牌顺序的LOI_imcy在比赛开始前就可以知道比赛的结果了，然而，因为LOI_imcy是个蒟蒻，他并不知道要如何得到结果，所以说他就把写程序的问题都扔给你了，</span></p><p><span style="">因为在比赛结束后才得到结果就没有意义了，所以LOI_imcy要求你在1S内得出结果（过了1S就比完了啊）！</span></p><p style=""><span style="">附：</span></p><p style="">Yo Gi Oh <span style="">是一款二人的回合制桌游，由于它的规则长达</span>25+P<span style="">，这里的规则做简化，具体如下：</span></p><p><br></p><p style=""><span style="">以下是对战场地（每人有</span>5<span style="">个卡片摆放的位置，每个位置上只能放一张卡片）</span></p><p style=""><span style="">每个人都有一个自己的卡组（就是一堆牌），每到自己的回合就必须抽一张牌。</span></p><p style=""><span style="">在游戏前先决定谁先出牌，然后每个人先各自在自己的牌堆里抽出</span>5<span style="">张牌（放入手中）</span></p><p style=""><span style="">已经抽到手里的牌成为手牌！</span></p><p style=""><span style="">手牌最多不能超过</span>6<span style="">张，超过</span>6<span style="">张时要在自己的回合即将结束时弃牌（一直弃到还剩</span>6<span style="">张）</span></p><p style=""><span style="">双方各有</span>8000LP</p><p style=""><span style="">一方</span>LP<span style="">归为</span>0<span style="">（小于</span>0<span style="">也算</span>0<span style="">）时，视作</span>lose</p><p style=""><span style="">一个回合的流程：</span></p><p style=""><span style="">抽牌</span><span style="font-family: Wingdings;">à</span><span style="">加入手牌</span><span style="font-family: Wingdings;">à</span><span style="">召唤一张</span>monster<span style="">到场上的一个自己的位置</span><span style="font-family: Wingdings;">à</span><span style="">用自己场上的任意数量</span>monster<span style="">对对方场上的任意数量</span>monster<span style="">进行</span>attack<span style="">（但每个</span>monster<span style="">只能进行一次</span>attack<span style="">）</span><span style="font-family: Wingdings;">à</span><span style="">回合结束</span></p><p style=""><span style="">注：</span></p><p style="">       <span style="">一回合只能召唤一张</span>monster<span style="">，</span>LOI_M<span style="">和</span>LOI_dc<span style="">每次都会选择手卡中最佳的</span>monster<span style="">（</span>monster<span style="">的攻击比较：优先考虑</span>monster<span style="">的</span>atk<span style="">，</span>atk<span style="">高的</span>monster<span style="">将破坏</span>atk<span style="">低的</span>monster<span style="">，</span>atk<span style="">相等的</span>monster<span style="">考虑星级，星级高的</span>monster<span style="">将破坏星级低的</span>monster<span style="">）</span></p><p style="">Monster<span style="">被破坏后，被破坏的一方的</span>LP<span style="">减去</span>atk(<span style="">较高</span>)-atk(<span style="">较低</span>)<span style="">，被破坏</span>monster<span style="">原本的摆放位置被清空，即可以重新摆放</span>monster<span style="">。</span></p><p style=""><span style="">对于</span>LOI_M<span style="">和</span>LOI_dc<span style="">，他们的每次出牌都是有规律的：</span></p><p style="">       <span style="">每回合总是选择手卡中最优的一只</span>monster<span style="">召唤（毕竟一回合只能召唤一次）。</span></p><p style="">       <span style="">每次进行</span>attack<span style="">阶段时，</span>LOI_M<span style="">和</span>LOI_dc<span style="">会先计算下用自己的</span>atk<span style="">（</span>max<span style="">）的</span>monster<span style="">攻击对方</span>atk<span style="">（</span>min<span style="">）的</span>monster<span style="">，在用</span>atk<span style="">（次</span>max<span style="">）攻击</span>atk<span style="">（次</span>min<span style="">）</span>……<span style="">是否能扣除对方的</span>LP<span style="">至</span>0<span style="">，能的话当然直接</span>atk<span style="">啦。</span></p><p style="">       <span style="">不能的话，</span> LOI_M<span style="">和</span>LOI_dc<span style="">会用自己最优</span>..<span style="">次优</span>…<span style="">的</span>monster<span style="">攻击这只</span>monster<span style="">所能破坏的对方的最优的</span>monster<span style="">，也就是说，当双方的两只</span>monster<span style="">的</span>atk<span style="">和星级相同的话，他们不会相互攻击。</span>(<span style="">双方只会用</span>monster<span style="">攻击</span>monster<span style="">，最优的定义是</span>atk<span style="">最高的同时星级最高</span>)</p><p style=""><span style="">默认</span>LOI_M<span style="">先出牌</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行一个N表示一共进行N个回合</span></p><p style=""><span style="">接下来为10张卡片（格式见下），先是LOI_M和的5张初始手牌后是LOI_dc的初始手牌5张</span></p><p style=""><span style="">接下来2N行，每两行分别是LOI_M和LOI_dc所摸的卡片。</span></p><p style=""><span style="">怪兽卡格式如下</span></p><p style=""><span style="">x atk</span></p><p style=""><span style="">表示卡的种类是monster  x为卡片的星级  atk为卡片的攻击力</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:28px"><span style="font-family:宋体">如果能赢，输出</span>win<span style="font-family:宋体">后加上进行的回合数</span></p><p style="text-indent:28px"><span style="font-family:宋体">如果会输，输出</span>lose<span style="font-family:宋体">后加上进行的回合数</span></p><p style="text-indent:28px"><span style="font-family:宋体">这里的回合是指每人的一个回合算一个回合</span></p><p style="text-indent:28px"><span style="font-family:宋体">如果未能决出胜负，输出</span>both are baka!</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="">4</p><p style="">5 2000</p><p style="">5 2000</p><p style="">5 1000</p><p style="">4 2000</p><p style="">3 2000</p><p style="">6 2000</p><p style="">6 2000</p><p style="">7 2000</p><p style="">3 4000</p><p style="">2 4000</p><p style="">1 0</p><p style="">1 0</p><p style="">1 0</p><p style="">1 0</p><p style="">1 0</p><p style="">1 0</p><p style="">1 0</p><p style="">1 0</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">lose 8</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Courier New';">100%</span><span style="">的数据：</span><span style="font-family: 'Courier New';"> 50&lt;n&lt;100</span></p><p style=""><span style="font-family: 'Courier New';">           0&lt;</span><span style="">星级</span><span style="font-family: 'Courier New';">&lt;13</span></p><p style=""><span style="font-family: 'Courier New';">           -1&lt;atk&lt;20000</span></p><p style=""><br></p>
</div>
</div>