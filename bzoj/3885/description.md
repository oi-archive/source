
# Description

<div class="content"><p><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;">The locations of Farmer John&#39;s N cows (1 &lt;= N &lt;= 500) are described by distinct points in the 2D plane.  The cows belong to two different breeds: Holsteins and Guernseys.  Farmer John wants to build a rectangular fence with sides parallel to the coordinate axes enclosing only Holsteins, with no Guernseys (a cow counts as enclosed even if it is on the boundary of the fence).  Among all such fences, Farmer John wants to build a fence enclosing the maximum number of Holsteins.  And among all these fences, Farmer John wants to build a fence of minimum possible area.  Please determine this area.  A fence of zero width or height is allowable.<br/>
</span><font face="monospace"><span style="font-size: 14px; white-space: pre-wrap;">坐标系上给出n个点，分”H”和”G”，一个整点坐标上至多一个点。  现在求一个不包含”G”的包含尽量多”H”的子矩形，然后在保证”H”最多的情况下还要问最小面积。  输出”H”的最大数量，和保证”H”最多时的最小矩形面积。</span></font></p>
<p></p></div>

# Input

<div class="content"><div><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;">The first line of input contains N.  Each of the next N lines describes a cow, and contains two integers and a character. The integers indicate a point (x,y) (0 &lt;= x, y &lt;= 1000) at which the cow is located. The character is H or G, indicating the cow&#39;s breed.  No two cows are located at the same point, and there is always at least one Holstein.<br/>
</span></div>
<p></p></div>

# Output

<div class="content"><div></div>
<div>of Holsteins that can be enclosed by a fence containing no Guernseys,</div>
<div>and second line should contain the minimum area enclosed by such a<span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;"><br/>
</span></div>
<div>
<p></p>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 1 H<br/>
2 2 H<br/>
3 3 G<br/>
4 4 H<br/>
6 6 H</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold&amp;鸣谢18357">Gold&amp;鸣谢18357</a></p></div>

