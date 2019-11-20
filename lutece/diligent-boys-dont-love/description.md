
# Content

Zplinti1 is a student in UESTC, a school full of beautiful girls. As a diligent boy, he has no interest in girls and just wants to study hard and gets a good remark when graduating, so that he can get a postgraduate recommendation, which means he can directly to continue his study for post-graduate session without taking exams. 

The policy for a postgraduate recommendation in UESTC is as follows:

1.	The Base Score. That is the weighted mean score for all compulsory courses. You have n such courses, each with a full mark as $100$ points. The Base Score is calculated in this way: for each course $i$, there is a weight as $B\_i$, and suppose your score is $A\_i$. Then the Base Score $P$ is calculated as $\frac{\sum\_{i = 0}^{n - 1}A\_i\times B\_i}{\sum\_{i = 0}^{n - 1} B\_i}$.Please note that all $A_i$ must be no less than $60$, otherwise you can’t get the recommendation.
2.	Attending other contests can bring extra points. First Prize – $3$ points, Second Prize – $2$ points, and Third Prize – $1$ point. The points are directly added to the Base Score. **A student can attend at most $2$ contests**. 

Here is how zplinti1 studies in UESTC:

1.	For each course i, zplinti1 has an array $time[i][X]$, which is the time he needs to study to improve his result on the course, from **$10\times X$** points to **$10\times (X+1)$** points.

2.	Zplinti1 finds, after taking a certain contest, it is easier for him to study some courses. In other word, it will affect his initial score for some courses. Here, initial score of a course means the score he will get without paying any time studying that course. If he doesn’t attend any contests, the initial score for every course should be zero.

The new policy of UESTC gives students more freedom: They can study all the four-year’s courses freely, which means they can arrange their time as they like, study the courses in any order, as long as they finish all the courses in a certain time. The contest can be arranged freely also.

Zplinti1 wants to know his highest possible score, if he makes a proper plan. **Zplinti1 cannot do multiple things at the same time, i.e. he can only learn a single course or participate in a single contest at the same time.**

# Standard Input

The first line of input contains a number $T$, indicating the number of test cases. ($T\leq 30$).

For each case, the first line are two integers $n$ and $sum$ ($1\leq n\leq 100,1\leq  sum\leq 1000$), means that there are $n$ courses and zplinti1 has $sum$ time to study in total. Following $n$ lines, each line comes an integer $B_i$ first, followed by ten integers $time[i][j]$. ($0\leq i < n, 0\leq j < 10, 1\leq times[i][j]\leq 5, 1\leq B_i\leq 5$)

Next six lines describe the two contests. For each contest, the $k_{th}$ line comes with an integer $pt_k$ at first, which means that if zplinti1 wants to get $k$ points in this contest he needs to spend $pt_k$ time. Then followed by $n$ integers $base[k][t]$, which means that for course $t$, its initial score will become $10\times base[k][t]$, if zplinti1 gets $k$ points in this contest.($1\leq k\leq 3,0\leq t < n,1\leq pt_k\leq 1000,0\leq base[k][t]\leq 10$)

# Standard Output

For each case, output `Case #i: ` first. ($i$ is the number of the test case, from $1$ to $T$). Then output highest possible score zplinti1 can get(round to two decimal places). If zplinti1 can’t get the recommendation output `Impossible` instead.

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
<tr><td>3
1 9
2 1 1 1 1 1 2 2 2 2 2
4 2
5 3
7 5
3 1
5 4
6 6
1 10
2 5 5 5 5 5 5 5 5 5 5
5 0
10 0
15 0
5 1
10 2
15 3
2 20
2 1 1 1 1 1 1 1 1 1 1
3 2 2 2 2 2 2 2 2 2 2
6 1 2
9 2 3
14 3 5
5 2 1
8 3 2
15 5 4</td><td>Case #1: 73.00
Case #2: Impossible
Case #3: 68.00</td></tr></table>


# Constraints



# Note

If zplinti1 has attended both two contests, and those two contests’ influence on a course’s initial score is different, we will take the higher one.

For example, if in the first contest, $base[k1][t]=7$, and in the second contest, $base[k2][t]=8$, then if zplinti1 has got $k\_1$ points in the $1\_{st}$ contest and $k\_2$ points in the $2\_{nd}$ contest, his initial score for course t will be $80$.

# Source


