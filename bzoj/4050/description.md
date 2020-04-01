
# Description

<div class="content"><div>A very important and complicated machine consists of n wheels, numbered l, 2, . . . , n. They </div>
<div>are actually cogwheels, but the cogs are so small that we can model them as circles on the plane. </div>
<div>Every wheel can spin around its center. </div>
<div>Two wheels cannot overlap (they do not have common interior points), but they can touch. </div>
<div>If two wheels touch each other and one of them rotates, the other one spins as well, as their </div>
<div>micro-cogs are locked together. </div>
<div>A force is put to wheel I (and to no other wheel), making it rotate at the rate of exactly </div>
<div>one turn per minute, clockwise. Compute the rates of other wheels7 movement. You mav assume </div>
<div>that the machine is not jammed (the movement is physically possible). </div>
<div>
<div>给出平面上的n个齿轮，忽略齿的大小。它们不能有交集，但可以相切。当用T=1的速度推动1号齿轮时（相切的转动，可以传动），求每个齿轮的转速。你可以假定机器不会卡死。 </div>
<div>n&lt;=1000 </div>
<div>其余数字&lt;=10000 </div>
<div></div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains the number of test cases T. The descriptions of the test cases </div>
<div>follow: </div>
<div>Each test case consists of one line containing the number of wheels n (1《 n≤ 1000) . Each </div>
<div>of the following lines contain three integers x, y and r (-10 000 &lt; x, y &lt; 10 000; I≤ r≤ 10 000) </div>
<div>where (x, y) denote the Cartesian coordinates of the wheel&#39;s center and r is its radius. </div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>For each test case, output n lines, each describing the movement of one wheel, in the same </div>
<div>
<div>order as in the input. For every wheel, output either p/q clockwise or p/q counterclockwise, </div>
<div>where the irreducible fraction p/q is the number of wheel turns per minute. If q is l, output just </div>
<div>p as an integer. If a wheel is standing still, output not moving. </div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
5<br/>
0 0 6<br/>
6 8 4<br/>
-9 0 3<br/>
6 16 4<br/>
0- 11 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 clockwise<br/>
3/2 counterclockwise<br/>
2 counterclockwise<br/>
3/2 clockwise<br/>
not moving<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

