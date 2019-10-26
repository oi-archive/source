
# Description

<div class="content"><div class="ptx" lang="en-US"><span style="font-size: medium">Lineland is a strange country. As the name suggests, it&#39;s shape (as seen from above) is just a straight line, rather than some two-dimensional shape. The landscape along this line is very mountainous, something which occasionally leads to some problems. One such problem now occurs: in this modern era the king wants to build an airport to stimulate the country&#39;s economy. Unfortunately, it&#39;s impossible for airplanes to land on steep airstrips, so a horizontal piece of land is needed. To accommodate for the larger airplanes, this strip needs to have length at least L. <br/>
<br/>
Over the years, the inhabitants of Lineland have become very proficient in flattening pieces of land. Given a piece a land, they can remove rock quickly. They don&#39;t want to add rock for that may lead to an unstable landing strip. To minimize the amount of effort, however, they want to remove the least amount of rock necessary to reach their goal: a flat piece of land of length L. What is this minimum amount? Because of the low-dimensional nature of Lineland, the amount of rock that needs to be removed is measured as the total area of land above the place where the landing strip is placed, rather than the volume (so in the Figure below, the amount of land removed is given by the lightly shaded area). <br/>
</span>
<div align="center"><span style="font-size: medium"><img src="/source/bzoj/2583/img/aHR0cDovL3Bvai5vcmcvaW1hZ2VzLzMxMjdfMS5qcGc=.jpg" alt=""/></span></div>
<span style="font-size: medium"><br/>
</span></div>
<p></p></div>

# Input

<div class="content"><div class="ptx" lang="en-US"><span style="font-size: medium">One line with a positive number: the number of test cases (at most 25). Then for each test case: </span>
<ul>
    <li><span style="font-size: medium">One line with an integer N, 2 ≤ N ≤ 500, the number of points, and an integer L, 1 ≤ L ≤ 10 000, the necessary length to flatten. </span></li>
    <li><span style="font-size: medium">lines with two integers xi and yi with 0 ≤ xi, yi ≤ 10 000 describing the landscape of Lineland. The xi are in (strictly) ascending order. At position xi the height of the landscape is yi. Between two xi the landscape has constant slope. (So the landscape is piecewise linear). The difference between xN and x1 is greater than or equal to L.</span></li>
</ul>
</div></div>

# Output

<div class="content"><div class="ptx" lang="en-US"><span style="font-size: medium">For each test case, output one line with the minimum amount of rock which must be removed in order to build the airport. The answer should be given as a floating point number with an absolute error of at most 10<sup>−3</sup>.</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
3 5<br/>
0 2<br/>
4 2<br/>
14 0<br/>
4 3<br/>
0 2<br/>
2 0<br/>
4 0<br/>
5 3<br/>
3 10<br/>
10 2<br/>
30 2<br/>
35 7<br/>
2 777<br/>
222 333<br/>
4444 5555<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
0.9000<br/>
0.3750<br/>
0.0000<br/>
373362.4867<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

