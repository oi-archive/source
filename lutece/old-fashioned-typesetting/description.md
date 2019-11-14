
# Content

In Olden Days, before digital typesetting (before Babbage, even), typesetting was an art, practiced by highly skilled craftsmen. Certain character combinations, such as `a-e` or `f-i` were typeset as a single character, called a ligature, to save space and to make the characters look better together on the printed page (the ligatures for `a-e` and `f-i` were `æ` and `ﬁ`, respectively; the table on the next page, lists all possible ligature combinations).

In addition, there were two different versions of the lowercase letter $s$: the `long s` and the `short s`. Only the short $s$ is used today. The rules for when to use which version are odd, but straightforward: 
1. Short $s$ is used at the end of a word, or before punctuation within a word, such as a hyphen or apostrophe: programs, success, hocus-pocus, revis’d. (programs, ſucceſs, hocus-pocus, revis'd)
2. Short $s$ is used before the letters `f`, `b`, or `k`: transfer, husband, ask, successful. (transfer, husband, ask, ſucceſsful)
3. Long $s$ is used everywhere else, except...
4. It is possible that a compound word consists of a word ending in a double s followed by a word beginning with s (this is the only situation where the sequence `sss` occurs in English text). In this case, the middle s is set short and the other two are set long: crossstitch, crossstaff. (croſsﬅitch, croſsﬅaﬀ) 

![title](/source/lutece/old-fashioned-typesetting/img/aHR0cHM6Ly9oZXJhbm8uZ2l0aHViLmlvL2ltYWdlcy9MdXRlY2UvMzQxLnBuZw==.png)

Note that a `word` is not the same thing as an `identifier.` While identifiers can contain punctuation marks such as `_` or `$`, words can contain only letters (at least as far as typographers are concerned). Therefore, identifiers like `radius3` and `adios_amigo` would be typeset as `radius3` and `adios_amigo,` respectively, rather than `radiuſ3` and `adioſ_amigo.`

# Standard Input

The first line of input contains a single integer $P$, ($1\leq P\leq 1000$), which is the number of data sets that follow. Each data set consists of a single line containing the data set number, followed by a space, followed by a string of no more than $1000$ characters.

# Standard Output

For each data set, print the data set number, a space, and the input string, with the appropriate ligature and `long s` codes substituted into the string.

The table on the above shows the code strings to use for each symbol or ligature (note that the short s remains unchanged on output; note also that `Æ` and `Œ` are the only uppercase ligatures):

**Note** that the rules for the use of long and short s can combine with these ligatures in interesting (and not always obvious) ways. For example, the input word `crossstitch` becomes `cro[longs]s[longst]itch,` not `cro[longs]s[longs]titch,`

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
1 Last night, we went to see
2 "Oedipus Rex" at the 
3 AEgyptian's theater.</td><td>1 La[longst] night, we went to [longs]ee
2 "[OE]dipus Rex" at the 
3 [AE]gyptian's theater.</td></tr></table>


# Constraints



# Note



# Source


