
# Content

Employees of Baidu like to play a game called Making Numbers. It goes like this: there are two players in the game, one is called little A, the other little B. There are some cards with a number on each one of them, little A chooses a number $X$ from $1$ to $N$ randomly, while little B has to choose some cards, the sum of which equals $X$. Now there are already $M$ cards with numbers, and $K$ blank cards. At the beginning of the game, little B is allowed to write numbers on the blank cards. Now little B wants to know, if it is possible to write some numbers that will assure him of the victory, that is to say, if it is possible for him to make up any number from $1$ to $N$ with the cards.

# Standard Input

The input consists of several test cases. The first line is an integer $T$ , in the second line of each case are $3$ numbers, $N,M,K$, the second line shows the number that is already written on $M$ cards. $1 \leq N \leq 99999999,0 \leq M \leq 19,1 \leq K \leq 19$ The numbers in the second line are above $0$, smaller than or equals $N$, in non-descending order.

# Standard Output

If little B can make it, output `YES`, else output `NO`.

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
15 0 4
12 3 2
3 3 3
13 3 2
3 3 3</td><td>YES
YES
NO</td></tr></table>


# Constraints



# Note



# Source


