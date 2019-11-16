# 

 
 # 题目描述 
Freda和rainbow是超自然之界学校(Preternatural&nbsp;Kingdom&nbsp;University，简称PKU)魔法学院的学生。为了展示新学的魔法，Ta们决定进行一场对弈~~~<br>起初Freda面前有n堆魔法珠，其中第i堆有ai颗。Freda和rainbow可以轮流进行以下操作：<br>1.选择n堆中魔法珠数量大于1的任意一堆。记该堆魔法珠的数量为p，p有b1、b2……bm这m个小于p的约数。<br>2.施展魔法把这一堆魔法珠变成m堆，每堆各有b1、b2……bm颗魔法珠。<br>3.选择这m堆中的一堆魔法珠，施展魔法令其消失。<br>注意一次操作过后，魔法珠的堆数会增加m-2，各堆中魔法珠数量的总和可能会发生变化。<br>当轮到某人操作时，如果每堆中魔法珠的数量均为1，那么ta就输了。<br>Freda和rainbow都采取最好的策略，从Freda开始。请你预测一下，谁能获胜呢？<br> 

 
 # 输入格式 
本题仅有一个测试点，包含多组数据，以EOF结尾。<br>每组数据的第一行包含一个整数n。<br>第二行包含n个整数ai。<br> 

 
 # 输出格式 
对于每组数据，在两人均采取最佳策略的前提下，若Freda能获胜，输出freda；若Rainbow能获胜，输出rainbow。<br> 

 
 # 提示 
1&lt;=n&lt;=100,1&lt;=ai&lt;=1000<br>感谢zanoes提供出题思路<br> 
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
<tr><td>3
2 2 2
3
1 3 5
</td><td>freda
rainbow
</td></tr></table>
