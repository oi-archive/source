
# Description

<div class="content"><p><span style="font-size: medium">Solitaire is a game played on a chessboard 8x8. The rows and columns of the chessboard are numbered from 1 to 8, from the top to the bottom and from left to right respectively.<br/>
<br/>
There are four identical pieces on the board. In one move it is allowed to:</span></p>
<p><span style="font-size: medium">&gt; move a piece to an empty neighboring field (up, down, left or right),</span></p>
<p><span style="font-size: medium">&gt; jump over one neighboring piece to an empty field (up, down, left or right). </span></p>
<p align="center"><span style="font-size: medium"><img height="378" alt="" width="369" src="/source/bzoj/3338/img/aHR0cDovL2FjbS56anUuZWR1LmNuL29ubGluZWp1ZGdlL3Nob3dJbWFnZS5kbz9uYW1lPTAwMDAlMkYxNTA1JTJGMTUwNS5naWY=.gif"/></span></p>
<p><span style="font-size: medium">There are 4 moves allowed for each piece in the configuration shown above. As an example let&#39;s consider a piece placed in the row 4, column 4. It can be moved one row up, two rows down, one column left or two columns right.<br/>
<br/>
Write a program that:<br/>
<br/>
&gt; reads two chessboard configurations from the standard input,<br/>
<br/>
&gt; verifies whether the second one is reachable from the first one in at most 8 moves,<br/>
<br/>
&gt; writes the result to the standard output.</span></p>
<p><span style="font-size: medium"><font face="仿宋_GB2312">在一个8*8的棋盘上,方上4颗<strong><wbr/>相同</strong><wbr/>的棋子,每次可以将其中一颗棋子上下左右移动一格;如果有阻碍,也可以跳过一颗棋子.按照这样的移动规则,问是否能从给定的一种棋盘状态在8步之内移动到另一种状态</font><br/>
</span></p>
<p></p></div>

# Input

<div class="content"><p><br/>
<font size="4">Each of two input lines contains 8 integers a1, a2, ..., a8 separated by single spaces and describes one configuration of pieces on the chessboard. Integers a2j-1 and a2j (1 &lt;= j &lt;= 4) describe the position of one piece - the row number and the column number respectively. Process to the end of file.</font></p>
<p><span style="font-size: medium"><br/>
</span></p>
<p></p></div>

# Output

<div class="content"><p><br/>
<font size="4">The output should contain one word for each test case - YES if a configuration described in the second input line is reachable from the configuration described in the first input line in at most 8 moves, or one word NO otherwise.</font></p>
<p><span style="font-size: medium"><br/>
</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4 4 5 5 4 6 5<br/>
2 4 3 3 3 6 4 6<br/>
<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">YES<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=双向BFS">双向BFS</a></p></div>

