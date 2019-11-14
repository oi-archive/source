
# Content

If you have ever read Harry Potter, you would know that the evil and powerful wizard, Lord Voldemort, create this name by permuting his original name, `Tom Marvolo Riddle`, to `I am Lord Voldemort`.

Write a program to check whether it is possible to transform a given word to another by permuting its letters. 

The length of any given word is greater than $0$ and no larger than $50$.

# Standard Input

The first line is an integer $T$, the number of test cases. Following $T$ lines each contains two words separated by spaces.

# Standard Output

For each test case, Output on a line `Yes` if it is possible to do the transformation, otherwise output `No` instead. 

Permuting a word is to change the order of its letters, but no new letters can be added and no original letters can be deleted. For example, one can transform `aabc` to `abca`, but not to `bac`, `abc`, `aabca`, `aacbb`.

Words will contain letters only(`a`-`z`, `A`-`Z`).

A word won't contain any white spaces in itself.

The given two words will not be the same.

You should ignore case when comparing words, i.e. `a` is the same as `A`, `b` is the same as `B`, etc.

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
TomMarvoloRiddle IamLordVoldemort
stop pots
abbc bac
InternetAnagramServer IRearrangementServant</td><td>Yes
Yes
No
Yes</td></tr></table>


# Constraints



# Note



# Source


