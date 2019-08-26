
# Description

<div class="content"><p><span style="font-size: medium">Ever the maturing businessman, Farmer John realizes that he must manage his time effectively. He has N jobs conveniently numbered 1..N (1 &lt;= N &lt;= 1,000) to accomplish (like milking the cows, cleaning the barn, mending the fences, and so on). To manage his time effectively, he has created a list of the jobs that must be finished. Job i requires a certain amount of time T_i (1 &lt;= T_i &lt;= 1,000) to complete and furthermore must be finished by time S_i (1 &lt;= S_i &lt;= 1,000,000). Farmer John starts his day at time t=0 and can only work on one job at a time until it is finished. Even a maturing businessman likes to sleep late; help Farmer John determine the latest he can start working and still finish all the jobs on time. </span></p>
<p><span style="font-size: medium">N个工作,每个工作其所需时间,及完成的Deadline,问要完成所有工作,最迟要什么时候开始.</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer: N </span></p>
<p><span style="font-size: medium">* Lines 2..N+1: Line i+1 contains two space-separated integers: T_i and S_i </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: The latest time Farmer John can start working or -1 if Farmer John cannot finish all the jobs on time. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
3 5<br/>
8 14<br/>
5 20<br/>
1 16<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
Farmer John has 4 jobs to do, which take 3, 8, 5, and 1 units of<br/>
time, respectively, and must be completed by time 5, 14, 20, and<br/>
16, respectively.<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
Farmer John must start the first job at time 2. Then he can do<br/>
the second, fourth, and third jobs in that order to finish on time.<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

