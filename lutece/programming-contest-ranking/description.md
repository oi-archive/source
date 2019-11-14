
# Content

Heilongjiang Programming Contest will end successfully! And your task is programming contest ranking.
The following rules rankings:
1. A problem is solved when it is accepted by the judges.
2. Teams are ranked according to the most problems solved；
3. Teams who solve the same number of problems are ranked by least total time. The total time is the sum of the time consumed for each problem solved. The time consumed for a solved problem is the time elapsed from the beginning of the contest to the submittal of the accepted run plus $20$ penalty minutes for every rejected run for that problem regardless of submittal time. Team(s) who firstly solved the problem will have no penalty in the problem. There is no time consumed for a problem that is not solved.
4. Teams who are the same number of problems solved and the same total time are ranked by the most weighting number of problems solved；The weight of the $i\_{th}$ problem is the floor of $\frac{N}{C\_i}$. where $N$ is the number of all teams, and $C\_i$ is the number of teams who solved the $i\_{th}$ problem. The weight of one problem will be 0 if there is no team solved the problem.

# Standard Input

The input contains multiple test cases. For each test case,first line contains two integers, $N$ and $M$，$N (1 < N \leq 200)$ is the number of all teams，$M (6 \leq M \leq 20)$ is the number of problems；

Then following $N$ lines, there are $M+1$ items seprated by a space in each.line, corresponding the record of one team . The first item is the name of the team, not exceed $20$ letters. Then following $M$ items, each item is:
1.  `-\-`    if the team did not submit for the problem;
2. `TT\-`  if the team submitted $TT$ times for the problem,but did not solve it.
3. `TT\FT` if the team submitted $TT$ times for the problem, $FT$ is the time elapsed from the beginning of the contest to the submittal of the accepted. 

  $1 \leq TT \leq 32, 1 \leq FT \leq 300$ , Both $TT$ and $FT$ are integer.

# Standard Output

Output ranking result in $N$ lines.

The format of each line is:

  Rank (width $3$)  

Name of team (width $20$)

Number of problems solved (width $2$) 

Total time(width $6$) 

Weighting Number of problems solved (width $4$)

  Each item above align $\textbf{right}$, seprated by a space.

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
<tr><td>6 6
Leifeng 8\135 1\20 1\57 5\230 6\- 3\283
Fighter 7\136 1\15 1\42 6\200 5\- 2\270
AlwaysAK 7\156 1\24 1\31 5\202 5\270 4\- 
SoyOnceMore 5\- 6\- 3\- 2\75 -\- -\-
RpRpRp 5\- 3\35 10\- -\- -\- -\-
StartAcm 2\- 3\- 3\- 4\- 1\- -\-</td><td>1              Leifeng  5    845    9
  2             AlwaysAK  5    883   12
  3              Fighter  5    883    9
  4               RpRpRp  1     75    1
  4          SoyOnceMore  1     75    1
  6             StartAcm  0      0    0</td></tr></table>


# Constraints



# Note

样例输出第一行最前面有两个空格，但是被吞了，大家就当有两个空格吧，耶！

# Source


