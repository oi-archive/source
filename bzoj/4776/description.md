
# Description

<div class="content"><div>
<div>modeArt critics worldwide have only recently begun to recognize the creative genius behind the great</div>
<div>bovine painter, Picowso.Picowso paints in a very particularway. She starts with an N×N blank canvas</div>
<div>, represented by an N×N grid of zeros, where a zero indicates an empty cell of the canvas. She then</div>
<div>draws N2 rectangles on the canvas, one in each of N2 colors (conveniently numbered 1…N2). For examp</div>
<div>le, she might start by painting a rectangle in color 2, giving this intermediate canvas:</div>
<div>2 2 2 0 </div>
<div>2 2 2 0 </div>
<div>2 2 2 0 </div>
<div>0 0 0 0</div>
<div></div>
<div>She might then paint a rectangle in color 7:</div>
<div></div>
<div>2 2 2 0 </div>
<div>2 7 7 7 </div>
<div>2 7 7 7 </div>
<div>0 0 0 0</div>
<div></div>
<div>And then she might paint a small rectangle in color 3:</div>
<div></div>
<div>2 2 3 0 </div>
<div>2 7 3 7 </div>
<div>2 7 7 7 </div>
<div>0 0 0 0</div>
<div>Each rectangle has sides parallel to the edges of the canvas, and a rectangle could be as large as t</div>
<div>he entire canvas or as small as a single cell. Each color from 1…N^2is used exactly once, although </div>
<div>later colors might completely cover up some of the earlier colors.Given the final state of the canva</div>
<div>s, please count how many of the N^2colors could have possibly been the first to be painted.</div>
<div>
<div>给定一个n*n的矩阵，初始都为0，选择一个1到n*n的排列，然后按照这个排列的顺序，每次选择这个矩阵的一个非</div>
<div>空子矩形，然后涂上当前数字。现在给定最终的矩阵，求哪些数字可能是排列的第一位。</div>
</div>
<div></div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains N, the size of the canvas (1≤N≤1000). The next N lines describe t</div>
<div>he final picture of the canvas, each containing N integers that are in the range 0…N^2. The input i</div>
<div>s guaranteed to have been drawn as described above, by painting successive rectangles in different c</div>
<div>olors.</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Please output a count of the number of colors that could have been drawn first.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
2 2 3 0<br/>
2 7 3 7<br/>
2 7 7 7<br/>
0 0 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">14<br/>
<br/>
In this example, color 2 could have been the first to be painted. Color 3 clearly had to have been p<br/>
ainted after color 7, and color 7 clearly had to have been painted after color 2. Since we don&#39;t see<br/>
 the other colors, we deduce that they also could have been painted first.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum ">Platinum </a></p></div>

