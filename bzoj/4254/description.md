
# Description

<div class="content"><div>You own a park located on a mountain, which can be described as a sequence of n points (xi, yi) from left to right, where xi,yi&gt;0, xi&lt;xi+1, yi!=yi+1  (that means there will not be horizontal segments in the mountain skyline), illustrated below(the numbers are the corresponding x-coordinate): </div>
<div><img src="/source/bzoj/4254/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwOS9mZi5QTkc=.PNG" width="754" height="277" alt=""/></div>
<div></div>
<div>You own a park located on a mountain, which can be described as a sequence of n points (xi, yi) from left to right, where xi,yi&gt;0, xi&lt;xi+1, yi!=yi+1  (that means there will not be horizontal segments in the mountain skyline), illustrated below(the numbers are the corresponding x-coordinate): Since the mountain is very sloppy, some aerial tramways across the park would be very helpful. In the figure above, people can go from p4 to p9 directly, by taking a tram. Otherwise he must follow a rather </div>
<div>zigzag path: p4-p5-p6-p7-p8-p9. </div>
<div>Your job is to design an aerial tramway system. There should be exactly m  trams, each following a horizontal  segment in the air,  between  two points pi  and pj. &#34;Horizontal&#34; means yi=yj,  “in the air&#34; means all the points in between are strictly below, i.e. yk&lt;yi for every i&lt;k&lt;j. For example, no tram can travel between p2 and p9, because p4 is not strictly below p2-p9. However, you can have two trams, one </div>
<div>from p2 to p4, and one p4 to p9. There is another important restriction: no point can be strictly below k or more tramways, because it’ll be dangerous. For example, if k=3, we cannot build these 3 tramways simultaneously: p1-p14, p4-p9, p6-p8, because p7 would be dangerous. You want to make this system as useful as possible, so you would like to maximize the total length of all tramways. For example, if m=3, k=3, the best design for the figure above is p1-p14, p2-p4 and p4-p9,the total length is 20. If m=3, k=2, you have to replace p1-p14 with p11-p13, the total length becomes 9. </div>
<p></p></div>

# Input

<div class="content"><div>There will be at most 200 test cases. Each case begins with three integers n, m and k(1&lt;=n,m&lt;=200, 2&lt;=k&lt;=10), the number of points, the number of trams in your design and the dangerous parameter introduced earlier. The next line contains n pairs of positive integers xi and yi.(1&lt;=xi,yi&lt;=10^5).  </div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>For each test case, print the case number and the maximal sum. If it is impossible to have exactly m tramways, print -1. </div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">14 3 3 <br/>
1 8 <br/>
2 6 <br/>
3 4 <br/>
4 6 <br/>
5 3 <br/>
6 4 <br/>
7 1 <br/>
8 4 <br/>
9 6 <br/>
10 4 <br/>
11 6 <br/>
12 5 <br/>
13 6 <br/>
14 8 <br/>
14 3 2 <br/>
1 8 <br/>
2 6 <br/>
3 4 <br/>
4 6 <br/>
5 3 <br/>
6 4 <br/>
7 1 <br/>
8 4 <br/>
9 6 <br/>
10 4 <br/>
11 6 <br/>
12 5 <br/>
13 6 <br/>
14 8 </span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: 20 <br/>
Case 2: 9 </span></div>

# Hint

<div class="content"><p></p><p> 2015年湖南省大学生程序设计竞赛</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢刘汝佳先生授权使用">鸣谢刘汝佳先生授权使用</a></p></div>

