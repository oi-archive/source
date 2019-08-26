
# Description

<div class="content"><p><span style="font-size: medium">The course of Software Design and Development Practice is objectionable. ZLC is facing a serious problem .There are many points in K-dimensional space .Given a point. ZLC need to find out the closest m points. Euclidean distance is used as the distance metric between two points. The Euclidean distance between points p and q is the length of the line segment connecting them.In Cartesian coordinates, if p = (p1, p2,..., pn) and q = (q1, q2,..., qn) are two points in Euclidean n-space, then the distance from p to q, or from q to p is given by:<br/>
D(p,q)=D(q,p)=sqrt((q1-p1)^2+(q2-p2)^2+(q3-p3)^2…+(qn-pn)^2<br/>
Can you help him solve this problem?<br/>
</span></p>
<p></p>
<p><span style="font-size: medium">
</span></p><p><br/>
软工学院的课程很讨厌！ZLC同志遇到了一个头疼的问题：在K维空间里面有许多的点，对于某些给定的点，ZLC需要找到和它最近的m个点。</p>
<p>（这里的距离指的是欧几里得距离：D(p, q) = D(q, p) =  sqrt((q1 - p1) ^ 2 + (q2 - p2) ^ 2 + (q3 - p3) ^ 2 + ... + (qn - pn) ^ 2)</p>
<p>ZLC要去打Dota，所以就麻烦你帮忙解决一下了……</p>
<p>【Input】</p>
<p>第一行，两个非负整数：点数n(1 &lt;= n &lt;= 50000)，和维度数k(1 &lt;= k &lt;= 5)。<br/>
接下来的n行，每行k个整数，代表一个点的坐标。<br/>
接下来一个正整数：给定的询问数量t(1 &lt;= t &lt;= 10000)<br/>
下面2*t行：<br/>
　　第一行，k个整数：给定点的坐标<br/>
　　第二行：查询最近的m个点(1 &lt;= m &lt;= 10)</p>
<p>所有坐标的绝对值不超过10000。<br/>
有多组数据！</p>
<p>【Output】</p>
<p>对于每个询问，输出m+1行：<br/>
第一行：&#34;the closest m points are:&#34; m为查询中的m<br/>
接下来m行每行代表一个点，按照从近到远排序。</p>
<p>保证方案唯一，下面这种情况不会出现：<br/>
2 2<br/>
1 1<br/>
3 3<br/>
1<br/>
2 2<br/>
1</p>
<p></p>
<p></p></div>

# Input

<div class="content"><p><font size="4">In the first line of the text file .there are two non-negative integers n and K. They denote respectively: the number of points, 1 &lt;= n &lt;= 50000, and the number of Dimensions,1 &lt;= K &lt;= 5. In each of the following n lines there is written k integers, representing the coordinates of a point. This followed by a line with one positive integer t, representing the number of queries,1 &lt;= t &lt;=10000.each query contains two lines. The k integers in the first line represent the given point. In the second line, there is one integer m, the number of closest points you should find,1 &lt;= m &lt;=10. The absolute value of all the coordinates will not be more than 10000.<br/>
There are multiple test cases. Process to end of file.<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">For each query, output m+1 lines:<br/>
The first line saying :”the closest m points are:” where m is the number of the points.<br/>
The following m lines representing m points ,in accordance with the order from near to far<br/>
It is guaranteed that the answer can only be formed in one ways. The distances from the given point to all the nearest m+1 points are different. That means input like this:<br/>
2 2<br/>
1 1<br/>
3 3<br/>
1<br/>
2 2<br/>
1<br/>
will not exist.<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2<br/>
1 1<br/>
1 3<br/>
3 4<br/>
2<br/>
2 3<br/>
2<br/>
2 3<br/>
1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">the closest 2 points are:<br/>
1 3<br/>
3 4<br/>
the closest 1 points are:<br/>
1 3<br/>
 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=k-d tree">k-d tree</a></p></div>

