
# Content

Marek loves dancing and he has danced a lot in the last couple of years. He has actually danced so much that he became too good in all of the traditional dances like swing, salsa, ballroom and hip-hop and now all partners he dances with can not keep up with him. Therefore he started to invent his own dances and even tries to convince other people to dance these new dances with him.

Marek got really excited when he heard about the coming wedding of his best friend Miroslav. For a whole month he worked on a special dance for the wedding. The dance was performed by $N$ people and there were $N$ marks on the floor. There was an arrow from each mark to another mark and every mark had exactly one incoming arrow. The arrow could be also pointing back to the same mark.

At the wedding, every person first picked a mark on the floor and no $2$ persons picked the same one. Then Marek played some music and every $10$ seconds there was a loud signal when all dancers had to move along the arrow on the floor to another mark. The placement of the marks was such that everybody could follow the arrow to the next mark in $10$ seconds without any trouble. If an arrow was pointing back to the same mark, the person at the mark just stayed there and maybe did some improvized dance moves on the spot.

A year has passed since Miroslav’s wedding and another wedding is coming up. Marek would like to do a similar dance at this wedding as well. He lost all the drawings he had, but luckily he found two photos from exactly when the dance started and when it ended. Marek also remembers that the signal was triggered $K$ times during the time the song was played, so people moved $K$ times along the arrows.

Given the two photos, can you help Marek reconstruct the arrows on the floor? On the two photos it can be seen for every person to which position he or she moved. Marek therefore numbered the people in the first photo from $1$ to $N$ and then wrote the number of the person whose place they took in the second photo.

Marek’s time is running out, so he is interested in any placement of arrows that could produce the two photos.

# Standard Input

The first line of the input contains two integers $N$ and $K$, $2\leq N\leq 10000$, $1\leq K\leq 10^9$. The second line of the input contains $N$ space separated integers $a\_1, \cdots, a\_N$, denoting that dancer number $i$ ended at the place of dancer number $a\_i$. You may assume that $1\leq a\_i\leq N$ for all $i$ and every number between $1$ and $N$ inclusive appears exactly once in the sequence.

# Standard Output

If it is impossible to find a placement of arrows such that the dance performed $K$ times would produce the two photos, print `Impossible`. Otherwise print $N$ numbers on a line, the $i_{th}$ number denoting to which person the arrow leads from person number $i$.

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
<tr><td>6 2
3 4 5 6 1 2</td><td>5 6 1 2 3 4</td></tr><tr><td>4 2
3 4 1 2</td><td>2 3 4 1</td></tr></table>


# Constraints



# Note



# Source


