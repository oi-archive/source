
# Content

In a long classroom, $N$ desks are arranged in a single row, with two students sitting at each desk. 
Students are cranky because they are about to have an art class, and their professor is planning to 
examine them. 

Each student has studied art, but only to a certain level. The old professor can tell by the looks on their 
faces just how much they have studied. The professor, being an artist, uses a different coloured pencil 
for each grade. Unfortunately, today he brought only one pencil. 

In order to make the examination seem fair, he wants to choose two desks and question one student 
from **each desk** positioned between the two desks he has chosen (including the chosen desks). It is 
important that **all examined students deserve the same grades**, so he can write them down using 
his only pencil. 

The professor wants to know the maximum number of students he can examine this way, as well as 
which grade the students will get.

# Standard Input

The first line of input contains a single integer $N$ ($1 \leq N \leq 100 000$). 

Each of the following $N$ rows contains two integers: $A\_i$
 and $B\_i$
, grades deserved by students sitting at 
desk $i$ ($1 \leq A\_i
, B\_i
 \leq 5$).

# Standard Output

The first and only line of output must contain two numbers separated by a single space: the maximum 
number of students the professor can examine and the grade those students will get. 

If there are multiple solutions possible, output the one with the smallest grade.

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
<tr><td>1 
1 5</td><td>1 1</td></tr><tr><td>3 
3 5 
4 5 
1 3</td><td>2 5</td></tr><tr><td>4 
2 1 
3 2 
5 3 
2 5</td><td>2 2</td></tr></table>


# Constraints



# Note

Test cases worth $70\%$ of total points have $N \leq 100$.

# Source


