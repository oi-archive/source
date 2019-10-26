
# Content

A cryptoquote is a simple encoded message where one letter is simply replaced by another throughout the message. For example:
* Encoded: `HPC PJVYMIY` 
* Decoded: `ACM CONTEST`

In the example above, $H=A$, $P=C$, $C=M$, $J=O$, $V=N$, $Y=T$, $M=E$ and $I=S$. For this problem, you will decode messages.

# Standard Input

The first line of input contains a single integer $N$,($1\leq N\leq 1000$) which is the number of data sets that follow. Each data set consists of two lines of input. The first line is the encoded message. The second line is a $26$ character string of upper case letters giving the character mapping for each letter of the alphabet: the first character gives the mapping for $A$, the second for $B$ and so on. Only upper case letters will be used. Spaces may appear in the encoded message, and should be preserved in the output string.

# Standard Output

For each data set, you should generate one line of output with the following values: The data set number as a decimal integer (start counting at one), a space and the decoded message.

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
HPC PJVYMIY 
BLMRGJIASOPZEFDCKWYHUNXQTV 
FDY GAI BG UKMY 
KIMHOTSQYRLCUZPAGWJNBVDXEF</td><td>1 ACM CONTEST 
2 THE SKY IS BLUE</td></tr></table>


# Constraints



# Note



# Source


