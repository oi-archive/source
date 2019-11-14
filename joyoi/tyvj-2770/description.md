# 

 
 # 题目描述 
<p>
对不同的值进行升序排列，指的是根据“小于号”提供的信息，将各个值从小到大进行排列。比如，如果告诉你A < B, B < C 和C < D，那么升序排列为：A，B，C，D。本问题中，给你一系列的小于关系（格式为A < B），你的任务是判断该序列能否全部排序。 </p> 

 
 # 输入格式 
<p>
输入包括多组测试数据。每组测试数据以两个正整数n和m开始。n表示序列中值的个数，满足满足2 <= n <= 26。要被排序的字母总是位于26个大写字母中的前n个位置。m表示提供的小于关系总数。接下来m行，每一行包含如下格式：一个大写字母，“<”，第二个大写字母。字母不会超出字母表的范围。当n=m=0意味着输入结束。</p> 

 
 # 输出格式 
<p>
对于每个样例，输出包含一行，分下列三种情况： <br>Sorted sequence determined after xxx relations: yyy...y. <br>Sorted sequence cannot be determined. <br>Inconsistency found after xxx relations. <br><br>xxx 是关系的编号，表示从该关系开始，已经确定了序列的顺序，或者说产生了不一致。yyy...y 是排序后的序列。 <br></p> 
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
<tr><td>4 6
A < B
A < C
B < C
C < D
B < D
A < B
3 2
A < B
B < A
26 1
A < Z
0 0
</td><td>Sorted sequence determined after 4 relations: ABCD.
Inconsistency found after 2 relations.
Sorted sequence cannot be determined.</td></tr></table>
