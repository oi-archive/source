# 

 
 # 题目描述 
<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">这个夏天，与众不同。QQ空间也引入了最近流行的社区交互类游戏《开心农场》。自然而然地，Chroi也成为了众多农场主的一员。可是Chroi整个暑假忙于OI，没什么时间照顾农场，这就需要你的帮助了。他可以告诉你他每天那些时间可以上线，你要做的就是告诉他该天最多可赚多少钱（为了降低难度，假设腾讯每天晚上0:00清空还没收获的作物，而且由于Chroi的农场等级比较低，所以只能种单季作物（就是只能收获一次的））。</p>

<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">在开心农场中，每个用户都有一定数目的土地，每次上线可以做的事是在土地上摘果实、卖果实、种下种子，每块土地上只能种一种作物，每块土地各自独立。</p>

<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">假设Chroi每次只能上线1秒，他能在瞬间做完所有他想做的事，所以你的程序要在一秒内得出结果。而且如果Chroi在一天的最后时刻上线，那他此刻做的事算第二天的。（比如时间为24，那他在24时刻做的事算第二天的0时刻做的。）</p> 

 
 # 输入格式 
<p><span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">输入文件包含多行，第一行有四个正整数n,m,t,k，分别表示Chroi的农场中有n块地，共有m种作物可以选择，一天的时间t，有k个时刻Chroi可以上线。</span><br style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;" />
<span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">接下来的m行每行输入三个正整数，第一个数字表示种子价格，第二个数字表示种子成熟时间（小于t），第三个数字表示成熟后果实的售价。再次提示，这些都是整数。</span><br style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;" />
<span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">再接下来的一行有k个自然数，保证该整数为0,1,2...t-1中的一个，为Chroi可以上线的时间。这k个自然数不会重复。</span><br style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;" />
<span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">输入文件到此结束。</span></p> 

 
 # 输出格式 
<p><span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">输出文件只有一个整数，表示Chroi每天可以获得的最大金钱数。</span></p> 

 
 # 提示 
<h2>样例数据说明</h2>

<h3>样例1(输出0)</h3>

<p>种第一种作物还亏钱，不如不种。</p>

<h3>样例2(输出180)</h3>

<p>共种了3次第一种作物，每次种6块土地，收获了3次，每次收获6块土地，最后一次上线18的时候只收获，不种植（之后不能再收获，再种植没时间收获，只能亏钱。）</p>

<p>&nbsp;</p>

<h2>数据范围</h2>

<p>对于30%的数据，0&lt;n&lt;=10,0&lt;m&lt;=50,0&lt;k&lt;=t&lt;=50。</p>

<p>对于50%的数据，0&lt;n&lt;=20,0&lt;m&lt;=500,0&lt;k&lt;=t&lt;=500。</p>

<p><span style="line-height: 1.6em;">对于100%的数据，0&lt;n&lt;=50,0&lt;m&lt;=3000,0&lt;k&lt;=t&lt;=3000，最后输出的数&lt;maxlongint。</span></p>

<p>&nbsp;</p>

<h2>版权</h2>

<p><span style="line-height: 1.6em;">此题目来源于HOI&nbsp;2009。本用户并不拥有该资料版权。如果无意侵犯了您的权益，请私信管理员或本用户。管理员接到通知后请删题，以避免不必要的纠纷，谢谢！</span></p> 
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
<tr><td>6 3 24 4
10 6 20
15 3 18
11 3 19
0 6 12 18</td><td>180</td></tr><tr><td>1 1 24 2
10 6 5
0 6</td><td>0</td></tr></table>
