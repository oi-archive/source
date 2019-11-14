
# Content

Freddy is planning a garden party for this weekend. Many old classmates are going to pay him a visit and Freddy is thinking about some elegant and unexpected improvement of his small horticultural oasis. Inspired by the creations in his favorite gardening journals he decided to install two flower arrangements on the opposite sides of the walkway leading to his garden. To match the other plants in the vicinity, one arrangement has to be in light bronze yellow and the other in dark pastel red color. The pots in which the flowers will be placed have to be painted with the same matching colors.

Freddy knows that it is much cheaper and faster to buy new pots than to repaint existing ones.Thus, being pressed by fast-approaching date of the party, Freddy has decided to purchase flowerpots from a small company which not only can deliver pots painted with exact colors needed but they can deliver them today afternoon. The owner of the company is a Dutch artist who specializes herself in designs far from ordinary. Her very special pots are manufactured in so-called pentomino shapes and they can be flipped over so that their top side can serve as the bottom side and vice versa.

A pentomino-shaped flower pot is made of five squares welded together so that sides of any two neighboring squares always touch each other along the whole edge. In the actual pots,each square is about ten square feet, but the size does not matter for this problem, it is only important that all squares in all shapes are of the same size. There are exactly $12$ possible shapes, they are listed in the figure below and each shape is traditionally named by a letter to which it bears some resemblance. (with Freddy's favorite shape being F, of course)

![.*](/source/lutece/flower-pots/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNzg5LzIwMTQwMzIyMjA1NDU1Mzk1My5wbmc=.png)

Freddy is going to buy two yellow pots and two red pots. For aesthetical reasons, he wants both arrangements to be of equal shape. Two pots of the same color will be put on the lawn closely together so that the divisions between them will not be visible and only the outline of the whole arrangement will be important for judging the equality of shapes. In the resulting arrangements, no pots can overlap. 

Freddy has to choose the pots carefully because some pairs are clearly incompatible from this point of view (such as $W+F$ and $I+I$), some other may be compatible but it might not be immediately obvious that they really are (such as $P+U$ and $V+Z$ and their possible arrangement in the figure below). Therefore, Freddy asks you for a help. You are given two yellow pots and two red pots and your program should decide if two arrangements with the same outline can be created.

![.*](/source/lutece/flower-pots/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNzg5LzIwMTQwMzIyMjA1NjIxMjUyNC5wbmc=.png)

# Standard Input

The input contains several test cases. Each test case consists of one line. The line starts with two letters that specify the shapes of two yellow pots, then there is one space and other two letters giving the shapes of two red pots. All four letters are in uppercase and each of them is one of the $12$ valid letters listed above.

# Standard Output

For each test case, output a single line of text. The line should contain `YES` if an arrangement exists which can be composed from both pairs of yellow pots and red pots. If there is no such arrangement, the line should contain `NO`.

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
<tr><td>II PP
WF II
VZ UP</td><td>YES
NO
YES</td></tr></table>


# Constraints



# Note



# Source


