
# Content

Master Oy likes drinking tea, and he is so rich that he has a servant who specializes in pouring tea for him. The servant is called Pupil Moeis.

Today, Master Oy received n boxes of tea from the guests. These teas have various types, each of which is represented by a string of length k, and these strings consist of only 0 and 1. As everyone knows, Master Oy is a person who is willing to think, so he defines DIO value. The DIO value between the two teas is the number of different places in the string representing their type. For example, the DIO value of 00110 and 01100 is 2 because their second position and the fourth position are different. Now Master oy wants Pupil Moeis to buy him a box of new tea. The maximum DIO value between this box of new tea and n boxes of tea is called DIOSAMA value. The modest Master Oy wants to minimize the DIOSAMA value, so what kind of tea should Pupil Moeis buy? Because Pupil Moeis is a newbie in fact, the problem is too hard for him. Now Pupil Moeis wants you to tell him what type of tea he should buy.

# Standard Input

First line contains two integer $n(1{\le}n{\le}100)$ and $k(1{\le}k{\le}15)$

Next n lines, each line of a string of length k containing only ‘0’ and '1’

# Standard Output

A string of length k, if there are multiple answers, please output the one with the smallest lexicographic order.

The lexicographic order means that for each $i(1{\le}i{\lt}k)$ , if $s_1[i]=s_2[i],s_1[i+1]{\le}s_2[i+1]$ , for example 00011 is smaller than 00100 and 01 is smaller than 10.

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
<tr><td>3 3
001
101
110</td><td>000</td></tr></table>


# Constraints



# Note



# Source


