
# Content

Vim is a powerful editer. 
And this problem is related to its auto-completion function.
The rule mentioned above will be different from the real function.
So be really careful.

The keys that this problem will use consist of three types.
* letter key i.e. `a`-`z`

By striking these key, a letter will be added after the current string you input.
* `backspace`

By striking backspace, the last letter in your string will be deleted.

* completion key i.e. `Ctrl+n`, `Ctrl+p`

By striking completion key, you will enter completion mode, and striking any non-completion key ends the mode.
Once you enter the completion mode, the words you have typed and whose prefix is the string you input will be listed in lexicographical order.
See the picture.

![title](/source/lutece/keystroke/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODAzLzIwMTQwMzI5MDgwNTEwMTAxMS5wbmc=.png)

strike `b`

![title](/source/lutece/keystroke/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODAzLzIwMTQwMzI5MDgwNTUxMTc5Mi5wbmc=.png)

strike `Ctrl+n`

![title](/source/lutece/keystroke/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODAzLzIwMTQwMzI5MDgwNjI1NDE5My5wbmc=.png)

strike `Ctrl+n`

![title](/source/lutece/keystroke/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODAzLzIwMTQwMzI5MDgwNjU1Mjg1NC5wbmc=.png)

strike `Ctrl+n`

![title](/source/lutece/keystroke/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODAzLzIwMTQwMzI5MDgwNzEzMDA0NS5wbmc=.png)

strike `Ctrl+p`

![title](/source/lutece/keystroke/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODAzLzIwMTQwMzI5MDgwNzIzMjU0Ni5wbmc=.png)

strike `c`

If you enter the completion mod by striking `Ctrl+n`, you will be choosing the lexicographical smallest word (top one).
And if you enter the completion mod by striking `Ctrl+p`, you will be choosing the lexicographical largest word (bottom one).

Once you are in the completion mode,  you can choose the next word (if existed) by striking `Ctrl+n`, and previous word (if existed) by striking `Ctrl+p`.

Now, given the words you have typed, and the string you want to type now, please answer the minimum times you have to strike the key.

# Standard Input

The first line of the input contains one integer $N$ ($1\leq N\leq 2000$), indicating the number of the words you have typed.
Each line of the next $N$ lines contains a word. And the total length of the words would not be larger than $2000$.
The last line of the input contains the word you want to type now. The length of that words would not be larger than $2000$.

# Standard Output

Output the minimum times you have to strike the key.

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
aaaab
aaaac
aaaad
aaaa</td><td>2</td></tr></table>


# Constraints



# Note

Striking `Ctrl+n` or `Ctrl+p` is only one keystroke.

By striking `Ctrl+n` or `Ctrl+p` followed by `backspace`, you can get `aaaa` in $2$ steps.

# Source


