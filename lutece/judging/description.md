
# Content

![title](/source/lutece/judging/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTEyMS8yMDE1MDUxNjE3MjIyNDA5NDc1LmpwZw==.jpg)

The NWERC organisers have decided that they want to improve the automatic grading of the submissions for the contest, so they now use two systems: DOMjudge and Kattis. Each submission is judged by both systems and the grading results are compared to make sure that the systems agree. However, something went wrong in setting up the connection between the systems, and now the jury only knows all results of both systems, but not which result belongs to which submission! You are therefore asked to help them figure out how many results could have been consistent.

# Standard Input

The input consists of:

>#####one line with one integer n $(1≤n≤10^5)$, the number of submissions;
>#####n lines, each with a result of the judging by DOMjudge, in arbitrary order;
>#####n lines, each with a result of the judging by Kattis, in arbitrary order.

Each result is a string of length between 5 and 15 characters (inclusive) consisting of lowercase letters.

# Standard Output

Output one line with the maximum number of judging results that could have been the same for both systems.

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
correct
wronganswer
correct
correct
timelimit
wronganswer
correct
timelimit
correct
timelimit</td><td>4</td></tr></table>


# Constraints



# Note



# Source


