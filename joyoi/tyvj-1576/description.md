# 

 
 # 题目描述 
在你面前有n级台阶。一个合法的走楼梯方案要满足：<BR>第一，你必须先上楼梯，到达某级后连续地下楼梯，直到返回0级。（即开始下楼梯后不能再上楼梯）<BR>第二，每次上下楼梯只能走1级或2级。<BR>第三，由于楼梯只有n级，你不能上到n级以上的位置，也不能下到0级以下的位置。<BR>问共有多少个不同的走楼梯方案。特别地，在0级站着不动也算一种方案。<BR> 

 
 # 输入格式 
一行两个正整数n和m。 

 
 # 输出格式 
一行一个整数，表示n级台阶有多少种合法的走楼梯方案，答案对m取模。 

 
 # 提示 
对于30%的数据，n&lt;=10000；<BR>对于100%的数据，n&lt;=10^17，m&lt;=2*10^9。<BR> 
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
<tr><td>样例一
2 10007

样例二
3 14</td><td>样例一
6

样例二
1
</td></tr></table>
