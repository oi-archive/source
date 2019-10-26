
# Content

Mzry1992 got sick recently. He had to go to the hospital for treatment. 
The time in the hospital was very boring, so Mzry1992 designed a game and wanted 
to persuade the nurse to play with him.

The game is played as follows:
There are $n$ piles of candies on the table. Each pile has a certain number of candies.
Mzry1992 and the nurse take turns to eat candies. As the designed of the game,
Mzry1992 always starts first. When it's someone's turn to eat candies,
he must select a pile of candies (suppose the pile has $m$ candies now),
and eat $x$($0 < x \leq \left \lfloor \frac{A\times m + B}{C} \right \rfloor$) candies.
Otherwise, he loses the game.

($\lfloor x\rfloor $ indicates the largest integer which is not greater than $x$)

The nurse loved candies, so she agreed to play with Mzry1992. To start the game,
they began to prepare $n$ candy piles. After they had arranged the first $n - 1$ piles of
candies (where the number of candies in the $i\_{th}$ pile was $x_i$, $1 \leq i \leq n - 1$),
a new patient came in and the nurse had to go to take care of him.
So Mzry1992 was left alone to decide the number of candies in the last pile.
But before the nurse left, she demanded that the last pile must have no less than $L$ candies
and no more than $R$ candies, i.e. , $L \leq x_n \leq R$.

Mzry1992 agreed with the nurse's demand, since it would be unfair for the nurse if Mzry1992
could place any number of candies in the last pile. Now Mzry1992 wondered, if both he
and the nurse play with their best strategies, how many different ways of placing candies
in the last pile will make him lose?

# Standard Input

The first line has a number $T$ ($T\leq 20$) , indicating the number of test cases.

Then there comes the input of each test case.

The input of each test case has four lines.

The first line contains three integers $A$, $B$, and $C$($0\leq A, B\leq 10^{18}$, $1\leq C\leq 10^{18}$), which are defined above in the description.

The second line contains an integer $n$($1\leq n\leq 10$), indicating the number of candy piles.

The third line contains $n - 1$ integers $x\_1$, $x\_2$, $\cdots$, $x\_{n-1}$, where $x\_i$($1\leq x\_i\leq 10^{18}$)
indicates the number of candies in the $i\_{th}$ pile.

The fourth line contains two integers $L$ and $R$($1\leq L\leq R\leq 10^{18}$), which constrains the number of the
$n_{th}$ pile in the range $[L, R]$, i.e., $L \leq x\_n \leq R$.

We can guaranteed that at any time $\left \lfloor \frac{A\times m + B}{C} \right \rfloor$ will no more than $10^5$.

# Standard Output

For every case, you should output `Case #t: ` at first, without quotes. 
The $t$ is the case number starting from $1$.

Then follows the answer. which indicates the number of different ways of placing
candies in the $n\_{th}$ pile that will make Mzry1992 lose.

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
1 2 3
3
3 4
1 8</td><td>Case #1: 1</td></tr></table>


# Constraints



# Note



# Source


