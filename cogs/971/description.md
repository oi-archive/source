# 题目描述


<h3>
	【题目描述】
</h3>
<div class="ptx" lang="zh-CN">
	Alex likes solving fillwords. Fillword is a word game with very simple rules. The author of the fillword takes rectangular grid (M cells width, N cells height) and P words. Then he writes letters in the cells of the grid (one letter in one cell) so that each word can be found on the grid and the following conditions are met: <br/>
<br/>
no cell belongs to more than one word <br/>
<br/>
no cell belongs to any word more than once <br/>
<br/>
Some word W (let us consider its length being k) is found on the grid if you can find such sequence of cells (x1, y1), (x2, y2), ..., (xk, yk) that: <br/>
<br/>
(xi, yi) and (xi+1, yi+1) are neighbors (|xi-xi+1| + |yi-yi+1| = 1) for each i = 1, 2, ..., k-1 <br/>
<br/>
W[i] is written in the cell with coordinates (xi, yi). <br/>
<br/>
The task is to find all the words on the grid. After they are found, you see that the letters in some cells are not used (they do not belong to any found word). You make up a secret word using these letters and win a big prize. <br/>
<br/>
To make things clear, let us consider the following example (the words are BEG and GEE): <br/>
	<center>
		<img src="http://www.poj.org/images/1629_1.jpg"/> 
	</center>
<br/>
<br/>
Your task is to help Alex to solve fillwords. You should find out which letters will be left after he finds all the words on the grid. The most difficult task -- to make up a secret word out of them -- we still reserve to Alex.
</div>
<h3>
	【输入格式】
</h3>
<div class="ptx" lang="zh-CN">
	The first line of the input file contains three integer numbers -- N, M (2 &lt;= M, N &lt;= 10) and P (P  &lt;=100). Next N lines contain M characters each, and represent the grid. The following P lines contain words that are to be found on the fillword grid. <br/>
<br/>
Fillword will always have at least one solution. All characters occurring in fillword will be capital English letters. <br/>
</div>
<h3>
	【输出格式】
</h3>
<div class="ptx" lang="zh-CN">
	Output letters from, which a secret word should be made up. Letters should be output in lexicographical order.
</div>
<h3>
	【样例输入】
</h3>
<pre class="sio">3 3 2
EBG
GEE
EGE
BEG
GEE</pre>
<h3>
	【样例输出】
</h3>
<pre class="sio">EEG</pre>
<h3>
	【来源】
</h3>
<p>
	</p><div class="ptx" lang="zh-CN" style="white-space:normal;">
		Northeastern Europe 2001, Northern Subregion
	</div>
<br class="Apple-interchange-newline"/>
POJ 1629
<p></p>
