# 

 
 # 题目描述 
小x正在销魂地玩魔兽<BR>他正控制着死亡骑士和n个食尸鬼(编号1～n)去打猎<BR><BR>死亡骑士有个魔法，叫做“死亡缠绕”，可以给食尸鬼补充HP<BR>战斗过程中敌人会对食尸鬼实施攻击，食尸鬼的HP会减少<BR><BR>小x希望随时知道自己部队的情况，即HP值第k多的食尸鬼有多少HP，以便决定如何施放魔法<BR>请同学们帮助他:)<BR><BR>小x向你发出3种信号：（下划线在输入数据中表现为空格）<BR>A_i_a表示敌军向第i个食尸鬼发出了攻击，并使第i个食尸鬼损失了a点HP，如果它的HP&lt;=0,那么这个食尸鬼就死了(Undead也是要死的……)。<BR>敌军不会攻击一个已死的食尸鬼。<BR>C_i_a&nbsp;表示死亡骑士向第i个食尸鬼放出了死亡缠绕，并使其增加了a点HP。<BR>HP值没有上限。<BR>死亡骑士不会向一个已死的食尸鬼发出死亡缠绕<BR>Q_k&nbsp;&nbsp;表示小x向你发出询问 

 
 # 输入格式 
第一行，一个正整数&nbsp;n<BR>以后n个整数&nbsp;表示n个食尸鬼的初始HP值<BR>接着一个正整数m<BR>以下m行&nbsp;每行一个小x发出的信号 

 
 # 输出格式 
对于小x的每个询问，输出HP第k多的食尸鬼有多少HP，如果食尸鬼总数不足k个，输出-1。每个一行数。<BR>最后一行输出一个数：战斗结束后剩余的食尸鬼数 

 
 # 提示 
40%的数据&nbsp;&nbsp;n&lt;=3000&nbsp;&nbsp;m&lt;=5000<BR>70%的数据&nbsp;&nbsp;n&lt;=8000&nbsp;&nbsp;m&lt;=10000<BR>100%的数据&nbsp;&nbsp;n&lt;=30000&nbsp;&nbsp;m&lt;=50000<BR>食尸鬼HP没有上限<BR>数据保证任意时刻食尸鬼的HP值在longint范围内<BR>数据保证A和C命令中的食尸鬼是活着的<BR>输入数据中没有多余空格、换行 
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
<tr><td>5
1 2 3
4 5
10
Q 2
A 4 6
C 1 4
Q 2
A 2 1
A 3 3
A 1 3
Q 4
C 2 10
Q 1
</td><td>4
5
-1
11
3
</td></tr></table>
