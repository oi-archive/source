
# Content

Jon Marius is the computer expert at his company and has now been tasked to find some software for erasing data properly. It is very important that the data should not be recoverable afterwards, so it should be overwritten on the hard drive several times. Unable to find any free program up to the task, Jon Marius decides to write such a program himself. The user interface is simple, it only asks for the file to be destroyed and $n$, the number of times it should be overwritten. This number can range from $1$ (quick deletion) to $20$ (maximum security). Jon Marius processes the file bit by bit and does not consider writing a zero where there was already a zero as really overwriting. So for each of the $n$ sweeps,
he overwrites each zero with a one and each one with a zero.

Jon Marius knows that independent testing is important, so he has asked you to write the verification routine. He will not listen to your objections to the algorithm so eventually you give in.

# Standard Input

The first line of the input contains a single integer $1\leq N\leq 20$. The two following lines each contain a string containing only the characters `0` and `1`. The first of these lines represent the bits of the file before deletion and the second the bits on the same position on the hard drive after the file has been deleted. The length of these strings are the same and between $1$ and $1000$ characters.

# Standard Output

Output a single line containing either the words `Deletion succeeded` if each bit is switched $N$ times or `Deletion failed` if this is not the case.

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
<tr><td>1
10001110101000001111010100001110
01110001010111110000101011110001</td><td>Deletion succeeded</td></tr><tr><td>20
0001100011001010
0001000011000100</td><td>Deletion failed</td></tr></table>


# Constraints



# Note



# Source


