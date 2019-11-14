# 

 
 # 题目背景 
<p>&nbsp;&nbsp;&nbsp;&nbsp;有一个单机五子棋游戏&hellip;&hellip;</p> 

 
 # 题目描述 
<p>&nbsp;&nbsp;&nbsp;&nbsp;A写了一个五子棋单机游戏，他和电脑玩每局都赢，他想知道如果电脑和电脑下会有什么结果。<br />
&nbsp;&nbsp;&nbsp;&nbsp;五子棋自然是2个人玩的。由于这个单机游戏是在DOS下运行的，分别用O、X表示两种棋，.表示空位置。<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;棋盘边缘视为敌方棋子。<br />
&nbsp;&nbsp;&nbsp;&nbsp;电脑的下棋的方法是：<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;定义1：五格结构：<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;一、规定五格结构某方下的棋坐标(x,y)。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;这个五格结构就是连续的五格（四个方向），这五格中应当全是空着的或一方的棋子（除了(x,y)外），五子结构的棋子方就是这些棋子的下棋方。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;无论是什么方向的五格，为了方便，我们都把这个五格和它向两边伸长出的两个位置横放。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;二、规定优先级a：（&nbsp;在下完棋(x,y)之后&nbsp;）<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在下棋方与五格结构的棋子方相同时：{<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;①自己连5颗棋时a=1<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;②自己连4颗棋时a=3<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;③自己连3颗棋时a=5<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;④自己连2颗棋时a=7<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;⑤自己连1颗棋时a=9<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;不同时：{<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;①封住他人即将连5颗棋时a=2<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;②封住他人即将连4颗棋时a=4<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;③封住他人即将连3颗棋时a=6<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;④封住他人即将连2颗棋时a=8<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;⑤封住他人即将连1颗棋时a=10<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（&nbsp;封住敌人连的棋可以看做将这个位置(x,y)&nbsp;下了一个敌方的棋&nbsp;）<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;三、规定阻碍数b：（&nbsp;在下完棋(x,y)之后，(x,y)看做是五格结构的棋子方&nbsp;）<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;l是最左边的棋子，r是最右边的棋子。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;①规定l与r之间的空着的位置个数为p。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;②对于12l*r34，&ldquo;*&rdquo;表示l与r之间的若干个位置。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;【若位置2是对方的棋子则k1=3，<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;不然若位置1是对方的棋子且位置2为空则k1=1，<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;其它情况k1=0。<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;若位置3是对方的棋子则k2=3，<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;不然若位置4是对方的棋子且位置3为空则k2=1，<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;其它情况k2=0。】<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;③b=k1+k2+p.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;定义五格结构函数compare(&nbsp;W&nbsp;,&nbsp;V&nbsp;)&nbsp;其中&nbsp;W&nbsp;,&nbsp;V&nbsp;是五子结构。（设Wa为五子结构W的优先级，以此类推）<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;这个函数返回哪个五格结构更有效，<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;当&nbsp;(&nbsp;Wa&nbsp;&lt;&nbsp;Va&nbsp;)&nbsp;或&nbsp;(&nbsp;(&nbsp;Wa&nbsp;=&nbsp;Va&nbsp;)&nbsp;且&nbsp;(&nbsp;Wb&nbsp;&lt;=&nbsp;Vb&nbsp;)&nbsp;)&nbsp;时&nbsp;：&nbsp;返回真<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;否则返回假。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;定义2：我方目的：<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;一个棋子下在(x,y)上的时候，它在某个方向，产生的对进攻的效果叫做我方目的。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;它就是一个下棋方与五格结构的棋子方相同的五子结构E，它满足以下两点：<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;①下棋坐标为(x,y)&nbsp;，&nbsp;方向是我方目的的方向。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;②对于所有满足条件①的五子结构R，满足&nbsp;compare(&nbsp;E&nbsp;,&nbsp;R&nbsp;)&nbsp;为真。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;如果没有一个五子结构满足条件①，这个我方目的优先级为oo,阻碍数为oo（oo即无穷大）（就是说，我方目的是没有任何目的）<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;定义3：敌方目的：<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;一个棋子下在(x,y)上的时候，它在某个方向，产生的防守进攻的效果叫做我方目的。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;它就是一个下棋方与五格结构的棋子方相同的五子结构E，它满足以下两点：<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;①下棋坐标为(x,y)&nbsp;，&nbsp;方向是敌方目的的方向。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;②对于所有满足条件①的五子结构R，满足&nbsp;compare(&nbsp;E&nbsp;,&nbsp;R&nbsp;)&nbsp;为真。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;如果没有一个五子结构满足条件①，这个敌方目为优先级为oo,阻碍数为oo（oo即无穷大）（就是说，敌方目的是没有任何目的）<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;定义4：目的：敌方目的与我方目的的统称。<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;定义5：效果：{<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;当一个棋子下在(x,y)时它的目的所组成的集合S。（一般情况下，它应当包含8个五子结构，即4个我方目的，和4个敌方目的）<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;效果就是有序的五子结构串T：集合S按五子结构的作用不上升排列。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;定义效果函数better(&nbsp;H&nbsp;,&nbsp;G&nbsp;)&nbsp;其中H,G是效果&nbsp;（设Ht为效果H串中第t个目的，这是一个五子结构）<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;这个函数返回哪个五格结构效果更好，<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;当有存在一个i&nbsp;(&nbsp;1&nbsp;&lt;=&nbsp;i&nbsp;&lt;=&nbsp;8&nbsp;)<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;使得&nbsp;（所有{Hj&nbsp;=&nbsp;Gj（完全相同）}&nbsp;且&nbsp;compare(&nbsp;Hi&nbsp;,&nbsp;Gi&nbsp;)&nbsp;返回真）&nbsp;(&nbsp;1&nbsp;&lt;=&nbsp;j&nbsp;&lt;&nbsp;i&nbsp;)<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;当两个效果完全相同且效果H下棋的坐标比G下棋的坐标要上或同样高度坐标更右时，返回真。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;其余情况返回假。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;定义6：最佳下法：所有下法的效果（better函数）最好的一个。<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;电脑每一步会按照当前的最优下法的坐标下棋。<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;现在给出当前局面，请你告诉A会有什么结果（当前轮到O)。</p> 

 
 # 输入格式 
<p>&nbsp;&nbsp;&nbsp;&nbsp;第一行一个数n，表示棋盘上有n个棋子。<br />
&nbsp;&nbsp;&nbsp;&nbsp;接下来n行，每行三个正整数x,y,z，<br />
&nbsp;&nbsp;&nbsp;&nbsp;z&nbsp;=&nbsp;1&nbsp;时&nbsp;表示第x行第y列的棋子为O<br />
&nbsp;&nbsp;&nbsp;&nbsp;z&nbsp;=&nbsp;2&nbsp;时&nbsp;表示第x行第y列的棋子为X<br />
&nbsp;&nbsp;&nbsp;&nbsp;其余格子里自然都是.了。</p> 

 
 # 输出格式 
<p>&nbsp;&nbsp;&nbsp;&nbsp;刚开始局面不用输出。<br />
&nbsp;&nbsp;&nbsp;&nbsp;之后每下一步输出一个19&times;19的矩阵，&ldquo;.&rdquo;表示位置为空，&ldquo;X&rdquo;、&ldquo;O&rdquo;表示棋子。输出后空行。<br />
&nbsp;&nbsp;&nbsp;&nbsp;在最后一行，如果X赢，输出&ldquo;X&nbsp;win!&rdquo;；如果O赢，输出&ldquo;O&nbsp;win!&rdquo;；如果平局，输出&ldquo;Draw!&rdquo;。</p> 

 
 # 提示 
<p>&nbsp;&nbsp;给出的数据都是合法的，而且不会开始就有5个棋子相连。<br />
&nbsp;&nbsp;样例中O下左边不如下右边。<br />
&nbsp;&nbsp;0&nbsp;&lt;=&nbsp;n&nbsp;&lt;=&nbsp;361<br />
&nbsp;&nbsp;EZ_lzh&nbsp;&amp;&nbsp;EZ_gx&nbsp;讨论后制定。</p> 
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
<tr><td>4
1 5 2
1 2 2
1 3 2
1 4 2
</td><td>.XXXXO.............
...................
...................
...................
...................
...................
...................
...................
...................
...................
...................
...................
...................
...................
...................
...................
...................
...................
...................

XXXXXO.............
...................
...................
...................
...................
...................
...................
...................
...................
...................
...................
...................
...................
...................
...................
...................
...................
...................
...................

X win!
</td></tr></table>
