
# Content

One positive integer can be represented by the product of some prime numbers.

Sort the prime numbers, such like $60=2*2*3*5$, $180=2*2*3*3*5$.

The $GCP$(Greatest Common Prefix) of two positive integers is defined as the longest prefix of the multiplication of sorted prime numbers.

For example, $GCP(60,180)=Longest\_Prefix(2*2*3*5,2*2*3*3*5)=2*2*3=12$.

Now, for a given array $A_i$, calculate
$\sum_{1\leq i<j\leq N}{GCP(A_i,A_j)}$.

# Standard Input

The first line contains a number $N$.

The second line contains $N$ integers $A_i$.

$1\leq N\leq 10^5, 1\leq A_i\leq 10^7$

# Standard Output

Output the sum described above.

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
1 2 8 5 10</td><td>13</td></tr></table>


# Constraints



# Note

In the sample,

$GCP(1,2)=GCP(1,8)=GCP(1,5)=GCP(1,10)=GCP(2,5)=GCP(8,5)=GCP(5,10)=1$,

$GCP(2,8)=GCP(2,10)=GCP(8,10)=2$.

# Source


