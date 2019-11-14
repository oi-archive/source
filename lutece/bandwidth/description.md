
# Content

Study in BUPT, you cannot get rid of the word `bandwidth`. Nearly all the courses like "Signal and System", "Digital Signal Processing", "Communication Theory" are related to the bandwidth.

In the night before the exam of Signal and System, you got an incredible filter. In the frequency spectrum, if the maximal amplitude is $X$, then those frequency amplitude is less than $\frac{X}{2}$ would be filtered.

Now your task is to simulate the incredible filter and figure out the bandwidth after being filtered.

# Standard Input

First line contains an integer $T$ ($0 < T \leq 10$), indicate there are $T$ cases.

For each case, the first line contains an integer $N$ ($0 < N < 1000$), indicate the bandwidth of the frequency spectrum before being filtered.

Then comes $N$ lines, only formed by `-` whose length indicate the frequency amplitude (maximal length is not greater than $1000$).

It guaranteed the maximal length in every case will greater than zero.

# Standard Output

One line per case.

Each line contains only an integer indicate the bandwidth of the frequency spectrum after being filtered.

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
<tr><td>2
6
-
--
----
-
--
-
10
--
--
--
---
-----
------
-----
----
--
-</td><td>4
5</td></tr></table>


# Constraints



# Note



# Source


