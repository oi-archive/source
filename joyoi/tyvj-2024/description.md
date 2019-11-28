# 

 
 # 题目背景 
运动员身高<br>县运动会即将在我校举行。来自县里的各个学校的运动员身高有高有矮，导致引导员给他们排队时很搞得头疼。<br><br> 

 
 # 题目描述 
现已知有n个运动员，他们之间有m对身高关系（如：运动员1比运动员2高，运动员2比运动员3高&nbsp;等）。<br>下面要让学OI的你来解决一个问题：对于每一组关系表，试判断哪些运动员的身高排名能够最终确定。<br><br>对于样例的解释：由于2比1高，2比3高，所以2的身高排名一定是最高的（能够确定），故有且仅有1位运动员的身高可以确定。<br> 

 
 # 输入格式 
第一行：两个整数，分别表示运动员数n、已知身高比较数m<br>第二..m行：两个整数x&nbsp;y，表示运动员x比运动员y高<br> 

 
 # 输出格式 
第一行&nbsp;一个数字t，表示能够确定身高名次的运动员个数；<br>第二行&nbsp;t个数字（空格隔开），是这t个运动员的编号（从小到大）。<br>注意：行末不要出现空格。<br> 

 
 # 提示 
数据范围：<br>&nbsp;20%数据，0&lt;n,m&lt;=10;<br>&nbsp;40%数据，0&lt;n&lt;=30,0&lt;m&lt;=80;<br>100%数据，0&lt;n&lt;=2000,0&lt;m&lt;=20000.<br>所有数据满足互不冲突。<br><br>运动员标号范围1~n.<br> 
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
<tr><td>3 2
2 1
2 3
</td><td>1
2
</td></tr></table>
