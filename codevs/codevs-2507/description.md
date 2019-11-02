<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>The Central Engineering Organization, International (CEOI) has received M job requests for the next N days. To perform a job requires exactly one day by one machine. CEOI has access to several machines, each of which can perform at most one job per day, so the organization can do at most as many jobs a day as the number of available machines. CEOI aims to work with at most D days of delay, which means that if a client submits a job for processing on day S, then it will be finished no later than on day S+D.</p>
<p>You are to write a program that computes the minimum number of machines that the organization needs to process all jobs with at most D days of delay.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>The first line of the input contains three integers, N (1 ≤ N ≤ 100 000) is the number of days the organization performs jobs, D (0 ≤ D &lt; N) is the maximum number of days permitted for the delay, and M <br>(1 ≤ M ≤ 1 000 000) is the number of job requests. The days are numbered from 1 to N, and the requests are numbered from 1 to M. The second line contains exactly M integers separated by space, the ith number is the day when request i is submitted for processing. No jobs are submitted after day N–D.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>The first line of the output contains one integer, the minimum number of machines that the organization <br />needs to be able to process all jobs with at most D days of delay.&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>8 2 12 <br>1 2 4 2 1 3 5 6 2 3 6 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 <br><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>In 50% of the test cases M is at most 100 000. <br>If only the first line is correct then 40% of the points are awarded.</p>
</div>
</div>