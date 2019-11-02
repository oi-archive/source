# 

 
 # 题目描述 
<p>
Farmer John's cows, pampered since birth, have reached new heights of<br>fastidiousness. They now require their barn to be immaculate. Farmer John,<br>the most obliging of farmers, has no choice but hire some of the cows to<br>clean the barn.<br><br>Farmer John has N (1 <= N <= 10,000) cows who are willing to do some<br>cleaning. Because dust falls continuously, the cows require that the farm<br>be continuously cleaned during the workday, which runs from second number M<br>to  second number E during the day (0 <= M <= E <= 86,399). Note that the<br>total number of seconds during which cleaning is to take place is E-M+1.<br>During any given second M..E, at least one cow must be cleaning.<br><br>Each cow has submitted a job application indicating her willingness to work<br>during a certain interval T1..T2 (where M <= T1 <= T2 <= E) for a certain<br>salary of S (where 0 <= S <= 500,000). Note that a cow who indicated the<br>interval 10..20 would work for 11 seconds, not 10. Farmer John must either<br>accept or reject each individual application; he may NOT ask a cow to work<br>only a fraction of the time it indicated and receive a corresponding<br>fraction of the salary.<br><br>Find a schedule in which every second of the workday is covered by at least<br>one cow and which minimizes the total salary that goes to the cows.<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Three space-separated integers: N, M, and E.<br><br>* Lines 2..N+1: Line i+1 describes cow i's schedule with three<br>        space-separated integers: T1, T2, and S.<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: a single integer that is either the minimum total salary to<br>        get the barn cleaned or else -1 if it is impossible to clean<br>        the barn.<br><br></p> 
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
<tr><td>3 0 4  //三头牛,要打扫从0到4号stall
0 2 3  //一号牛,从0号stall打扫到2号,工资为3
3 4 2
0 0 1

INPUT DETAILS:

FJ has three cows, and the barn needs to be cleaned from second 0 to second
4. The first cow is willing to work during seconds 0, 1, and 2 for a total
salary of 3, etc.
</td><td>5

OUTPUT DETAILS:

Farmer John can hire the first two cows.(问你最少花多少钱....)</td></tr></table>
