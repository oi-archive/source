
# Content

Is Friday the $13\_{th}$ really an unusual event?

That is, does the $13\_{th}$ of the month land on a Friday less often than on any other day of the week? To answer this question, write a program that will compute the frequency that the $13\_{th}$ of each month lands on Sunday, Monday, Tuesday, Wednesday, Thursday, Friday, and Saturday over a given period of $N$ years. The time period to test will be from January $1$, $1900$ to December $31$, $1900+N-1$ for a given number of years, $N$. $N$ is non-negative and will not exceed $400$.

There are few facts you need to know before you can solve this problem:
* January $1$, $1900$ was on a Monday.
* Thirty days has September, April, June, and November, all the rest have $31$ except for February which has $28$ except in leap years when it has $29$.
* Every year evenly divisible by $4$ is a leap year ($1992 = 4\times 498$ so $1992$ will be a leap year, but the year $1990$ is not a leap year)
* The rule above does not hold for century years. Century years divisible by $400$ are leap years, all other are not. Thus, the century years $1700$, $1800$, $1900$ and $2100$ are not leap years, but $2000$ is a leap year. 

Do not use any built-in date functions in your computer language.

Don't just precompute the answers, either, please.

# Standard Input

One line with the integer $N$.

# Standard Output

Seven space separated integers on one line. These integers represent the number of times the $13\_{th}$ falls on Saturday, Sunday, Monday, Tuesday, ..., Friday.

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
<tr><td>20</td><td>36 33 34 33 35 35 34</td></tr></table>


# Constraints



# Note



# Source


