<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Hexagon Coin Toss is a simple game played on a Hexagon chessboard. Players toss a coin on the chessboard and see how many hexagons intersect with the coin.<br/>
　　To simplify the problem, assume that the side length of each hexagon is 1cm and the radius of the coin will not exceed 0.5cm, which means that the coin can intersect with no more than three hexagons.<br/>
<img width="322" height="218"/><br/>
　　The chessboard contains several rows, numbered from 1 to <i>M</i> from top to bottom, of hexagons. The numbers of hexagons in all rows with odd number are the same, so are the numbers of hexagons in all rows with even number. Note that these two numbers always differ by one. Thus, the chessboard can be uniquely characterized by a triple of numbers (<i>N</i>, <i>M</i>, <i>K</i>), where <i>N</i> is the number of hexagons in the longest row, <i>M</i> is the number of rows and <i>K</i> is the number of hexagons in the first row. For example, the chessboard shown above can be represented by the triple (4, 3, 3).<br/>
　　The center of the coin will be within the range of the chessboard and the areas outside the chessboard should not be taken into consideration. Hence the coin shown below covers only two hexagons.<br/>
<img width="299" height="204"/><br/>
　　With some possibility, the coin may ‘stand’ on the chessboard instead of ‘being laid’ on. Looking straight down at the chessboard, we will find that the board and the coin can be as follows.<br/>
<img width="413" height="210"/><br/>
　　In this case, the coin <i>a</i> covers three hexagons while the coin <i>b</i> covers two. In this problem, it is assumed that if the coin ‘stand’ on the chessboard, it must be horizontal or vertical, or specifically, parallel to the <i>X</i>-axis or <i>Y</i>-axis.<br/>
　　To conclude, there are three possibilities when a coin hits the chessboard:<br/>
　　－ The coin ‘is laid’ on the chessboard;<br/>
　　－ The coin ‘stands’ on the chessboard and is parallel to the X-axis;<br/>
　　－ The coin ‘stands’ on the chessboard and is parallel to the Y-axis.<br/>
　　It has been figured out that the probabilities of the three cases are 70%, 20% and 10%, respectively.<br/>
　　Given all the conditions, please find out the possibilities that the coin intersects with one, two and three hexagons, separately.</div>
# 输入格式

<div class="pdcont">　　The input contains multiple test cases.<br/>
　　For each case, the first line of the input contains three integers <i>N</i>, <i>M</i> and <i>K</i>, characterizing the chessboard. It is guaranteed that all input information is valid.<br/>
　　The second line is a positive real number <i>R</i>, the radius of the coin.<br/>
　　The input ends with a line of three ‘0’s. There are no empty lines between consecutive cases.</div>
# 输出格式

<div class="pdcont">　　For each test case, the case number should be output first in a line.<br/>
　　The following three lines should be the possibilities that the coin intersects with one, two and three hexagons, respectively.<br/>
　　The output format should be exactly the same as those shown in the following samples. Note that for each case, there are three spaces before the equal sign in the second line, and two in the third and the fourth line. The results should be rounded to five decimal places.<br/>
　　There should be an empty line between two consecutive cases.</div>
# 样例输入

<div class="pddata">4 5 4<br/>
0.38<br/>
4 5 3<br/>
0.26<br/>
4 2 3<br/>
0.24<br/>
0 0 0</div>
# 样例输出

<div class="pddata">Case 1:<br/>
Probability of covering 1 hexagon   = 52.98601 percent.<br/>
Probability of covering 2 hexagons  = 32.02317 percent.<br/>
Probability of covering 3 hexagons  = 14.99082 percent.<br/>
<br/>
Case 2:<br/>
Probability of covering 1 hexagon   = 65.62436 percent.<br/>
Probability of covering 2 hexagons  = 26.94496 percent.<br/>
Probability of covering 3 hexagons  = 7.43068 percent.<br/>
<br/>
Case 3:<br/>
Probability of covering 1 hexagon   = 75.30007 percent.<br/>
Probability of covering 2 hexagons  = 20.85583 percent.<br/>
Probability of covering 3 hexagons  = 3.84410 percent.</div>
# Constraints

<div class="pdcont">　　The number of test cases will not exceed 30.<br/>
　　For all test cases, 1 ≤ <i>N</i>, <i>M</i> ≤ 1000, <i>N</i> – 1 ≤ <i>K</i> ≤ <i>N</i>.</div>

</div>