# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;你正在玩你最喜欢的电子游戏，&nbsp;并且刚刚进入一个奖励关。&nbsp;在这个奖励关里，<BR>系统将依次随机抛出k次宝物，每次你都可以选择吃或者不吃（必须在抛出下一<BR>个宝物之前做出选择，且现在决定不吃的宝物以后也不能再吃）&nbsp;。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;宝物一共有n种，系统每次抛出这n种宝物的概率都相同且相互独立。也就<BR>是说，即使前&nbsp;k-1&nbsp;次系统都抛出宝物&nbsp;1（这种情况是有可能出现的，尽管概率非<BR>常小）&nbsp;，第k次抛出各个宝物的概率依然均为1/n。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;获取第&nbsp;i&nbsp;种宝物将得到&nbsp;Pi分，但并不是每种宝物都是可以随意获取的。第&nbsp;i<BR>种宝物有一个前提宝物集合Si。只有当Si中所有宝物都至少吃过一次，才能吃第<BR>i&nbsp;种宝物（如果系统抛出了一个目前不能吃的宝物，相当于白白的损失了一次机<BR>会）&nbsp;。注意，Pi&nbsp;可以是负数，但如果它是很多高分宝物的前提，损失短期利益而<BR>吃掉这个负分宝物将获得更大的长期利益。&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;假设你采取最优策略，平均情况你一共能在奖励关得到多少分值？&nbsp; 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行为两个正整数k&nbsp;和n，即宝物的数量和种类。以下n行分别描述一种<BR>宝物，&nbsp;其中第一个整数代表分值，随后的整数依次代表该宝物的各个前提宝物（各<BR>宝物编号为1到n）&nbsp;，以0结尾。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;输出一个实数，保留六位小数，即在最优策略下平均情况的得分。 

 
 # 提示 
1&nbsp;&lt;=&nbsp;k&nbsp;&lt;=&nbsp;100,&nbsp;1&nbsp;&lt;=&nbsp;n&nbsp;&lt;=&nbsp;15，分值为[-10^6,10^6]内的整数SCOI2008&nbsp;day1&nbsp;T1 
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
<tr><td>样例1：

1 2 
1 0 
2 0 

样例2：

6 6 
12 2 3 4 5 0 
15 5 0 
-2 2 4 5 0 
-11 2 5 0 
5 0 
1 2 4 5 0
</td><td>样例1：

1.500000

样例2:

10.023470</td></tr></table>
