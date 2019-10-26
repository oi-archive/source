
# Content

Since most computers are binary machines, both powers of two and problems that involve only two values are important to computer scientists. The following problem has to do with powers of two and the digits $1$ and $2$.

Some powers of two as decimal values, such as

$29 = 512$ and $289 = 618,970,019,642,690,137,449,562,112$

end in a string of digits consisting only of $1$'s and $2$'s ($12$ for $29$ and $2112$ for $289$ ). In fact, it can be proved that:

For every integer $R$ , there exists a power of $2$ such that $2K$ uses only the digits $1$ and $2$ in its last $R$ digits. 

This is shown a bit more clearly in the following table: 

![title](/source/lutece/the-two-note-rag/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzQ5LzIwMTQwNDEwMjE1MDM1MDM1MjMucG5n.png)

Your job is to write a program that will determine, for given $R$ , the smallest $K$ such that $2K$ ends in a string of $R$ digits containing only $1$'s and $2$'s.

# Standard Input

The first line of the input contains a single decimal integer, $N$ , $1\leq N\leq 50$ , the number of problem data sets to follow. Each data set consists of a single integer $R$ , $1\leq R\leq 20$ , for which we want a power of $2$ ending in a string of $R$ $1$'s and $2$'s.

# Standard Output

For each data set, you should generate one line of output with the following values: The data set number as a decimal integer (start counting at one), a space, the input value $R$ , another space, and the smallest value $K$ for which $2^K$ ends in a string of $R$ $1$'s and $2$'s.

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
<tr><td>6 
1 
2 
4 
5 
7 
15</td><td>1 1 1 
2 2 9 
3 4 89 
4 5 589 
5 7 3089 
6 15 11687815589</td></tr></table>


# Constraints



# Note



# Source


