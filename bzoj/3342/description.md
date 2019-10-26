
# Description

<div class="content"><div style="margin: 7.5pt 16.45pt 0pt 0cm; line-height: 13pt"><span style="font-size: medium"><span style="color: black">Mirko and Slavko have a new board game. The game board resembles a complete infinite binary tree. More precisely, the board consists of nodes and two-way roads connecting them. The root node is located at the </span></span></div>
<div style="margin: 0cm -1.5pt 0pt 0cm; line-height: 13.5pt; text-align: left" align="left"><span style="font-size: medium"><span style="color: black">top of the board and we say it is at <i>   level zero</i>. Each node has exactly two children, the <i>    left child</i> and the </span></span></div>
<div style="margin: 0cm -1.5pt 0pt 0cm; line-height: 13.5pt; text-align: left" align="left"><span style="font-size: medium"><i><span style="color: black">right child</span></i><span style="color: black"> , located in the lower-left and the lower-right directions of the parent node. The level of a </span></span></div>
<div style="margin: 0cm 16.25pt 0pt 0cm; line-height: 12.65pt"><span style="font-size: medium"><span style="color: black">child node is one greater than the level of the parent node. In addition to roads connecting a parent node with its children, there are roads connecting all of the nodes at a particular level – for each level, starting from the leftmost node, there is a road connecting each node to the next node to the right on the same level. </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> <img height="340" width="568" alt="" src="/source/bzoj/3342/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS8xKDEpLmpwZw==.jpg"/></span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 4pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span><span style="font-size: medium"><b><span style="color: black">Figure 1: The second test example below </span></b></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.5pt 0pt 0cm; line-height: 13.5pt" align="left"><span style="font-size: medium"><span style="color: black">Each <i>path</i> through the game board is a sequence of steps, each moving from a node to a different node via </span></span></div>
<div style="margin: 0cm -1.5pt 0pt 0cm; line-height: 13.5pt" align="left"><span style="font-size: medium"><span style="color: black">a single road. Each step can be described by a single character as follows: </span></span></div>
<div style="margin: 0.5pt -1.1pt 0pt 18pt; line-height: 13.5pt" align="left"><span style="font-size: medium"><span style="color: black">· </span><span style="color: black"> </span><span style="color: black">character „1</span><span style="color: black">‟</span><span style="color: black"> describes moving from a node to its left child, </span></span></div>
<div style="margin: 0.5pt -1.1pt 0pt 18pt; line-height: 13.5pt" align="left"><span style="font-size: medium"><span style="color: black">· </span><span style="color: black"> </span><span style="color: black">character „2</span><span style="color: black">‟</span><span style="color: black"> describes moving from a node to its right child, </span></span></div>
<div style="margin: 1.5pt -1.1pt 0pt 18pt; line-height: 13.5pt" align="left"><span style="font-size: medium"><span style="color: black">· </span><span style="color: black"> </span><span style="color: black">character „U</span><span style="color: black">‟</span><span style="color: black"> describes moving from a node to its parent, </span></span></div>
<div style="margin: 0.5pt -1.1pt 0pt 18pt; line-height: 13.5pt" align="left"><span style="font-size: medium"><span style="color: black">· </span><span style="color: black"> </span><span style="color: black">character „L</span><span style="color: black">‟</span><span style="color: black"> describes moving from a node to the next node to the left on the same level, </span></span></div>
<div style="margin: 1.5pt -1.1pt 0pt 18pt; line-height: 13.5pt" align="left"><span style="font-size: medium"><span style="color: black">· </span><span style="color: black"> </span><span style="color: black">character „R</span><span style="color: black">‟</span><span style="color: black"> describes moving from a node to the next node to the right on the same level. </span></span></div>
<div style="margin: 0cm 16.8pt 0pt 0cm; line-height: 13pt"><span style="font-size: medium"><span style="color: black">For example, if we were to start at the root node and take the sequence of steps „221LU</span><span style="color: black">‟</span><span style="color: black"> we would end up in the node denoted with the letter „A</span><span style="color: black">‟</span><span style="color: black"> in the figure above. </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 10pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.1pt 0pt 0cm; line-height: 8pt" align="left"><span style="font-size: medium"><span style="color: black"> </span></span></div>
<div style="margin: 0cm -1.9pt 0pt 222.75pt; line-height: 13.5pt" align="left"><span style="font-size: medium"><b><span style="color: black">TASK </span></b></span></div>
<div style="margin: 7.5pt 16.15pt 0pt 0cm; line-height: 13pt"><span style="font-size: medium"><span style="color: black">Write a program that will, given two nodes on the board, find the smallest number of steps needed to go from one node to the other. The two nodes are given by specifying paths from the root node to them. If the two paths lead to the same node, the answer is zero. </span></span></div></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 7.5pt 16.35pt 0pt 0cm; line-height: 13pt; mso-line-height-rule: exactly; mso-layout-grid-align: none"><span style="font-size: medium"><span lang="EN-US" style="color: black; font-family: &#34;Trebuchet MS&#34;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt">The first line of input contains a sequence of at most 100 000 characters – the path from the root to the first node. </span></span><span lang="EN-US" style="font-size: 10pt; color: black; font-family: &#34;Trebuchet MS&#34;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0.5pt 16.2pt 0pt 0cm; line-height: 12pt; mso-line-height-rule: exactly; mso-layout-grid-align: none"><span style="font-size: medium"><span lang="EN-US" style="color: black; font-family: &#34;Trebuchet MS&#34;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt">The second line of input contains a sequence of at most 100 000 characters – the path from the root to the second node. </span></span><span lang="EN-US" style="font-size: 10pt; color: black; font-family: &#34;Trebuchet MS&#34;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><o:p></o:p></span></p>
<p class="MsoNormal" align="left" style="margin: 0.5pt -1.5pt 0pt 0cm; line-height: 13.5pt; text-align: left; mso-line-height-rule: exactly; mso-layout-grid-align: none"><span style="font-size: medium"><span lang="EN-US" style="color: black; font-family: &#34;Trebuchet MS&#34;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt">The two paths will be valid (it will be possible to make every move in both sequences). </span></span><span lang="EN-US" style="font-size: 10pt; color: black; font-family: &#34;Trebuchet MS&#34;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><o:p></o:p></span></p>
<p></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 7.5pt 25.85pt 0pt 0cm; line-height: 13pt; mso-line-height-rule: exactly; mso-layout-grid-align: none"><span style="font-size: medium"><span lang="EN-US" style="color: black; font-family: &#34;Trebuchet MS&#34;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt">The first and only line of output should contain a single integer - the smallest number of steps needed to go from one node to the other. </span></span><span lang="EN-US" style="font-size: 10pt; color: black; font-family: &#34;Trebuchet MS&#34;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">221LU <br/>
12L2 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

