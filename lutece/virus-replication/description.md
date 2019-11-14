
# Content

Some viruses replicate by replacing a piece of DNA in a living cell with a piece of DNA that the virus carries with it. This makes the cell start to produce viruses identical to the original one that infected the cell. A group of biologists is interested in knowing how much DNA a certain virus inserts into the host genome. To find this out they have sequenced the full genome of a healthy cell as well as that of an identical cell infected by a virus.

The genome turned out to be pretty big, so now they need your help in the data processing step. Given the DNA sequence before and after the virus infection, determine the length of the smallest single, consecutive piece of DNA that can have been inserted into the first sequence to turn it into the second one. A single, consecutive piece of DNA might also have been removed from the same position in the sequence as DNA was inserted. Small changes in the DNA can have large effects, so the virus might insert only a few letters, or even nothing at all.

# Standard Input

The input consists of two lines containing the DNA sequence before and after virus infection respectively. A DNA sequence is given as a string containing between $1$ and $10^5$ upper-case letters from the alphabet $(A, G, C, T)$.

# Standard Output

Output one integer, the minimum length of DNA inserted by the virus.

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
<tr><td>AAAAA
AGCGAA</td><td>3</td></tr><tr><td>GTTTGACACACATT
GTTTGACCACAT</td><td>4</td></tr></table>


# Constraints



# Note



# Source


