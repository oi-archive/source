# 

 
 # 题目背景 
Freda：aya，文明5时间太长了啊。<BR>Rainbow：是呀是呀，要不然玩点别的吧~<BR>Freda：捉迷藏怎么样？<BR>Rainbow：听起来不错的说lala~<BR>Freda：不过光捉迷藏太没意思了呀&gt;.&lt;<BR>Rainbow：那就在捉迷藏的同时加上寻找宝藏吧~~~ 

 
 # 题目描述 
题目叙述<BR>	Freda既要拿到宝藏，又要躲避Rainbow的拦截。游戏在Rainbow的城堡一层进行，城堡一层为一个N*M的矩形，由N*M个1*1的单元格组成。每个格子可能是如下5种情况：Freda现在的位置；Rainbow现在的位置；宝藏的位置；空地；障碍物。其中空地可以通过，障碍物则不能通过。Freda和Rainbow每次都只能向上下左右四个方向中的一个方向移动一格，也可以不移动，每一步都是Freda先移动，Rainbow后移动。当Freda与Rainbow处于同一行或同一列且中间没有障碍物阻隔时，Freda就被Rainbow发现了，此时Rainbow获胜。然而，如果Freda顺利拿到宝藏并且没有被Rainbow发现（包括最后拿到宝藏的那一步），则Freda获胜。<BR>	众所周知，Freda和Rainbow都拥有城堡一层的地图，而且它们都是很聪明的，所以它们在寻宝和拦截的过程中都会采取最聪明的方式。Freda想请你帮帮它，看看它是否能够安全的拿到宝藏，取得胜利呢？ 

 
 # 输入格式 
输入格式<BR>	每个测试点包含若干组测试数据，对于每组数据：<BR>	第1行两个正整数N,M。接下来N行，每行M个字符，为如下5种之一：“F”表示Freda的位置；“R”表示Rainbow的位置；“T”表示宝藏的位置；“.”表示空地；“I”表示障碍物。 

 
 # 输出格式 
输出格式<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于每组测试数据，如果Freda可以安全拿到宝藏，输出一行“YES”（不含引号），否则输出一行“NO”（不含引号）。 

 
 # 提示 
数据范围与约定<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于50%的数据，1&lt;=N,M&lt;=200<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于100%的数据，1&lt;=N	,M&lt;=700，每个测试点测试数据组数不超过5.From&nbsp;-&nbsp;This_poet<BR>Contact&nbsp;me&nbsp;-&nbsp;This_poet@126.com/Freda.RD.Shi@gmail.com<BR>This_poet's&nbsp;Blog&nbsp;-&nbsp;http://thispoet.blogcn.com 
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
<tr><td>输入样例
2 3
.FT
RII
5 7
F.....R
..I....
..IIIII
.......
...T...</td><td>输出样例
NO
YES</td></tr></table>
