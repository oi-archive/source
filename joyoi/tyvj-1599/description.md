# 

 
 # 题目描述 
身体是革命的本钱，OIers不要因为紧张的学习和整天在电脑前而忽视了健康问题。小x设计了自己的锻炼计划，但他不知道这个计划是否可行，换句话说如果计划不当可能会让他的体力超支，所以小x请你帮助他。<BR>一天有1440分钟，所以小x列出的是这一整天第1至第1440分钟的计划。小x的体力用一个整数来表示，他会按照计划表进行锻炼，同时，每分钟小x的体力会自动增加1。如果某一分钟末小x的体力小于等于零，那么可怜的小x就累死了…… 

 
 # 输入格式 
第一行是用空格分开的三个整数n,m，分别表示小x的初始体力值和计划的项目数量。<BR>从第二行开始的m行，每行描述一个锻炼项目：名称、开始时间a、结束时间b、每分钟耗费的体力(用空格分隔)，表示此项目从第a分钟初开始，第b分钟末结束。锻炼项目按照开始时间递增顺序给出，不会出现两个项目时间冲突的情况。 

 
 # 输出格式 
输出包括两行，如果计划可行，第一行输出"Accepted"，第二行输出这一天过后最后剩余的体力；否则在第一行输出"Runtime&nbsp;Error"，第二行输出在第几分钟累死。 

 
 # 提示 
0&lt;=n&lt;=2^31-1<BR>0&lt;=m&lt;=500<BR>所有中间值的绝对值不会超过2^31-1<BR>每一个锻炼项目的名称不超过20个字符，其中不含空格。 
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
<tr><td>input1:

10 1
Basketball 1 10 1

input2:

1 1
Nunchakus 1 1 2</td><td>output1:

Accepted
1440

output2:

Runtime Error
1</td></tr></table>
