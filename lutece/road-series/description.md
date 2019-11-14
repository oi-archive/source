
# Content

Don and Jan spend a lot of time together on the road. To pass the time, they've invented various games they can play, many of which involve license plates and road signs. One of their favorites is Road Series.

The object is to find the number $1$ on some sign, then $2$, then $3$, and so on. When they get to two digit numbers the two digits must appear directly next to each other on the sign or license plate, and any sign or license plate can provide multiple answers. For example, if they see a sign with the characters `678-43 15`, they can use the numbers $67$, $78$, $43$ and $15$ but not $84$ (dash between the two digits) or $31$ (space between the two digits). They could also use the individual digits $6$, $7$, $8$, $4$, $3$, $1$ and $5$ as well as the three digit number $678$ (if they got up that high)

When they first started playing the game, they had very strict rules about when you could find a number, namely you weren't allowed to find a number n until all the numbers $1$ through $n - 1$ were already found. They soon found that this made the game REALLY slow, so they modified the game as follows. First, they called a number n the last complete number if it was the highest number such that all the numbers from $1$ to $n$ had been found. (Initially, $0$ is the last complete number.)

Given this, Don and Jan allowed themselves to keep track of having seen some numbers beyond the last complete number $n$, so long they weren't too much bigger than $n$. More precisely, they can keep track of which numbers they've seen in a window of size $w$ beyond $n$. This allows them to remember any number they've seen up to $n + w$.

For example, suppose $w = 4$ and and the last complete number Don and Jan have seen is $19$. When they see the following sign:

`Show time at 8:25, no one under 21 admitted`

they can use the $21$, but not the $25$ (since it's not in the window). If this sign is followed by the sign:

`The FleaBag Hotel, phone 555-2520`

they can use the $20$, which now makes $21$ the last complete number, and thus can also use the $25$, since it's now in the window.

# Standard Input

The first line of the input file will contain an integer m indicating the number of test cases. Each test case will start with a pair of positive integers $k$, $w$, where $k \leq 1000$ indicates the number of signs seen by Don and Jan, and $w \leq 100$ indicates the window size. Following that will be $k$ lines each consisting of text from a sign. Each line of text may contain any combination of alphanumeric characters, punctuation and spaces, and will have length at most $1000$. Input for each sign will end with a new line.

# Standard Output

For each test case, output the case number followed by the last complete number that can be found using the signs, followed by the highest number seen within the window.

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
<tr><td>4
2 10
13
2
2 10
2
13
1 8
Tomorrow, from 12 to 2, 4-4 basketball tournament! $3 entry fee.
1 8
Tomorrow, from 11 to 7, 4-4 basketball tournament! $3 entry fee.</td><td>Case 1: 3 3
Case 2: 3 13
Case 3: 4 12
Case 4: 1 7</td></tr></table>


# Constraints



# Note



# Source


