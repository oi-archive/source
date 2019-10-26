
# Content

`Kennethsnow` and `Hlwt` both love football.

One day, `Kennethsnow` wants to review the match in $2003$ between AC Milan and Juventus for the Championship Cup. But before the penalty shootout. he fell asleep.

The next day, he asked `Hlwt` for the result. `Hlwt` said that it scored $a$:$b$ in the penalty shootout.

`Kennethsnow` had some doubt about what `Hlwt` said because `Hlwt` is a fan of Juventus but `Kennethsnow` loves AC Milan. 

So he wanted to know whether the result can be a legal result of a penalty shootout. If it can be, output `Yes`, otherwise output `No`.

The rule of penalty shootout is as follows:

   * There will be $5$ turns, in each turn, $2$ teams each should take a penalty shoot. If goal, the team get $1$ point. After each shoot, if the winner can be confirmed(i.e: no matter what happened after this shoot, the winner will not change), the match end immediately.

   * If after $5$ turns the $2$ teams score the same point. A new turn will be added, until that one team get a point and the other not in a turn.

Before the penalty shootout begins, the chief referee will decide which team will take the shoot first, and afterwards, two teams will take shoot one after the other. Since `Kennethsnow` fell asleep last night, he had no idea whether AC Milan or Juventus took the first shoot.

# Standard Input

The only line contains $2$ integers $a$, $b$. Means the result that `Hlwt` said.

$0 \leq a, b \leq 10$

# Standard Output

Output a string `Yes` or `No`, means whether the result is legal.

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
<tr><td>3 2</td><td>Yes</td></tr><tr><td>2 5</td><td>No</td></tr></table>


# Constraints



# Note

The Sample $1$ is the actual result of the match in $2003$.

The Sample $2$, when it is $2$:$4$ after $4$ turns, AC Milan can score at most $1$ point in the next turn. So Juventus has win when it is $2$:$4$. So the result cannot be $2$:$5$.

This story happened in a parallel universe. In this world where we live, `kennethsnow` is a fan of Real Madrid.

# Source


