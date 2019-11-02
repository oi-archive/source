# 

 
 # 题目描述 
118号工厂是世界唯一秘密提炼锎的化工厂，由于提炼锎的难度非常高，技术不是十分完善，所以工厂生产的锎成品可能会有3种不同的纯度，A：100%，B：1%，C：0.01%，为了出售方便，必须把不同纯度的成品分开装箱，装箱员grant第1次顺序从流水线上取10个成品（如果一共不足10个，则全部取出），以后每一次把手中某种纯度的成品放进相应的箱子，然后再从流水线上顺序取一些成品，使手中保持10个成品（如果把剩下的全部取出不足10个，则全部取出），如果所有的成品都装进了箱子，那么grant的任务就完成了。<BR>由于装箱是件非常累的事情，grant希望他能够以最少的装箱次数来完成他的任务，现在他请你编个程序帮助他。<BR> 

 
 # 输入格式 
第1行为n（1&lt;=n&lt;=100），为成品的数量<BR>以后n行，每行为一个大写字母A，B或C，表示成品的纯度。<BR> 

 
 # 输出格式 
仅一行，为grant需要的最少的装箱次数。 
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
<tr><td>11
A
B
C
A
B
C
A
B
C
A
B
</td><td>3
</td></tr></table>
