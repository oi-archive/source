
# Content

One day kennethsnow was so boring, so he thought up a string, and write it on a paper, he wrote the same string again and again, say $K$ times in total. Kennethsnow looked at the string, and thought it as beautiful.

So, a beautiful string for kennethsnow is such a string, that is connected by $K$ exactly same strings, those strings cannot overlap. 

Later, God Kufeng came and saw the paper, Kufeng is a naughty boy (or a naughty God, you might say), he could change the string kennethsnow wrote on the paper a little bit, adding some letters at the beginning and the end. (It is also possible that he didn't change the string at all!) Kufeng looked at the new string, and thought it as beautiful.

So, a beautiful string for KuFeng is such a string, that it contains a substring that is beautiful for kennethsnow.

After a while, another naughty boy, gongbaoa, write a new string on the paper, he wonders how many substrings are there that is beautiful for Kufeng?

# Standard Input

The first line come with a number $n$ and $K$($1\leq n\leq 10^5, 1\leq K\leq 10^9$), 
the length of the string, and the times kennethsnow has written his string.

On the second lines is a string $s$ with length $n$. 
The strings only contain lowercase letters.

# Standard Output

Output the number of substrings that is beautiful for KuFeng. Same strings appearing in different positions are considered as different.

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
ababab</td><td>6</td></tr><tr><td>5 2
abcde</td><td>0</td></tr></table>


# Constraints



# Note

In the first sample, `abab`, `baba`, `ababa`, `babab`, `ababab`, are beautiful for KuFeng, and `abab` appears twice in the string.

In the second sample, there are no beautiful substrings for KuFeng.

# Source


