
# Content

OSU is a music game.

Cookiezi is an OSU player.There're $N$ beatmaps in his computer.

There're so many beatmaps that Cookiezi doesn't want to play them all within today.So he decides to choose $X$ beatmaps.

He comes up with an idea to choose those beatmaps.
1. Put all beatmaps into sequence One and number them from $1$ to $N$;
2. Get out those beatmaps which are in odd position of the sequence One to form a new sequence Two;
3. Let the remaining beatmaps to form a new sequence Three;
4. Add the sequence Two to the tail of the sequence Three to form a new sequence One.
5. repeat step $2\sim 4$ for $M-1$ times.

After all steps above,he chooses the first $X$ beatmaps to play.

Now ,$N,M,X$ are given.Cookiezi wants you to tell him what beatmaps he will choose.

Notice:the first position of a sequence is numbered $1$,the second is $2$,and so on.

# Standard Input

In the first line there's a integer $T$($T\leq 200$) means the number of cases.

In the next $T$ lines there're $3$ integer $N,M,X$($N\leq 1000000$, $M\leq 20$, $X\leq 20$, $X\leq  N$)

# Standard Output

For every case,you should output $X$ numbers,representing the beatmaps Cookiezi will choose. **A space must be output between every two numbers.There shouldn't be any other space at the end of each line.**

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
5 1 2
5 2 2
4 3 3</td><td>2 4
4 3
3 1 4</td></tr></table>


# Constraints



# Note

In the third sample.
* After $0$ times : `1 2 3 4`
* After $1$ times : `2 4 1 3`
* After $2$ times : `4 3 2 1`
* After $3$ times : `3 1 4 2`

So print `3 1 4`

# Source


