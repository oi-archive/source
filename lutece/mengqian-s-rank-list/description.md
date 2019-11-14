
# Content

Mengqian has attracted overwhelming suitors after March $11$. The suitors compete to marry Mengqian with their Charm values (an integer value evaluating how much the suitors can fascinate Mengqian). And Mengqian claims that she prefers smaller Charm value to greater one, so that the suitor with smallest Charm value ranks top first in Mengqian’s selection.

Mengqian wants to wait for more suitors in order to choose the best. However, the suitors are not so patient. Some of them give up after waiting too long while some new join the Mengqian’s competition. Mengqian keeps a ranking list of all current suitors ordered by their Charm value. She will add a new Charm value into the list when a new suitor join and she will delete whose Charm value from the list when someone give up, and Mengqian will keep the list in order of Charm all the time. Please note that suitors with same Charm value have the same rank.

Suitors are asking Mengqian about their rankings and even who ranks higher or lower than them. There are totally $4$ kinds of queries.
* Query $0$. What’s the Charm value ranks the $R$ currently? (You can assume ranking $R$ must currently exist).
* Query $1$. What’s the rank of Charm value $C$ currently? (You can assume $C$ must exist in the current list).
* Query $2$. What’s the minimal Charm $C$ ranks higher than Charm $D$? (You can assume $D$ and its higher ranker must exist in the current list).
* Query $3$. What’s the maximal Charm $C$ ranks lower than Charm $D$? (You can assume $D$ and its lower ranker must exist in the current list).

Now Mengqian asks you to program on the issue to serve the queries.

# Standard Input

There are several test inputs, and only one test case in each input.

The first line of the input contains only an integer $N$. And $N$ lines follow.

Each line of the input contains one command and one parameter as the $6$ formats below.
* `ADD C` (a new suitor with Charm value $C$ joins)
* `DEL C` (an exist suitor with Charm value $C$ gives up and leaves)
* `Q0 R` (Query $0$ described)
* `Q1 C` (Query $1$ described)
* `Q2 D` (Query $2$ described)
* `Q3 D` (Query $3$ described)

$0 < N, R < 1000000$, $C$ fits into a signed $32$bit integer.

# Standard Output

For every query, output one line as describe below.
* For `Q0`, output the Charm value ranks the $R$ (given).
* For `Q1`, output the rank of Charm value $C$ (given).
* For `Q2`, output the minimal Charm $C$ ranks higher than Charm $D$(given).
* For `Q3`, output the maximal Charm $C$ ranks lower than Charm $D$(given).

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
<tr><td>12
ADD 3
ADD 1
ADD 3
ADD 3
ADD 4
Q0 2
Q1 4
DEL 3
Q2 3
ADD 2
DEL 1
Q3 3</td><td>3
5
4
2</td></tr></table>


# Constraints



# Note

Huge input/output, scanf/printf is recommended instead of cin/cout to avoid unnecessary Time Limited Exceed.

# Source


