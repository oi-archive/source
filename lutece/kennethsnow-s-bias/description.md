
# Content

<div class="text-right">
<i>
Take it, and you’ll change false words to true:
<br/>
I loosed, at random, vows, complaints: and you,
<br/>
you’ll see these wandering birds come home to roost.
<br/>
 You’ll see in this letter I was - take it, you must -
<br/>
more eloquent, as well, the less I was sincere!
<br/>
Take it, and be done!
<br/>
——CYRANO DE BERGERAC, by Edmond Rostand 
</i>
</div>
<br/>
Our lovely young girl zplinti1 is playing a game with bearchild. To play the game, they have to find a blackboard and a single piece of paper.

First of all, they write a string on the blackboard. After that, they take turns playing. Zplinti1 always moves first. In each step:
1. The player chooses a letter either from the leftmost or the rightmost position of the string, and erases that letter.
2. The player then write down the string remains on the blackboard on a paper.

When the blackboard is clean, the game is over. 

But who is the winner? Luckily, we have kennethsnow as a judge. He has already written some words in secret and calls those words `magic word`. When the game finishes, if zplinti1 has ever written a magic word on paper, he will win, otherwise bearchild wins. 

You see, if both of them play this game fairly, poor zplinti1 will hardly have a chance to win… But kennethsnow loves zplinti1, he told her those magic words in advance – in secret, of course! But bearchild is such a clever animal, how could they cheat under his eyes? 

So the truth is, both players know those magic words in advance, so we decided to let you, the clever programmers, know those words too. Given the original string s and some magic words, who will be the winner of the game?

# Standard Input

The first line of input contains a number $T$, indicating the number of cases($T\leq 50$).

For each case, the first line is a string s, with length no more than $100,000$. The second line is a number $n$, which is the number of magic words. Then $n$ lines comes, each with a string. They are the magic strings.

All the strings contains lowercase letters from `a` to `z` only. The total length of all magic strings in one case will be no more than $200,000$.

# Standard Output

For each case, output `Case #i: ` first. ($i$ is the number of the test case, from $1$ to $T$). Then output the name of the winner. See sample output for more details.

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
<tr><td>2
abcde
2
abc
bcde
aaaaa
1
nya</td><td>Case #1: zplinti1
Case #2: bearchild</td></tr></table>


# Constraints



# Note



# Source


