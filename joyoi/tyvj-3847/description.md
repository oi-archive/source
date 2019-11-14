# 

 
 # 题目背景 
<p>LOI_M是LOI大家庭里的一只神犇，然而他一直深爱着一款名叫Yo&nbsp;Gi&nbsp;Oh!的桌游。</p>

<p>LOI_M发现原来LOI里也有喜欢Yo&nbsp;Gi&nbsp;Oh的神犇&mdash;LOI_dc！于是LOI_M就与dc开始了游戏。</p> 

 
 # 题目描述 
<p style="line-height: 20.7999992370605px;">&nbsp;&nbsp;&nbsp;&nbsp;LOI_imcy想要知道LOI_M是否能赢，能赢得话，最少用几个回合，不能的话，最多能坚持几个回合。LOI_imcy已经事先得到了双方摸牌的规律(不要问我怎么知道的！)，LOI_M和LOI_dc的实力不相上下，他们都会采用最佳的方案出牌（最佳方案见&ldquo;附&rdquo;），也就是说，早已知道了摸牌顺序的LOI_imcy在比赛开始前就可以知道比赛的结果了，然而，因为LOI_imcy是个蒟蒻，他并不知道要如何得到结果，所以说他就把写程序的问题都扔给你了，</p>

<p style="line-height: 20.7999992370605px;">&nbsp;&nbsp;&nbsp;因为在比赛结束后才得到结果就没有意义了，所以LOI_imcy要求你在1S内得出结果（过了1S就比完了啊）！</p>

<p style="line-height: 20.7999992370605px;">附：</p>

<p style="line-height: 20.7999992370605px;">&nbsp;&nbsp;&nbsp;Yo&nbsp;Gi&nbsp;Oh&nbsp;是一款二人的回合制桌游，由于它的规则长达25+P，这里的规则做简化，具体如下<span style="line-height: 20.7999992370605px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&darr;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;LOI_M&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&darr;&nbsp;</span></p>

<table border="1" cellpadding="1" cellspacing="1" style="line-height: 20.7999992370605px; height: 100px; width: 500px;">
	<tbody>
		<tr>
			<td>&nbsp;</td>
			<td>&nbsp;</td>
			<td>&nbsp;</td>
			<td>&nbsp;</td>
			<td>&nbsp;</td>
		</tr>
		<tr>
			<td>&nbsp;</td>
			<td>&nbsp;</td>
			<td>&nbsp;</td>
			<td>&nbsp;</td>
			<td>&nbsp;</td>
		</tr>
	</tbody>
</table>

<p style="line-height: 20.7999992370605px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&uarr;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;LOI_dc&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&uarr;</p>

<p style="line-height: 20.7999992370605px;">以上是对战场地（每人有5个卡片摆放的位置，每个位置上只能放一张卡片）</p>

<p style="line-height: 20.7999992370605px;">每个人都有一个自己的卡组（就是一堆牌），每到自己的回合就必须抽一张牌。</p>

<p style="line-height: 20.7999992370605px;">在游戏前先决定谁先出牌，然后每个人先各自在自己的牌堆里抽出5张牌（放入手中）</p>

<p style="line-height: 20.7999992370605px;">已经抽到手里的牌成为手牌！</p>

<p style="line-height: 20.7999992370605px;">手牌最多不能超过6张，超过6张时要在自己的回合即将结束时弃牌（一直弃到还剩6张）</p>

<p style="line-height: 20.7999992370605px;">双方各有8000LP</p>

<p style="line-height: 20.7999992370605px;">一方LP归为0（小于0也算0）时，视作lose</p>

<p style="line-height: 20.7999992370605px;">一个回合的流程：</p>

<p style="line-height: 20.7999992370605px;">抽牌-&gt;加入手牌-&gt;召唤一张monster到场上的一个自己的位置-&gt;用自己场上的任意数量monster对对方场上的任意数量monster进行attack（但每个monster只能进行一次attack）&nbsp;-&gt;回合结束</p>

<p style="line-height: 20.7999992370605px;">注：</p>

<p style="line-height: 20.7999992370605px;">&nbsp;&nbsp;一回合只能召唤一张monster，LOI_M和LOI_dc每次都会选择手卡中最佳的monster（monster的攻击比较：优先考虑monster的atk，atk高的monster将破坏atk低的monster，atk相等的monster考虑星级，星级高的monster将破坏星级低的monster）</p>

<p style="line-height: 20.7999992370605px;">Monster被破坏后，被破坏的一方的LP减去atk(较高)-atk(较低)，被破坏monster原本的摆放位置被清空，即可以重新摆放monster。</p>

<p style="line-height: 20.7999992370605px;">对于LOI_M和LOI_dc，他们的每次出牌都是有规律的：</p>

<p style="line-height: 20.7999992370605px;">&nbsp;&nbsp;&nbsp;&nbsp;每回合总是选择手卡中最优的一只monster召唤（毕竟一回合只能召唤一次）。</p>

<p style="line-height: 20.7999992370605px;">&nbsp;&nbsp;&nbsp;&nbsp;每次进行attack阶段时，LOI_M和LOI_dc会先计算下用自己的atk（max）的monster攻击对方atk（min）的monster，在用atk（次max）攻击atk（次min）&hellip;&hellip;是否能扣除对方的LP至0，能的话当然直接atk啦。</p>

<p style="line-height: 20.7999992370605px;">&nbsp;&nbsp;&nbsp;&nbsp;不能的话，&nbsp;LOI_M和LOI_dc会用自己最优..次优&hellip;的monster攻击这只monster所能破坏的对方的最优的monster，也就是说，当双方的两只monster的atk和星级相同的话，他们不会相互攻击。(双方只会用monster攻击monster，不存在monster直接攻击玩家的情况，最优的定义是atk最高的同时星级最高)</p>

<p style="line-height: 20.7999992370605px;">默认LOI_M先出牌</p> 

 
 # 输入格式 
<p style="line-height: 20.7999992370605px;">第一行一个N表示一共进行N个回合</p>

<p style="line-height: 20.7999992370605px;">接下来为10张卡片（格式见下），先是LOI_M和的5张初始手牌后是LOI_dc的初始手牌5张</p>

<p style="line-height: 20.7999992370605px;">接下来2N行，每两行分别是LOI_M和LOI_dc所摸的卡片。</p>

<p style="line-height: 20.7999992370605px;">怪兽卡格式如下</p>

<p style="line-height: 20.7999992370605px;">x&nbsp;atk</p>

<p style="line-height: 20.7999992370605px;">x为卡片的星级&nbsp;&nbsp;atk为卡片的攻击力</p> 

 
 # 输出格式 
<p style="line-height: 20.7999992370605px;">如果LOI_M会赢，输出win后加上进行的回合数</p>

<p style="line-height: 20.7999992370605px;">如果LOI_M会输，输出lose后加上进行的回合数</p>

<p style="line-height: 20.7999992370605px;">这里的回合是指每人的一个回合算一个回合</p>

<p style="line-height: 20.7999992370605px;">如果未能决出胜负，输出&quot;both&nbsp;are&nbsp;baka!&quot;（无引号）</p> 

 
 # 提示 
<p style="line-height: 20.7999992370605px;">【数据限制】</p>

<p style="line-height: 20.7999992370605px;">&nbsp;&nbsp;100%的数据：&nbsp;&nbsp;50&lt;n&lt;100</p>

<p style="line-height: 20.7999992370605px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0&lt;星级&lt;13</p>

<p style="line-height: 20.7999992370605px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-1&lt;atk&lt;20000</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>1
1 0
1 0
1 0
1 0
1 0
1 12450 
1 0 
1 0 
10 0 
5 0 
1 0
1 0
</td><td>lose 2</td></tr><tr><td>4
5 2000
5 2000
5 1000
4 2000
3 2000
6 2000
6 2000
7 2000
3 4000
2 4000
1 0
1 0
1 0
1 0
1 0
1 0
1 0
1 0</td><td>lose 8</td></tr></table>
