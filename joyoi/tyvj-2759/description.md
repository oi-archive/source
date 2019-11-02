# 

 
 # 题目描述 
<p>
	棒球是一项冲斥着统计学的运动。这么多统计有什么好处？它们可能能够帮助预测比赛的结果。<br>	一场棒球比赛包括9局。如果9局之后比赛仍是平局，则进行加时赛，直到比分不再是平局为止。每一局分为上下两个半局，每一个半局中一个队进攻，另一个队防守。客队先进攻，主队后进攻。因此如果第9局上半局结束时如果主队领先，则比赛将不再进行下去，因为主队必胜了。<br>	赛前，每一支队伍将提交一份击球顺序。在每一个半局中，攻方的选手按照击球顺序顺次击球，第一局中的第一个击球的选手是击球顺序中的第一个，第二个击球的是击球顺序中的第二个……之后每一局中第一个击球的选手是上一局最后一个击球的选手在击球顺序表中的下一个选手（最后一名选手的下一个是第一名选手）。<br>	当一个选手成功击球时，他可以跑入一垒，已经在垒位中的选手顺次前进一位（垒位包括本垒，一垒，二垒，三垒）（真实比赛中可以一次跑多个垒位，但这里我们不予考虑），而位于三垒的选手可以跑回本垒，并得到一分，这时，他将回到板凳，排到这局比赛击球序列的最后，等待他的下一次击球。每一个半局将持续进行直到攻方有3名击球手出局。每一次击球失败被算作一次出局，这名选手将不再在这一局中出场（但是不影响他在下一局中继续出场）。<br>	还有一种特殊的规则，一名选手可以选择在击球时牺牲自己。如果他成功了，他自己出局但是所有在垒位上的选手前进一位；如果他失败了，他就出局了。考虑到如果本方如果已经有2人出局，则击球手即使牺牲自己也没有意义，因此每个选手只有在本方二垒有人且无人出局或是本方三垒有人且最多一人出局的时候才会尝试牺牲自己。<br>	这里，我们根据以往比赛统计出了每一个选手的击球成功率与牺牲成功率（在0到1之间），下面请你根据这些数据和比赛规则模拟一场棒球比赛。模拟过程中需要用到随机函数，请使用以下的生成器：<br>X(n+1)=(X(n)*25173+13849) mod 65536<br>其中x(n)是当前的随机数，x(n+1)是新产生的随机数。每一场比赛前，请设定随机种子x(0)=1，比赛中用到的第一个随机数为x(1)，第二个随机数为x(2)……击球成功被定义为随机数/65536<=击球成功率，牺牲成功也有类似定义。<br>	在一场比赛中间，请不要重新设定随机种子。<br></p> 

 
 # 输入格式 
<p>
	输入文件分别用10行介绍了客队与主队的信息，其中第一行为队名，接下来9行为9名参赛选手的姓名，击球成功率，牺牲成功率，用空格隔开。选手按照击球顺序排列。你可以假定任意一场比赛不会超过200局。</p> 

 
 # 输出格式 
<p>
首先输出比赛的主客队的名称：<br><visiting> vs. <home><br>之后输出一行空行。<br>对于每一局比赛，顺次输出每一个成功击球和成功得分的选手和队名，使用以下的格式：<br>Inning <x>:<br>Hits:<br><player1> <team><br><player2> <team><br>Runs:<br><player3> <team><br><player4> <team><br>其中player使用17位场宽，team使用16位场宽。（参见样例）<br>如果没有人成功击球或得分，输出一行”none”(不包括引号)<br>之后输出一行空行。<br>最后输出比赛的总结，使用以下格式：<br>End of Game:<br>  <visiting> <x> runs, <x> hits<br>  <home> <x> runs, <x> hits<br>其中两个队名使用17位场宽。<br><br></p> 

 
 # 提示 
<p>
Rangers vs. BlueJays<br><br>Inning 1:<br>Hits:<br>             Hill        BlueJays<br>          Overbay        BlueJays<br>            Adams        BlueJays<br><br>Runs:<br>  none<br><br>Inning 2:<br>Hits:<br>  none<br><br>Runs:<br>  none<br><br>Inning 3:<br>Hits:<br>      Catalanotto         Rangers<br>            Wells        BlueJays<br>             Hill        BlueJays<br>            Adams        BlueJays<br><br>Runs:<br>            Wells        BlueJays<br><br>Inning 4:<br>Hits:<br>          Kinsler         Rangers<br><br>Runs:<br>  none<br><br>Inning 5:<br>Hits:<br>      Catalanotto         Rangers<br><br>Runs:<br>  none<br><br>Inning 6:<br>Hits:<br>             Sosa         Rangers<br>            Laird         Rangers<br>             Rios        BlueJays<br><br>Runs:<br>  none<br><br>Inning 7:<br>Hits:<br>        Wilkerson         Rangers<br>         Teixeira         Rangers<br>           Stairs        BlueJays<br><br>Runs:<br>  none<br><br>Inning 8:<br>Hits:<br>  none<br><br>Runs:<br>  none<br><br>Inning 9:<br>Hits:<br>  none<br><br>Runs:<br>  none<br><br>End of Game:<br>          Rangers 0 runs, 7 hits<br>         BlueJays 1 runs, 8 hits<br></p> 
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
<tr><td>Rangers
Young .213 .523
Kinsler .207 .602
Sosa .254 .300
Laird .220 .432
Byrd .206 .749
Wilkerson .236 .508
Catalanotto .272 .483
Teixeira .297 .573
Saltalamacchia .243 .632
BlueJays
Wells .378 .502
Hill .276 .544
Overbay .372 .694
McDonald .373 .618
Adams .320 .690
Rios .300 .450
Johnson .379 .559
Stairs .302 .621
Zaun .346 .515

</td><td>[样例输出1]
0
[样例输出2]
3
[样例输出3]
2</td></tr></table>
