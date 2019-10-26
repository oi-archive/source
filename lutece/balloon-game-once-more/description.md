
# Content

In referees' office, a long line of balloons are prepared.
All balloons of the same color are are adjacent to each other.

But God Kufeng happened to destroy some balloons.
To help the DAGE (Aniki, Big Brother), Kennethsnow and Sakuya are going to solve it.

Luckily, all the destroyed balloons are adjacent to each other.

The destroyed balloons are shown in `?`, and Kennethsnow and Sakuya can replace those places with new balloons of any color.
The only limitation is that, all the balloons of the same color including the remaining ones and new ones are adjacent to each other, still.

So, for `a???c`, both `aabcc` and `aabdc` are OK, but they can't change the balloons to `abbac`, 
since all balloons of color a are not adjacent to each other anymore.

Kennethsnow wants the total number of different colors to be odd, while Sakuya wants it to be even.
So they decides to play a game.

And they take turns replacing a destroyed balloon with a new one. Kennethsnow moves first, then Sakuya, then Kennethsnow again ...

Each of them can choose the color of the balloon as they like, as long as the limitation is not violated.

Kennethsnow wants you to find whether he has a strategy to win(making the number of color odd), if both of them play optimally.

# Standard Input

There is one line in the input, containing a string which consists of `a` - `z` and `?`.

`a` - `z` here means $26$ kinds of different color, and the `?` means the destroyed balloon.

The length of the string will not exceed $10^5$.

# Standard Output

Output `Yes` if Kennethsnow can win, otherwise output `No`.

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
<tr><td>a?z</td><td>Yes</td></tr></table>


# Constraints



# Note



# Source


