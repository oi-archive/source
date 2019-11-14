# 

 
 # 题目描述 
<p>
《星际争霸2》全面公测啦！Farmer John和Bessie正在测试中——在1v1的战役中使用一些不同的策略来对抗对方的部队。星际争霸2的游戏目标就是在战役中打败你对手的军队。每个选手的军队都在战役中拼杀。一支军队由若干3种不同类型的单位所组成，不同单位有着不同的由正实数表示的，且不被选手所知道的力量值：cattlebruisers 的力量是S1，cow templars 的力量是S2，ultracows的力量是S3。唯一提供的信息是，没有一个单位的力量值超过另一个单位力量值的100倍。一支军队的总力量值，是其中各自单独的单位的力量值的总和。比如一支军队除了其他单位有23个cattlebruisers，那么这支军队单独从cattlebruisers就能获得23*S1的力量值。当两支对立的军队在战役中厮杀，有着更高力量值的军队将获得胜利。如果两支军队的力量值恰好相同，那么将随机产生一个获胜方。Farmer John 和 Bessie 进行了 N (0 <= N <= 300) 局的“测试战役”。在第 i 局测试战役中，Farmer John 有 J1_i 个 cattlebruisers，J2_i 个 cow templars 以及 J3_i 个 ultracows(0 <= J1_i + J2_i + J3_i <= 1,000)。相似的，Bessie的军队有 B1_i 个 cattlebruisers，B2_i 个 cow templars 以及 B3_i 个 ultracows (0 <= B1_i + B2_i + B3_i <= 1,000)。当他们的军队战斗结束后，FJ 和 Bessie 将胜者以一个单独的“胜利字母” V_i 记录下来："J"表示 Farmer John 赢得了战役；"B" 表示 Bessie 获胜了。虽然这些结果是他们唯一所拥有的信息，但是他们希望预测一些额外的战役的结果——如果告知他们两支对立军队的组成。尽管，可能对于一些比赛他们是无法确定到底哪一方一定能获胜的。给出已经结束的 N 场测试战役的结果，写一个程序来确定(如果可能的话)M (1 <=M <=2,000)场额外战役的获胜方。<br>所有给出的测试战役的结果都是正确的。至少存在一种合法的力量值的取值符合这些结果。为了示范一下力量值函数的计算，考虑如下战役，并且有 S1=9.0, S2=7.0, S3=4.0 (当然，Farmer John 和 Bessie 都是不知道这3个数值的)：<br><img border="0" src="/source/joyoi/tyvj-2647/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjY0Ny9wcm9ibGVtc19pbWFnZXMvMzEwMi8xODI5LmpwZw==.jpg"> <br></p> 

 
 # 输入格式 
<p>
* Line 1: 两个用空格隔开的整数；N和 M<br>* Lines 2..N+1: 第 i+1 行用7个用空格分开的数据来描述第i场测试战役：V_i, J1_i, J2_i,<br>J3_i,B1_i, B2_i, 和 B3_i——第一个是胜利字母，接下来是6个整数<br>* Lines N+2..N+M+1: 第i+N+1行描述了第i场额外战役，这里给出6个用空格分开的整数<br>J1_i, J2_i, J3_i, B1_i, B2_i, 和 B3_i<br><br><br></p> 

 
 # 输出格式 
<p>
* Lines 1..M: 第i包含第i场额外战役的结果："J"表示Farmer John一定能赢，"B"表示Bessie一<br>定能赢，"U"表示不确定——也就是不可能利用给出的信息推断出谁一定能获胜。<br><br></p> 

 
 # 提示 
<p>
一开始的两场战役已经在题目中给出过解释了。最后一场战役是不能利用已有信息推断出结果的。<br>具体来说，对于 S_1=9.0, S_2=7.0, S_3=4.0 和 S_1=12.0, S_2=20.0, S_3=10.0 <br>这两组不同的数值都符合输入信息，但是却能使的最后一场测试战役产生不同的结果。<br></p> 
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
<tr><td>3 3
J 6 5 4 5 4 7
B 5 4 2 3 5 5
J 9 0 10 8 2 7
6 6 4 5 4 7
9 0 10 8 2 6
3 4 8 4 4 6

</td><td>J
J
U

</td></tr></table>
