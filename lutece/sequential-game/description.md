
# Content

Sequential detector is a very important device in Hardware experiments. But is very difficult for many students such as `HeroWei`. In nearest days, his teacher Miss Fang let him simulate sequence detector. But there many sequence here ,and Miss Fang add the difficulty that when she give `HeroWei` a sequence and a string ,you must tell her how many string here in this sequence. But now Miss Fang simplified the problem for `HeroWei`, she just give `Herowei` a sequence and let `HeroWei` play a game with it.

When comes a character , it must compare with the rightmost one of sequence, if it's the same with the coming characters ,the coming one just join the string. Most the right side. Otherwise all the characters in the sequence must change its value, $0$ to $1$ and $1$ to $0$,then the coming one add to its right side. Here is an example, if there is a sequence `110` when comes a character $0$,the sequence become `1100` at last, if comes a character $1$,the sequence become `0011` at last. 

It's very difficult for `HeroWei` to play the game. Can you help him?

# Standard Input

Each line contains a composed by a string of $0$s and $1$s. the input is ended by `EOF`.

# Standard Output

For each given sequence you just play with this string as descripted above.Output a line contains two integers ,which are the number of $0$s and $1$s in the sequence after the game.

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
<tr><td>0
110
1111
1010</td><td>1 0
3 0
0 4
4 0</td></tr></table>


# Constraints



# Note

For example ,1010:  1->00->111->0000

# Source


