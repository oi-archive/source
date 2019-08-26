
# Description

<div class="content"><div class="plm"></div>
<div lang="en-US" class="ptx"><span style="font-size: medium">There are two applications running on a multiprocessor machine. Each application i (i=1,2) consists of N procedures which are numbered from 1 to N and must be executed sequentially (in the order 1,...,N). A procedure will be identified by a pair (i,j), where i=1,2 identifies the application and 1≤j≤N represents the index of the procedure in the sequence of procedures of the application i. A procedure (i,j) can only be executed on the processor P(i,j) of the machine and its execution lasts for D(i,j) seconds. We want to schedule the execution of the procedures of the two applications over the processors of the machine in such a way that the time moment when the last procedure finishes its execution (from any of the two applications) is minimum; this time moment is called makespan. We consider that the two applications are available for scheduling starting from the time moment 0. The schedule needs to obey the following rules: <br/>
</span>
<p style="padding-left: 30px"><span style="font-size: medium"><br/>
once the execution of a procedure (i,j) starts on the processor P(i,j), we cannot interrupt it until the execution of the procedure ends <br/>
we cannot execute multiple procedures on the same processor at the same time, but we can execute multiple procedures in parallel on different processors <br/>
the execution of the procedure (i,j) (2≤j≤N) starts either at the exact time moment tm when the procedure (i,j-1) finishes its execution or at any time moment after tm <br/>
if a procedure begins its execution at time moment tm, then it will finish its execution at the time moment tm+D(i,j) <br/>
</span></p>
<span style="font-size: medium"><br/>
</span></div>
<div style="widows: 2; text-transform: none; text-indent: 0px; font: 14px/23px 幼圆; white-space: normal; orphans: 2; letter-spacing: normal; color: rgb(0,0,0); word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px"><span style="font-size: medium">有两组任务，每组都有N个任务，现在将这些任务放到一些处理器中处理，条件如下： </span></div>
<div style="widows: 2; text-transform: none; text-indent: 0px; font: 14px/23px 幼圆; white-space: normal; orphans: 2; letter-spacing: normal; color: rgb(0,0,0); word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px"><span style="font-size: medium">1.任意一组任务必须按顺序完成，也就是必须先做完前i-1个才能做第i个。 </span></div>
<div style="widows: 2; text-transform: none; text-indent: 0px; font: 14px/23px 幼圆; white-space: normal; orphans: 2; letter-spacing: normal; color: rgb(0,0,0); word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px"><span style="font-size: medium">2.某个任务只能在指定的处理器（编号不超过10）上做。 </span></div>
<div style="widows: 2; text-transform: none; text-indent: 0px; font: 14px/23px 幼圆; white-space: normal; orphans: 2; letter-spacing: normal; color: rgb(0,0,0); word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px"><span style="font-size: medium">3.一个处理器同一时间只能处理一个任务，并且不允许中断。 </span></div>
<div style="widows: 2; text-transform: none; text-indent: 0px; font: 14px/23px 幼圆; white-space: normal; orphans: 2; letter-spacing: normal; color: rgb(0,0,0); word-spacing: 0px; -webkit-text-size-adjust: auto; -webkit-text-stroke-width: 0px"><span style="font-size: medium">求完成两组任务的最短时间。</span></div></div>

# Input

<div class="content"><p>Write a program that, given the information regarding the procedures of the two applications, computes the minimum makespan.</p>
<div lang="en-US" class="ptx">The first line of the input file contains the number T of test cases which are described next. The first line of a test case contains the number N (1≤N≤300) of procedures composing each of the two applications. Then, N lines follow, describing the first application. The j<sup>th</sup> of these N lines contains two integers, separated by a blank: P(1,j) and D(1,j). After this, other N lines follow, describing the second application. The j<sup>th</sup> of these N lines contains two integers, separated by a blank: P(2,j) and D(2,j). We have 1≤P(i,j)≤10 and 1≤D(i,j)≤15000 (i=1,2; 1≤j≤N). Notice that we may have P(i,j)=P(k,l) – this implies that the procedures (i,j) and (k,l) cannot be executed during overlapping time intervals (notice also that if i=k this would not matter, as the procedures of the same application must be executed sequentially).</div></div>

# Output

<div class="content"><div lang="en-US" class="ptx">The output file must contain exactly T lines with a single number each – the minimum makespan for the corresponding test from the input file. These answers must be printed in the order in which the test cases are given in the input file (i.e. the i<sup>th</sup> line of the output file contains the answer to the i<sup>th</sup> test case from the input file).</div></div>

# Sample Input

<div class="content"><span class="sampledata">2 <br/>
1 <br/>
2 6 <br/>
1 10 <br/>
3 <br/>
2 31 <br/>
2 18 <br/>
4 15 <br/>
2 26 <br/>
3 40 <br/>
5 16<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">10 <br/>
90<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Seerc2009">Seerc2009</a></p></div>

