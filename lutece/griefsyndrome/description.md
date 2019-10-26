
# Content

![title](/source/lutece/griefsyndrome/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNTQxLzIwMTQwODI1MjMzNzUyNDk1MTMuanBn.jpg)

During the endless transmigration, Madoka with her friends beat the witches time and time again. The abilities of them are different.   

If the Magical Girl’s ability is higher than the witch's, they can eliminate the witch. Otherwise they will die just as Mami san did. In order to eliminate all the witches, Magical Girls need to save their power.  So the one with lowest ability who could beat the witch would go to eliminate the witch.  

Now, they meet a series of witches again. You shoule tell them for each witch who will go to eliminate it.  

If they can't beat all the witches at all, just output `Game over.`.  

**You can assume that after each fighting with a single witch, the ability of the Magical Girl is not changed.**

# Standard Input

The first line of the input contains one integer $T$($1\leq T\leq 30$), which indicate the number of test cases.

In each test case, the first five lines indicate name and ability for the girls. Then, there will be an integer $n$ ($0<n\leq 100$) which means the number of witches. Next $n$ lines, each line indicates name and ability for a single witch.

All the names' length won't exceed $20$, and the ability won't exceed $100$. The ability of these Magical Girl are distinct.

Before each test case there will be a blank line.

# Standard Output

For each test case, if Magical Girls can beat all the witches, next $n$ lines output one of girls' names. Otherwise just output `Game over.`

Output a blank line after each case.

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

Madoka 90
Homura 87
Sayaka 65
Mami 73
Kyouko 80
4
Gertrud 68
Charlotte 80
Elly 79
Gisela 40

Homura 74
Madoka 95
Kyouko 68
Sayaka 40
Mami 77
3
Charlotte 30
Patricia 70
Walpurgis 99</td><td>Mami
Homura
Kyouko
Sayaka

Game over.</td></tr></table>


# Constraints



# Note



# Source


