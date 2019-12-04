
# Content

Mzry1992 invented a new programming language, and named it `PaPaPa`. `PaPaPa` uses a pointer and the pointer moves in a code rectangle. At the beginning, the pointer located in the left-upper corner and the working direction is right. When meeting a character, it will execute a particular command. See the form below to learn about this. Given the code of the program, can you tell us the result of the program?

<table class="table">
<thead>
<tr><th>Token</th><th>Description</th></tr>
</thead>
<tbody>
<tr><td>`^`</td><td>Go up from current position</td></tr>
<tr><td>`>`</td><td>Go **right** from current position</td></tr>
<tr><td>`v`</td><td>Go up from current position</td></tr>
<tr><td>`<`</td><td>Go **left** from current position</td></tr>
<tr><td>Character `A`-`Z`</td><td>Output Character `A`-`Z`</td></tr>
<tr><td>`@`</td><td>Stop the program</td></tr>
</tbody>
</table>

Notice that if the pointer goes out of the code rectangle the program will stop too.

And if the program can’t be stop and repeatedly output a series of character, use the brackets `[]` to show that.

![title](/source/lutece/papapa/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNTQzLzIwMTQwODI1MjM0NDEyMjI5MTUuanBn.jpg)

# Standard Input

There is only one integer $T$($1\leq T\leq 50$) in the first line, indicates the number of test cases.

Then $T$ parts follows, each begin with a line with $2$ integers $N$, $M$ ($1\leq N, M\leq 200$). And there would be the code within a rectangle of a size of $N\times M$.

# Standard Output

For each part, output the result of the program.

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
1 14
HELLOWORLD@AAA
1 14
HELLOWORLD><AA
2 20
>YUKKURISHITEITTENEv
^<<<<<<<<<<<<<<<<<<<
3 7
ABCDEFv
HIJKLMN
OP^RST<</td><td>HELLOWORLD
HELLOWORLD[]
[YUKKURISHITEITTENE]
ABCDEFNTSRJC</td></tr></table>


# Constraints



# Note



# Source


