
# Content

Dr. Suresh has discovered that special genetic pieces would enable human beings to have special abilities, such as flying, self-healing, time-stopping, and so on. He would like to compile a list containing all such special people. An individual is on the list if and only if his genetic code contains one of the special pieces as a substring. Please help Dr.Suresh to do the task.

# Standard Input

The first line contains an integer $N$, number of special genetic pieces. Following $N$ lines each contain a string, the genetic code of each piece. On the next line is an integer $M$, number of individuals to be examined. Next $M$ lines each has a string, which is the genetic code of each individual.

* $1 \leq N \leq 10, 1 \leq M \leq 50$

* The length of any genetic code is greater than zero and does not exceed $50$.

* A genetic code is a string containing `A`, `T`, `C` and `G` only and it doesn't contain any white spaces.

* String $A$ is a substring of $B$, if and only if $A$ appears continuously in $B$ (e.g. `ATC` is a substring of `AATCTC`, but `ATT` isn't).

* A Hero's genetic code can contain multiple kinds of special genetic pieces as substrings.

# Standard Output

For each individual, if he is on the list, output `A new hero discovered` on a single line. Otherwise output `Just an ordinary person` instead.

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
ATA
ATC
3
ACATAG
AATTCCGG
ATCGGATACG</td><td>A new hero discovered
Just an ordinary person
A new hero discovered</td></tr></table>


# Constraints



# Note



# Source


