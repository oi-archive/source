
# Content

Captain Chen attended a programming contest. He was not happy with the result for the lack of first blood earned by him. 
First blood here means being the first one to solve a problem.
However, the host suddenly said that there was something wrong with the database.

The database here is quite simple, only two keys are involved, that is the team's name and it's submission result.
The name of Captain Chen's team is `Captain_Chen` itself.
And the format of the submission result is `X_ZZ`. `X` here means the id of the problem, can be one of the letter between `A` ... `Z`. `ZZ` here is the result of the submission, can be `AC` or `WA`, meaning `Accepted` or `Wrong Answer`.

Now, the host said they missed ** ONLY ONE ** submission result, thus all the submission results after that submission were wrongly placed.
Additionally, the missing submission is known to be a `Wrong Answer`, however, the actual position of the missing one is still unclear.

Captain Chen wants to know the maximum number of first blood he have a chance to earn, among all the possible positions of the missing submission.

# Standard Input

The first line of the input contains $3$ integers, $N, M, K$ $100\leq N\leq 150, 1\leq M\leq 12, 1\leq K\leq 10^6$, indicating the number of teams, the number of problems, the number of submission results.

The next $K-1$ lines contains two strings, indicating the team's name and the submission result. The id of the problem starts from `A`.

The last line contains one string, indicating the team's name.

The team's name is a string without `space`, and its length will not exceed $20$

# Standard Output

Output the maximum number of first blood he have a chance to earn in a line.

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
<tr><td>3 2 5
GOD_Kufeng A_AC
Captain_Chen B_WA
GOD_Kufeng B_AC
Daye B_AC
Captain_Chen</td><td>1</td></tr></table>


# Constraints



# Note

Thanks to the missing submission result, there will be $K$ teams' names and $K-1$ submission results.

For the sample case, a possible missing submission might be `A_WA`, if we insert this submission at the beginning, the database will look like this:

GOD_Kufeng A_WA

Captain_Chen A_AC

GOD_Kufeng B_WA

Daye B_AC

Captain_Chen B_AC

So, Captain_Chen gets the `first blood` for Problem A, however, there can be no way for him to get the `first blood` for Problem B at the same time, so the best answer is $1$.

# Source


