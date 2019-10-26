
# Content

Paul Erdos(1913-1996) is a legendary mathematician of the $20$th century(For more information about Erdos, see Problem `Erdos Number`). Erdos likes to travel and visit other mathematicians. One day he comes to a strange country named ByteLand, where people live on small islands. The islands are connected by two-way bridges and the topology of the islands is a tree(i.e. you can go from any island to any other one via bridges, and if any bridge is broken then the islands will be separated into two mutually unreachable parts). See the picture below for an example of the topology of the islands.

![.*](/source/lutece/erdos-travel/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNzcvMjAxNDAxMTMwMjUzMTc0ODMyLmdpZg==.gif)

Erdos has heard before from legends that on each island of ByteLand lives a great mathematician, so he devised the following visiting plan before he arrives here: On each day he would randomly choose an island different from the one he is currently on and go to visit the mathematician there. He would spend the whole day on that island, discussing mathematical problems with his host, and moves on again the next day. Note Erdos might visit the same mathematician twice during a series of days. 

For example, in the picture above, assume Erdos initially arrives in island $1$ on the first day, he would randomly choose from islands 
$2$, $3$, $4$, $5$ and $6$ as his next stop and travels there. If he chooses island $2$, then on the second day his choice would be $1$, $3$, $4$, $5$ or $6$.

Although Erdos is very enthusiastic about his traveling plan, he hates to cross the old bridges every day! However he still stipulates to his random-traveling plan, because he is a strong believer in probability theory and he thinks that this is the best way to maximize the chance of discovering new mathematic theorems.

Now Erdos would like to know, if his choice in each day is purely random(i.e. if there are n choices, then each one will be chosen with probability of $1/n$), what is the expected(i.e. average) number of bridges he would cross during $R$ days. In addition, the initial island which Erdos arrives in is equally likely to be any of the islands of ByteLand.

# Standard Input

On the first line of the input file are two integers $N$ and $R$, the number of islands of ByteLand and the number of days Erdos would travel. The following $N-1$ lines each contain two number $A$ and $B$, meaning there is a bridge between island $A$ and $B$.

$1 \leq N \leq 50000, 1 \leq R \leq 10000$

Notes

* Islands are numbered from $1$ to $N$.

* The topology of the given islands is a tree.

* A fraction $\frac{A}{B}$ is reduced if and only if the greatest common divisor of $A$ and $B$ is $1$

# Standard Output

Output on a single line the expected number of bridges Erdos would cross during R days. Output the answer as a reduced fraction $A/B$.

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
<tr><td>3 1
1 2
2 3</td><td>4/3</td></tr><tr><td>2 2
1 2</td><td>2/1</td></tr></table>


# Constraints



# Note

Sample Input/Output 1 Clarification

There are $3$ islands. Connected by bridges as $1 – 2 – 3$. Erdos would travel for $1$ day. If he arrives in island $1$ initially, he would pick island $2$ or island $3$ as his next stop, both with probability of $1/2$, for an expected number of $1\times \frac{1}{2} +2\times \frac{1}{2}=\frac{3}{2}$ bridges. If he arrives in island $2$ initially, he would cross, on average, $1\times \frac{1}{2}+1\times \frac{1}{2}=1$ bridge. He would cross an expected number of $2\times\frac{1}{2}+1\times\frac{1}{2}=\frac{3}{2}$ bridges if he initially arrives in island $3$. The expected number of bridges Erdos would cross is thus $\frac{3}{2}\times\frac{1}{3}+1\times\frac{1}{3}+\frac{3}{2}\times\frac{1}{3}=\frac{4}{3}$.

Sample Input/Output 2 Clarification

There are only $2$ islands, and Erdos would travel for $2$ days. There are $2$ equally likely paths that he would take during the $2$ days: $1-2-1$ and $2-1-2$, so the answer is $(2+2)\times\frac{1}{2}=2$.

# Source


