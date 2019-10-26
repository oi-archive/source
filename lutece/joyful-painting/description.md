
# Content

You are using a painting software to draw a picture $H$ pixels in height and $W$ pixels in width.

There are $n$ kinds of black brushes in rectangle shape, and $i^{th}$ brush is $A_i$ high and $B_i$ wide.

All brushes can't be rotated, and all pixels are white initially.

You want to draw a specific picture, and now you should determine whether it is possible to draw it.

# Standard Input

The first line contains two integers $H$ and $W$: the height and the width of picture.

Then $H$ lines follow, each with a string consisting of $W$ characters with only `W`(White) and `B`(Black), showing the target picture.

The following line contains a number $n$.

Then $n$ lines follow, each line with two integers $A_i$ and $B_i$.

$1\leq W, H, A_i, B_i\leq 2000$

$1\leq n\leq 10$

# Standard Output

If it is possible to draw the target picture, print `POSSIBLE`, otherwise print `IMPOSSIBLE`.

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
<tr><td>5 5
WWWWW
WBBBW
WBBWW
WBWWW
WWWWW
3
1 3
2 2
3 1</td><td>POSSIBLE</td></tr><tr><td>3 3
BBW
WBB
WWB
1
1 2</td><td>POSSIBLE</td></tr><tr><td>4 3
WWW
WBW
WBW
WWW
1
1 2</td><td>IMPOSSIBLE</td></tr></table>


# Constraints



# Note

Please note that brushes can redraw the area that have been drawn, and can be out of bound partly.

# Source


