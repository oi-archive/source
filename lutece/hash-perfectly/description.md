
# Content

In computing, a hash table is a data structure used to implement an associative array, a structure that can map keys to values.

A hash table uses a hash function to compute an index into an array of buckets or slots, from which the desired value can be found. A common hash function is $index=key\ \%\ array\\_size$ ($\%$ is modulo operator), but it may cause some collisions.

For example, if keys are $1,2,6,10$, and we choose $array\\_size=4$, the indexes will be $1,2,2,2$, where some collisions happen.

To solve the collision, we can use the method known as separate chaining with linked lists.

Seeing the example again, when we try to insert $6$, because its index $2$ is used, we build a linked list in index $2$, and there would be $2\rightarrow 6$ in index $2$. Insert $10$ next, there would be a linked list $2\rightarrow 6\rightarrow 10$ in index 2.

<center>![title](/source/lutece/hash-perfectly/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTMxNC8yMDE2MDQwMjEwNTI0NDI4OTcuUE5H.PNG)</center>

To calculate the efficiency of the hash function, we define a value called $ASL$ (Average search length):
$$ASL=\frac{1}{n}\sum_{i=1}^{n}c_i$$
$c_i$ is the number of times to compare when we search the $i^{th}$ key.

Using the example above again, $c_1=1,c_2=1,c_3=2,c_4=3$, so $ASL=\frac{1}{4}(1+1+2+3)=1.75$.

It's obvious that $ASL$ can minimize when we choose a sufficiently large $array\\_size$, but in fact due to the limitation of memory, $array\\_size$ must be no more than $limit$, i.e., $1\leq array\\_size\leq limit$.

Now you are given n keys, try to choose a proper $array\\_size$ to minimize $ASL$. If there are multiple answers, choose the smallest one.

# Standard Input

The first line contains two integers $n$ and $limit$.

The second line contains $n$ integers, where $i^{th}$ integer indicates the $i^{th}$ key.

$1\leq n, limit, key\leq 2*10^5$

# Standard Output

Print the smallest $array\\_size$ which can minimize $ASL$.

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
<tr><td>4 4
1 2 6 10</td><td>3</td></tr></table>


# Constraints



# Note

In sample,

if $array\\_size=4$, the indexes will be $1,2,2,2$, so $ASL=\frac{1}{4}(1+1+2+3)=1.75$;

if $array\\_size=3$, the indexes will be $1,2,0,1$, so $ASL=\frac{1}{4}(1+1+1+2)=1.25$;

if $array\\_size=2$, the indexes will be $1,0,0,0$, so $ASL=\frac{1}{4}(1+1+2+3)=1.75$;

if $array\\_size=1$, the indexes will be $0,0,0,0$, so $ASL=\frac{1}{4}(1+2+3+4)=2.50$;

So the answer is $3$.

# Source


