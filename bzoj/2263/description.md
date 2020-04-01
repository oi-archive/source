
# Description

<div class="content"><p>With a growing desire for modernization in our increasingly larger cities comes a need for new street designs. Chris is one of the unfortunate city planners responsible for these designs. Each year the demands keep increasing, and this year he has even been asked to design a completely new city. <br/>
More work is not something Chris needs right now, since like any good bureaucrat, he is extremely lazy. Given that this is a character trait he has in common with most computer scientists it should come as no surprise that one of his closest friends, Paul, is in fact a computer scientist. And it was Paul who suggested the brilliant idea that has made Chris a hero among his peers: Fractal Streets! By using a Hilbert curve, he can easily fill in rectangular plots of arbitrary size with very little work. <br/>
A Hilbert curve of order 1 consists of one &#34;cup&#34;. In a Hilbert curve of order 2 that cup is replaced by four smaller but identical cups and three connecting roads. In a Hilbert curve of order 3 those four cups are in turn replaced by four identical but still smaller cups and three connecting roads, etc. At each corner of a cup a driveway (with mailbox) is placed for a house, with a simple successive numbering. The house in the top left corner has number 1, and the distance between two adjacent houses is 10m. <br/>
The situation is shown graphically in figure 2. As you can see the Fractal Streets concept successfully eliminates the need for boring street grids, while still requiring very little effort from our bureaucrats. <br/>
</p>
<p></p>
<p></p>
<p><a href="http://poj.org/images/3889_1.png"><img alt="图片" src="/JudgeOnline/upload/201104/3889_1.png"/></a></p>
<p></p>
<p>As a token of their gratitude, several mayors have offered Chris a house in one of the many new neighborhoods built with his own new scheme. Chris would now like to know which of these offerings will get him a house closest to the local city planning office (of course each of these new neighborhoods has one). Luckily he will not have to actually drive along the street, because his new company &#34;car&#34; is one of those new flying cars. This high-tech vehicle allows him to travel in a straight line from his driveway to the driveway of his new office. Can you write a program to determine the distance he will have to fly for each offier (excluding the vertical distance at takeoff and landing)?</p>
<p></p></div>

# Input

<div class="content"><p class="pst">On the first line of the input is a positive integer, the number of test cases. Then for each test case: <br/>
A line containing a three positive integers, n &lt; 16 and h, o &lt; 2<sup>31</sup>, specifying the order of the Hilbert curve, and the house numbers of the offered house and the local city planning office.</p>
<p>n h o，n-图的阶数，h-起点编号，o-终点编号，求两点直线距离，取整，图中每条小线段长度是10 <br/>
图的规律要自己看，这题难在这个地方<br/>
</p></div>

# Output

<div class="content"><div class="ptx" lang="en-US">For each test case: <br/>
One line containing the distance Chris will have to fly to his work in meters, rounded to the nearest integer.</div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1 1 2<br/>
2 16 1<br/>
3 4 33<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">10<br/>
30<br/>
50<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=BAPC 2009&amp;鸣谢SJTU YYD">BAPC 2009&amp;鸣谢SJTU YYD</a></p></div>

