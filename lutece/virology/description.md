
# Content

Little is understood about the virus and the way it infects its human hosts, but what has been discovered is a peculiar pattern in human DNA that can tell virologists if a particular person is vulnerable or immune to the virus. DNA was sampled from every individual working with the CDC, and a pattern was recognized to be present in only those who were infected by the virus.

We have isolated $9$ genes within human DNA that can tell us if a person is vulnerable to infection. Most people have at least $14$ occurrences of these genes. An individual that is considered vulnerable is known to have met the following conditions:

* The individual must have exactly $14$ occurrences of the numbered DNA genes ($1-9$). You will only test samples from people that meet this condition. There will be a max of $3$ of the same gene in a test case. The order of the genes is not significant.

* Within their DNA there must be 4 total instances of triples and/or straights and $1$ pair

 * triples ($3$ of the same gene, example: [$7$ $ $ $7$ $ $ $7$]
 * straights of $3$ (examples: [$1$ $ $ $2$ $ $ $3$] [$7$ $ $ $8$ $ $ $9$] [$4$ $ $ $5$ $ $ $6$])
 * pair ($2$ of the same gene, example: [$9$ $ $ $9$])

Note: An instance of a gene cannot be reused in multiple sets

So if an individual with $14$ numbered genes in their DNA has

* $4$ triples/straights AND
* $1$ pair
then they are vulnerable. If this pattern cannot be found in an individual's DNA then that individual is $\textbf{immune}$.

Your job is to take a list of DNA samples from individuals with $14$ of the numbered genes and determine if they are vulnerable.

# Standard Input

The first number will be the number of test cases $N (1 \leq N \leq 200000)$. Following that will be $N$ lines of $14$ numbers separated by spaces indicating the genes present in the DNA.

# Standard Output

If an individual is vulnerable to the virus, output Vulnerable. Otherwise, output Immune. Output each answer on a separate line.

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
1 1 2 3 4 4 4 5 6 7 7 8 9 1
1 1 1 2 3 4 4 4 5 6 6 7 8 9</td><td>Vulnerable
Immune</td></tr></table>


# Constraints



# Note



# Source


