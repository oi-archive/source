
# Content

Phyllis works for a large, multi-national corporation. She moves from department to department where
her job is to uncover and remove any redundancies inherent in the day-to-day activities of the workers.
And she is quite good at her job.

During her most recent assignment, she was given the following chart displaying the chain of command
within the department:

<p class="text-center">
<img src="/source/lutece/super-phyllis/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODcyLzIwMTQwNTEwMTg1MDQ5NzQ0MjgucG5n.png" alt="title">
<h5 class="text-center">Figure $1$</h5>
</p>

Whenever anyone needs to send a report to their bosses, they use the above chart, sending one report
along each arrow. Phyllis realized almost instantly that there were redundancies here. Specifically, since
`D` sends a report to `B` and `B` sends a report to `A`, there's really no need for `D` to send a report to `A`
directly, since it will be summarized in the report `B` sends to `A`. Thus the connection from `D` to `A` can
be removed. If there had also been a connection from `C` to `B`, then the connections from `D` to `B` and `C`
to `A` could have been removed as well.

Phyllis would like your help with this. Given a description of a chart like the one above, she would like
a program that identifies all connections that can be removed from the chart.

# Standard Input

The first line of each test case will contain a positive integer $m$ indicating the number of connections
in the chart. Following that will be $m$ lines each containing two strings $s\_1$ $s\_2$ indicating that there
is a connection from employee $s\_1$ to his/her boss $s\_2$. In any test case there will be no more than
$200$ employees listed and no connection will appear more than once. A line containing a single $0$ will
terminate the input.

# Standard Output

For each test case, output the number of connections that should be removed followed by a list of the
deleted connections in lexicographic order. Connection $s\_1$ $s\_2$ should be represented by the string `s1,s2`.

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
<tr><td>5
D B
D C
D A
B A
C A
6
D B
D C
D A
C B
B A
C A
1
Danny Tessa
0</td><td>Case 1: 1 D,A
Case 2: 3 C,A D,A D,B
Case 3: 0</td></tr></table>


# Constraints



# Note



# Source


