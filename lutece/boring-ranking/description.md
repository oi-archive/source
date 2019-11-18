
# Content

New term is coming, so the annual scholarship is going to be distributed. But Alibaba can’t wait to know how much he can get. Now he gets all the info including every course’s score and quality score of every student. He is too impatient to ask you for help.

As a UESTCer, you must know the evaluation method of scholarship. If you aren’t familiar with it, you can refer to the following description.

Your score consists of two parts: basis score and quality score.

Basis score is the weighted average score of all courses’ scores. Every course has a weight coefficient. Assume $S\_i$ and $W\_i$ are the score and weight coefficient of the $i\_{th}$ course, then the weighted average score is equal to:
                                         
$$\frac{\sum{S\_i\times W\_i}}{\sum{W\_i}}$$

Quality score is up to your performance in science and technology activities, competitions and student works.

At first, all students are ranked by basis score, and divided into $4$ groups: top $10\%$, next $20\%$, then next $30\%$ and others. And then every student is ranked only in his/her group according to the sum of basic score and quality score.

Alibaba wants to know the final ranklist of top $3$ groups because the last $40\%$ can’t get the scholarship. Can you tell him?

# Standard Input

The first line of input contains an integer $T$ ($T\leq 20$), which is the number of test cases that follow.

For each test case:

There are two integers $N$ and $M$ ($10\leq N\leq 100$, $1\leq M\leq 20$) in the first line, which is the number of students and courses. 

Then $N$ lines follow, each of them containing a string. The string in $i\_{th}$ line is the name of the $i\_{th}$ student. All strings only consist of lowercase letters and the length isn’t larger than $20$.

Then a single line follows containing $M$ integers. The $i\_{th}$ integer is $W\_i$ indicating the weight coefficient of the $i\_{th}$ course. All weight coefficients are in the range $[1,6]$.

Then $N$ lines follow, each of them containing $M$ integers separated by single spaces. The $j\_{th}$ element in the $i\_{th}$ line is the $j\_{th}$ course’s score of the $i\_{th}$ student. All scores are in the range $[0,100]$.

Then $N$ lines follow, each of them containing a single integer indicating the quality score. All scores are in the range $[0,20]$.

You can assume every student’s name, basis score and final score are unique, and $N$ is a multiple of $10$.

# Standard Output

For every test case, you should output `Case #k:` first in a single line, where $k$ indicates the case number and starts at $1$. Then output the final ranklist of top $3$ groups who get the scholarship. Print a blank line between every two adjacent groups, and print a blank line after every test case.

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
<tr><td>1
10 1
standy
totalfrank
total
frank
frost
joyzhang
uestc
uestcmelody
acm
icpc
5
90
92
65
30
50
60
85
95
80
88
10
3
12
8
6
3
5
1
20
5</td><td>Case #1:
uestcmelody

standy
totalfrank

acm
icpc
uestc</td></tr></table>


# Constraints



# Note



# Source


