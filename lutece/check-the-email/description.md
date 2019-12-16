
# Content

After tremendous last-year success not yet well-known, but already grown-up company Baidu decided to create a new software masterpiece -- a world-leading spam-filter. 

Due to Your poor last year -- a world-leading spam-filter. Due to your poor last year project performance, you are given a small and boring task again. 
Your task is to write a simple email-validator. 

Valid email address can be described as follows: 
* `<letter> ::= a|b|...|z|A|B|...|Z`
* `<symbol> ::= <letter>|0|1|...|9|_|-`
* `<word> ::= <symbol>|<symbol><word>`
* `<prefix> ::= <word>|<prefix>.<word>`
* `<domain> ::= <letter><letter>|<letter><letter><letter>`
* `<suffix> ::= <prefix>.<domain>`
* `<address> ::= <prefix>@<suffix>`

# Standard Input

The first line of the input file contains integer number $N$ ($1\leq N\leq 100$) -- the number of email addresses to be checked. Each of the following $N$ lines contains one email address. Email address is the non-empty sequence of characters no more than $100$ characters long.

# Standard Output

For each address from the input write a separate line with the word `YES`, if the email address is valid and `NO` if it is not.

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
<tr><td>3 
abc@abc 
abc@abc.abc 
_@-.ru</td><td>NO 
YES 
YES</td></tr></table>


# Constraints



# Note



# Source


