
# Content

Freddy discovered a new procedure to grow much bigger cauliflowers. He wants to share thisfinding with his fellow gardener Tommy but he does not want anyone to steal the procedure. Sothe two gardeners agreed upon using a simple encryption technique proposed by M. E. Ohaver.

The encryption is based on the Morse code, which represents characters as variable-length sequences of dots and dashes. The following table shows the Morse code sequences for all letters:

![.*](/source/lutece/false-sense-of-security/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNzkyLzIwMTQwMzIyMjEyMDA3MjkwNS5wbmc=.png)

Note that four possible dot-dash combinations are unassigned. For the purposes of this problem we will assign them as follows (note these are not the assignments for actual Morse code):

![.*](/source/lutece/false-sense-of-security/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNzkyLzIwMTQwMzIyMjEyMTAxOTQyNi5wbmc=.png)

In practice, characters in a message are delimited by short pauses, typically displayed as spaces. Thus, the message ACM GREATER NY REGION is encoded as:

`.- -.-. -- ..-- --. .-. . .- - . .-. ..-- -. -.-- ..-- .-. . --. .. --- -.`

The Ohaver's encryption scheme is based on mutilating Morse code, namely by removing the pauses between letters. Since the pauses are necessary (because Morse is a variable-length encoding that is not prefix-free), a string is added that identifies the number of dots and dashes in each character. For example, consider the message `.--.-.--`. Without knowing where the pauses should be, this could be `ACM`, `ANK`, or several other possibilities. If we add length information, such as `.--.-.-- 242`, then the code is unambiguous.

Ohaver's scheme has three steps, the same for encryption and decryption: 
1. Convert the text to Morse code without pauses but with a string of numbers to indicate code lengths. 
2. Reverse the string of numbers. 
3. Convert the dots and dashes back into the text using the reversed string of numbers as code lengths.

As an example, consider the encrypted message `AKADTOF IBOETATUK IJN`. Converting to Morse code with a length string yields:

`.--.-.--..----..-...--..-...---.-.--..--.-..--...----. 232313442431121334242`

By reversing the numbers and decoding, we get the original message `ACM GREATER NY REGION`.

The security of this encoding scheme is not too high but Freddy believes it is sufficient for his purposes. Will you help Freddy to implement this encoding algorithm and to protect his sensitive information?

# Standard Input

The input will consist of several messages encoded with Ohaver's algorithm, each of them on one line. Each message will use only the twenty-six capital letters, underscores, commas, periods, and question marks. Messages will not exceed $1000$ characters in length.

# Standard Output

For each message in the input, output the decoded message on one line.

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
<tr><td>FENDSVTSLHW.EDATS,EULAY
TRDNWPLOEF
NTTTGAZEJUIIGDUZEHKUE
QEWOISE.EIVCAEFNRXTBELYTGD.
?EJHUT.TSMYGW?EJHOT
DSU.XFNCJEVE.OE_UJDXNO_YHU?VIDWDHPDJIKXZT?E
ADAWEKHZN,OTEATWRZMZN_IDWCZGTEPION</td><td>FALSE_SENSE_OF_SECURITY
CTU_PRAGUE
TWO_THOUSAND_THIRTEEN
QUOTH_THE_RAVEN,_NEVERMORE.
TO_BE_OR_NOT_TO_BE?
THE_QUICK_BROWN_FOX_JUMPS_OVER_THE_LAZY_DOG
ADAPTED_FROM_ACM_GREATER_NY_REGION</td></tr></table>


# Constraints



# Note

Adapted from Greater New York ACM Regionals 2001

# Source


