# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;小A成功地在紧要关头逃离了神奇山洞，同时他也感觉自己rp大增。现在他站在了一座阴森森的城堡前，这就是江湖人称“死亡城堡”的魔域。为了rp，小A毅然决然地走了进去……<BR>&nbsp;&nbsp;&nbsp;&nbsp;不愧是死亡城堡，险境丛生，小A又是一个大意的人，XXX他掉进了一个陷阱。<BR>&nbsp;&nbsp;&nbsp;&nbsp;这是一个n*n的矩阵陷阱，矩阵的每一个小格内都有一个魔鬼，并且这些魔鬼属于不同的种类，种类数不超过p（1&lt;=p&lt;=n*n,有可能存在某一种魔鬼不在矩阵中出现）。每一种魔鬼i都有一种战斗力c[i]，不同的魔鬼战斗力不同。打魔鬼也不是那么好玩的，需要消耗小A相应数量的战斗力。当小A打败了一个魔鬼后，此种类型的魔鬼就会全部消失，这样小A就可以自由的在这种类型的格子间传送，不会消耗任何的战斗力。每到一个格子，小A可以向紧邻的上下左右四个格子进发去打魔鬼，直到走出矩阵。小A开始郁闷了，他怎样才能从矩阵的第一行出发，顺利的走到矩阵的最后一行呢？所谓的顺利，就是使自己的战斗力大于0。<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在小A求助于聪明的你，希望你能求出小A顺利走出陷阱时剩余的最大战斗力。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行：两个整数n，p;<BR>&nbsp;&nbsp;&nbsp;&nbsp;第2到n+1行是一个n*n的矩阵，矩阵中不同的数字代表不同的格子类型；<BR>&nbsp;&nbsp;&nbsp;&nbsp;第n+2行是p个数，代表p种魔鬼的战斗力；<BR>&nbsp;&nbsp;&nbsp;&nbsp;最后一行:小A的初始战斗力值W。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;一个整数表示小A顺利走出陷阱时剩余的最大战斗力，如果小A走不出陷阱就输出'Dangerous!'; 

 
 # 提示 
对于30%的数据：1&lt;=n&lt;=50<BR>对于100%的数据：1&lt;=n&lt;=500;w&lt;=maxlongint<BR> 
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
<tr><td>样例一：
3 3
1 2 1
2 1 2
1 1 1
1 2 5
7
样例二：
3 3
1 2 1
2 1 2
3 3 3
1 2 5
2
</td><td>样例一：
6
样例二：
Dangerous!</td></tr></table>
