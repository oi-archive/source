# 

 
 # 题目描述 
<p>
Ever the maturing businessman, Farmer John realizes that he must<br>manage his time effectively. He has N jobs conveniently numbered<br>1..N (1 <= N <= 1,000) to accomplish (like milking the cows, cleaning<br>the barn, mending the fences, and so on).<br><br>To manage his time effectively, he has created a list of the jobs<br>that must be finished. Job i requires a certain amount of time T_i<br>(1 <= T_i <= 1,000) to complete and furthermore must be finished<br>by time S_i (1 <= S_i <= 1,000,000). Farmer John starts his day at<br>time t=0 and can only work on one job at a time until it is finished.<br><br>Even a maturing businessman likes to sleep late; help Farmer John<br>determine the latest he can start working and still finish all the<br>jobs on time.<br><br><br>N个工作,每个工作其所需时间,及完成的Deadline,问要完成所有工作,最迟要什么时候开始.<br></p> 

 
 # 输入格式 
<p>
* Line 1: A single integer: N<br><br>* Lines 2..N+1: Line i+1 contains two space-separated integers: T_i<br>        and S_i<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: The latest time Farmer John can start working or -1 if<br>        Farmer John cannot finish all the jobs on time.<br><br></p> 
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
<tr><td>4
3 5
8 14
5 20
1 16

INPUT DETAILS:

Farmer John has 4 jobs to do, which take 3, 8, 5, and 1 units of
time, respectively, and must be completed by time 5, 14, 20, and
16, respectively.

</td><td>2

OUTPUT DETAILS:

Farmer John must start the first job at time 2. Then he can do
the second, fourth, and third jobs in that order to finish on time.</td></tr></table>
