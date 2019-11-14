
# Content

Resently, loneknight is doing research on job shop schedule problem(JSP for short). Let us take a look at JSP, there are n jobs and m machines, and every job must be processed in every machines, with a process time $t[i,j]$ for job $i$ being processed in machines $j$. One restrain is that the order for each job processed in machines is fixed, which means that for every job $i$, there is a process oder $(a[i,1], a[i,2], ..., a[i,m])$, job $i$ must processed in machine $a[i,1]$ first then $a[i,2], \cdots, a[i,m]$. Another restrain is every machine can process amost one job at any time, and every job can be process in amost one machine at any time. The problem is to find a schedule fit this restrains, that make the end time for all jobs, namely the makespan is minimum. Because of the fact that JSP is a NP-Complete problem, loneknight try using simulated anealing and gene algorithm to construct a heuristics algorithm for it. In developing such algorithm for JSP, he confront with a problem that if a schedule is already given, what is the makespan of this schedule, now this your task to solve this problem.

# Standard Input

There are mutiple test cases in the input. The beginning of each case is n, the number of jobs, m, the number of machines. $(0 < n,m \leq 300)$ Each follow three components. First is a $n \times m$ matrix, the value in the $i$_th row and $j$_th column is $t[i,j]. (0 \leq t[i,j] < 100)$ Second is a $n \times m$ matrix, the jobs process order, the value in the $i$_th row and $j$_th column is $a[i,j]$. Third is a $m \times n$ matrix the machines process order, the value in the $i$_th row and $j$_th column is $b[i,j], (b[i,1],b[i,2], ..., b[i,n])$ is the jobs process order in machine $i$, which means machine $i$ process $b[i,1]$ first, then $b[i,2], \cdots, b[i,n]$. (jobs and machines are indexed from $1$) The input end with EOF.

# Standard Output

For each test case, you should output a single integer, which is the makespan for that schedule in a single line.

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>3 3
83 86 77 
15 93 35 
86 92 49 

3 1 2 
3 1 2 
1 3 2 

1 2 3 
1 3 2 
1 2 3</td><td>495</td></tr></table>


# Constraints



# Note



# Source


