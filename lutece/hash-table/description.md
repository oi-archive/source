
# Content

Akemi Homura is a Mahou Shoujo (Puella Magi/Magical Girl).

To help her friend Madoka save the world, Homura need to collect data, and she choose a kind of data structure called Hash Table.

I suppose all of you are familiar with the Hash Table (if not, you won't take part in the competition!), for a piece of data $D$, the Hash Function $H$ gives a Hash Key: $H(D)$, and the data will be stored in Hash Table $[H(D)]$. For two pieces of data $D\_1$ and $D\_2$, if their Hash Keys are the same ($H(D\_1) = H(D\_2)$), we say an `COLLUSION` occurs. $D\_1$ and $D\_2$ cannot be stored in the same position of the Hash Table. The most convenient way to solve the problem is linear probing.

We assume that $D\_1$ has been inserted into Hash Table $[H(D\_1)]$, now if we need to insert $D\_2$ into the Hash Table, since Hash Table $[H(D\_1)]$ has been occupied by $D\_1$, $D\_2$ has to find the next position of $H(D\_1)$: Hash Table $[H(D\_1)+1]$. If Hash Table $[H(D\_1)+1]$ is also occupied, $D\_2$ has to find the next position of $H(D\_1)+1$: Hash Table $[H(D\_1)+1]$ ... Till $D\_2$ finds an unoccupied position: Hash Table $[p]$, and be stored in it.

As It is known that Homura has magic that can control time, she can rearrange the order that data is inserted into the Hash Table in. Given $N$ Hash Keys $H(D\_1), H(D\_2),\cdots , H(D\_N)$ of data $D\_1, D\_2,\cdots , D\_N$, your task is to help her rearrange the order to minimize the total collusion times. You may assume the length of the Hash Table is infinitive.

# Standard Input

The first line contains an integer $N$ ($1\leq N\leq 10^6$).

The second line contains $N$ integers $D\_1, D\_2, \cdots , D\_N$ ($1\leq D\_i\leq 2^{31}-1$).

# Standard Output

The minimum of total collusion times.

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
1 2 1 3 2</td><td>6</td></tr></table>


# Constraints



# Note

Huge input. `scanf` recommended.

# Source


