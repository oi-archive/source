
# Content

The concert promoters of the Bon Jovi Tour $2013$ have decided to sell tickets for the concerts in lotteries. The rules are quite simple. For every concert, fans can apply online for tickets. In response they 
receive unique reservation numbers. It is important that for each concert the numbers distributed
online are consecutive nonnegative integers starting with $0$. Unfortunately, as the organizers tried to
draw reservation numbers randomly, they discovered that the pseudo random generator they used is
extremely slow. To minimize the number of calls to the generator, they invented a peculiar but fair
enough way to distribute tickets.

As soon as the reservation for a concert is finished, the organizers ascertain the number of submissions
$M$ and draw one random integer $Z$ from {$0,\cdots ,M−1$} (remember, fans get integers from $0$ to $M−1$).
Integer $Z$ is the only object the organizers have to draw randomly! Finally, to complete the selection
rules the organizers determine an integer $r > 0$ which has a direct impact on the number of selected
tickets.

Now, using $Z$ and $r$, tickets are selected deterministically as follows. For the reservation numbers
$0,\cdots ,M −1$ and the number $Z$, their decimal representations of length $n$ are considered, where $n$ is
the length of the representation of $M − 1$ without leading zeros. Thus, the decimal representations
of the remaining numbers are padded on the left with leading zeros, if needed. If $z\_1 \cdots z\_n$ denotes
such a representation for $Z$, then the holder of a number $a\_1 \cdots a\_n$ gets the ticket if and only if the
strings $z\_1 \cdots z\_n$ and $a\_1 \cdots a\_n$ have a common contiguous substring of length $r$ or more which starts
at the same position. Speaking formally, he or she gets the ticket if there exists an index $i$, with
$1\leq i\leq n − r + 1$, such that $z\_i \cdots z\_{i+r−1} = a\_i \cdots a\_{i+r−1}$. For example, if $Z = 56743$ and $r = 3$ then
a fan with a reservation number $06740$ gets a ticket, but a fan having $56143$ does not.

Your task is to help the organizers to estimate, for given numbers $M$, $Z$ and $r$, the exact number of
tickets selected in such a way.

# Standard Input

The first line contains the number of concerts $C$, with $1\leq C\leq 5000$. Then follow $C$ lines, each
containing three integers $M$, $Z$, and $r$, with $0 < M\leq 10^{18}$, $0\leq Z\leq M − 1$ and $r\geq 1$. You may
safely assume that $r$ is smaller or equal to the length of the decimal representation of $M − 1$.

# Standard Output

For each concert, print one line containing the number of tickets selected during the ticket draw.

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
<tr><td>8
89 32 1
67 49 1
67 45 2
1000 23 1
1000 401 2
1000 54 2
3571 2 3
3571 976 3</td><td>18
15
1
271
19
19
13
12</td></tr></table>


# Constraints



# Note



# Source


