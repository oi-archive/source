
# Content

An integer hash table is a data structure that supports insert, delete and lookup of integer values in
constant time. Traditional hash structures consist of an array (the *hash table*) of some size $n$, and a
*hash function* $f(x)$ which is typically $f(x) = x\ \rm mod$ $n$. To insert a value $x$ into the table, you compute
its *hash value* $f(x)$ which serves as an index into the hash table for the location to store $x$. For example,
if $x = 1234$ and the hash table has size $101$, then $1234$ would be stored in location $22 = 1234\rm\ mod$ $101$.
Of course, it's possible that some other value is already stored in location $22$ ($x = 22$ for example),
which leads to a collision. Collisions can be handled in a variety of ways which you can discuss with
your faculty advisor on the way home from the contest.

Cuckoo hashing is a form of hashing that employs two hash tables $T\_1$ and $T\_2$, each with its own hash
function $f\_1(x)$ and $f\_2(x)$. Insertion of a value $x$ proceeds as follows: you first try to store $x$ in $T\_1$ using
$f\_1(x)$. If that location is empty, then simply store $x$ there and you're done. Otherwise there is a collision
which must be handled. Let $y$ be the value currently in that location. You replace $y$ with $x$ in $T\_1$, and
then try to store $y$ in $T\_2$ using $f\_2(y)$. Again, if this location is empty, you store y there and you're
done. Otherwise, replace the value there (call it $z$) with $y$, and now try to store $z$ back in $T\_1$ using
$f\_1(z)$, and so on. This continues, bouncing back and forth between the two tables until either you find
an empty location, or until a certain number of swaps have occurred, at which point you rehash both
tables (again, something to discuss with your faculty advisor). For the purposes of this problem, this
latter occurrence will never happen, i.e., the process should always continue until an empty location is
found, which will be guaranteed to happen for each inserted value.

Given the size of the two tables and a series of insertions, your job is to determine what is stored in
each of the tables.

(For those interested, cuckoo hashing gets its name from the behavior of the cuckoo bird, which is
known to fly to other bird's nests and lay its own eggs in it alongside the eggs already there. When
the larger cuckoo chick hatches, it pushes the other chicks out of the nest, thus getting all the food for
itself. Gruesome but efficient.)

# Standard Input

Input for each test case starts with $3$ positive integers $n\_1$ $n\_2$ $m$, where $n\_1$ and $n\_2$ are the sizes of the
tables $T\_1$ and $T\_2$ (with $n\_1, n\_2\leq 1000$ and $n\_1\neq n\_2$) and $m$ is the number of inserts. Following this
will be $m$ integer values which are the values to be inserted into the tables. All of these values will be
non-negative. Each table is initially empty, and table $T\_i$ uses the hash function $f\_i(x) = x\rm\ mod$ $n\_i$
. A
line containing $3$ zeros will terminate input.

# Standard Output

For each test case, output the non-empty locations in $T\_1$ followed by the non-empty locations in $T\_2$.
Use one line for each such location and the form `i:v`, where $i$ is the index location of the table, and $v$
is the value stored there. Output values in each table from lowest index to highest. If either table is
empty, output nothing for that table.

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
<tr><td>5 7 4
8 18 29 4
6 7 4
8 18 29 4
1000 999 2
1000
2000
0 0 0</td><td>Case 1:
Table 1
3:8
4:4
Table 2
1:29
4:18
Case 2:
Table 1
0:18
2:8
4:4
5:29
Case 3:
Table 1
0:2000
Table 2
1:1000</td></tr></table>


# Constraints



# Note



# Source


