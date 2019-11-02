# 

 
 # 题目背景 
NOIP&nbsp;2012&nbsp;普及组&nbsp;题4 

 
 # 题目描述 
有一位使者要游历各国，他每到一个国家，都能学到一种文化，但他不愿意学习任何一种文化超过一次（即如果他学习了某种文化，则他就不能到达其他有这种文化的国家）。不同的国家可能有相同的文化。不同文化的国家对其他文化的看法不同，有些文化会排斥外来&nbsp;文化（即如果他学习了某种文化，则他不能到达排斥这种文化的其他国家）。<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;现给定各个国家间的地理关系，各个国家的文化，每种文化对其他文化的看法，以及这&nbsp;位使者游历的起点和终点（在起点和终点也会学习当地的文化），国家间的道路距离，试求&nbsp;从起点到终点最少需走多少路。	把每一班级的队形看成一个字母(仅可能为大写字母)，然后按他们的出场顺序无聊地排成一串，成为了一个著名的字符串！JHT神犇想看看一个年级中，一共有多少种不同的出场组合(LCZ：说白了就是求字符串内的非空子串的数量！)。 

 
 # 输入格式 
第一行为五个整数&nbsp;N，K，M，S，T，每两个整数之间用一个空格隔开，依次代表国家&nbsp;个数（国家编号为&nbsp;1&nbsp;到&nbsp;N），文化种数（文化编号为&nbsp;1&nbsp;到&nbsp;K），道路的条数，以及起点和终点&nbsp;的编号（保证&nbsp;S&nbsp;不等于&nbsp;T）；<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第二行为&nbsp;N&nbsp;个整数，每两个整数之间用一个空格隔开，其中第&nbsp;i&nbsp;个数&nbsp;Ci，表示国家&nbsp;i&nbsp;的文化为&nbsp;Ci。<br><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接下来的&nbsp;K&nbsp;行，每行&nbsp;K&nbsp;个整数，每两个整数之间用一个空格隔开，记第&nbsp;i&nbsp;行的第&nbsp;j&nbsp;个数&nbsp;为&nbsp;aij，aij=&nbsp;1&nbsp;表示文化&nbsp;i&nbsp;排斥外来文化&nbsp;j（i&nbsp;等于&nbsp;j&nbsp;时表示排斥相同文化的外来人），aij=&nbsp;0&nbsp;表示&nbsp;不排斥（注意&nbsp;i&nbsp;排斥&nbsp;j&nbsp;并不保证&nbsp;j&nbsp;一定也排斥&nbsp;i）。<br><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接下来的&nbsp;M&nbsp;行，每行三个整数&nbsp;u，v，d，每两个整数之间用一个空格隔开，表示国家&nbsp;u<br><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;与国家&nbsp;v&nbsp;有一条距离为&nbsp;d&nbsp;的可双向通行的道路（保证&nbsp;u&nbsp;不等于&nbsp;v，两个国家之间可能有多条&nbsp;道路）。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输出只有一行，一个整数，表示使者从起点国家到达终点国家最少需要走的距离数（如果无解则输出-1）。 

 
 # 提示 
对于样例1：<br><br>由于到国家2必须要经过国家1，而国家2的文明却排斥国家1的文明，所以不可能到国家2。<br><br>对于样例2：<br><br>路线为1-&gt;2。<br><br>【数据范围】<br><br><br>对于&nbsp;20%的数据，有&nbsp;2≤N≤8，K≤5；<br><br>对于&nbsp;30%的数据，有&nbsp;2≤N≤10，K≤5；<br><br>对于&nbsp;50%的数据，有&nbsp;2≤N≤20，K≤8；<br><br>对于&nbsp;70%的数据，有&nbsp;2≤N≤100，K≤10；<br><br>对于&nbsp;100%的数据，有&nbsp;2≤N≤100，1≤K≤100，1≤M≤N2，1≤ki≤K，1≤u,&nbsp;v≤N，1≤d≤1000，&nbsp;S≠T，1&nbsp;≤S,&nbsp;T≤N。NOIP&nbsp;2012 
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
2 2 1 1 2
1 2
0 1
1 0
1 2 10
样例2：
2 2 1 1 2
1 2
0 1
0 0
1 2 10</td><td>样例1：
-1
样例2：
10</td></tr></table>
