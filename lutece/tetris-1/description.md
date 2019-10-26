
# Content

Tetris
God Wu enjoy coding some trivial games like Tetris.His Tetris is made up by 9 columns and 12 rows.  
![title](/source/lutece/tetris-1/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTE4NS8yMDE1MDgwNDIxMTcwMzkzMTQuanBn.jpg)  
The game will prossess as following steps
1.a random token will appear ,and its special square will be on (4,9);
2.the player can send a signal which means up,left,right and down to control the tokens;(If the operation which means is illegal,the operation will be skipped)
3.the token will fall a unit.(If the fall is illegal,we prossess the 4th step.Otherwise,we prossess the 2nd step)
4.If there is a horizontal line of nine units without gaps,the line will disappear and the tokens above it will fall.If a line will disappear, we will get a score and prossess 4th step again.If there is not a horizontal line of nine units without gaps,we go back to 1st step  

For the sake of debugging, God Wu just created three kinds of Tetris piece. Each type of piece do the same while receiving "left", "right" and "down" operation. specificly:  
Left: the entire piece moves left one square with the special square.  
Right: the entire piece moves right one square with the special square.  
Down: the entire piece moves down one square with the special square.  
Up: rotate 90 degree clockwise  
The original direction of each square will be same as the first pattern in each picture.  
More details see the following pictures  
and following is the detail about the "up" operatrion, notice the green square is the special square:  
1. O-type  
![title](/source/lutece/tetris-1/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTE4NS8yMDE1MDgwNDIxMTgwNTU0NDUuanBn.jpg)  
2. I-type  
![title](/source/lutece/tetris-1/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTE4NS8yMDE1MDgwNDIxMTgxMTc4NzYuanBn.jpg)  
3. J-type  
![title](/source/lutece/tetris-1/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTE4NS8yMDE1MDgwNDIxMTgxNjIzODcuanBn.jpg)  
God Wu begins to test the game after finishing coding, and ran a lot of data. However, he find score record is omitted. So he ask you to finish it.

# Standard Input

Multiple testcase. The first line is an integer T, refers the case number, followed by T case, each case containing three lines:

The first line is n, refers the number of falling pieces.

Next line is a string s(|s|<=1000), which shows the operation God Wu made from the begining of the Game to the End of the last piece stop moving.

The third line has n integers, the ith integer ai represent the type of the ith piece.(0 is for O-type, 1 is for I-type and 2 is for J-type)

# Standard Output

For each test case, output the case number and the score obtained from operation sequence. Format should be "Case #X: Y",X is the case number and Y is the score.

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
18
waaasspdwsspppwwdddssaaassswdddsswwaasssdddddswwwwwdssaaasssdddsssddasswwaasppddddssaaasssaassswssssddssss
1 1 2 2 1 2 0 2 2 1 0 2 0 2 0 2 1 1
</td><td>Case 1: 6</td></tr></table>


# Constraints



# Note

w  --  up  
a   --  left  
s   --  down  
d  --  right  
p  --  passed(no operation)

# Source


