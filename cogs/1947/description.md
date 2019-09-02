

# 题目描述



# 输入格式



# 输出格式



# 样例输入


<pre>5 2
0 0
8 3
1 1
10 -5
2 2</pre>

# 样例输出


<pre>4</pre>

# 提示



# 来源


<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
Unhappy with the poor health of his cows, Farmer John enrolls them in
</p>
<p>
an assortment of different physical fitness activities.  His prize cow
</p>
<p>
Bessie is enrolled in a running class, where she is eventually
</p>
<p>
expected to run a marathon through the downtown area of the city near
</p>
<p>
Farmer John&#39;s farm!
</p>
<p>
The marathon course consists of N checkpoints (3 &lt;= N &lt;= 500) to be
</p>
<p>
visited in sequence, where checkpoint 1 is the starting location and
</p>
<p>
checkpoint N is the finish.  Bessie is supposed to visit all of these
</p>
<p>
checkpoints one by one, but being the lazy cow she is, she decides
</p>
<p>
that she will skip up to K checkpoints (K &lt; N) in order to shorten her
</p>
<p>
total journey.  She cannot skip checkpoints 1 or N, however, since
</p>
<p>
that would be too noticeable.
</p>
<p>
Please help Bessie find the minimum distance that she has to run if
</p>
<p>
she can skip up to K checkpoints.  
</p>
<p>
Since the course is set in a downtown area with a grid of streets, the
</p>
<p>
distance between two checkpoints at locations (x1, y1) and (x2, y2) is
</p>
<p>
given by |x1-x2| + |y1-y2|.
</p>
<p>
INPUT:
</p>
<p>
The first line gives the values of N and K.
</p>
<p>
The next N lines each contain two space-separated integers, x and y,
</p>
<p>
representing a checkpoint (-1000 &lt;= x &lt;= 1000, -1000 &lt;= y &lt;= 1000).
</p>
<p>
The checkpoints are given in the order that they must be visited.
</p>
<p>
Note that the course might cross over itself several times, with
</p>
<p>
several checkpoints occurring at the same physical location.  When
</p>
<p>
Bessie skips such a checkpoint, she only skips one instance of the
</p>
<p>
checkpoint -- she does not skip every checkpoint occurring at the same
</p>
<p>
location.
</p>
<p>
SAMPLE INPUT:
</p>
<p>
5 2
</p>
<p>
0 0
</p>
<p>
8 3
</p>
<p>
1 1
</p>
<p>
10 -5
</p>
<p>
2 2
</p>
<p>
OUTPUT:
</p>
<p>
Output the minimum distance that Bessie can run by skipping up to K
</p>
<p>
checkpoints.  In the sample case shown here, skipping the checkpoints
</p>
<p>
at (8, 3) and (10, -5) leads to the minimum total distance of 4.
</p>
<p>
SAMPLE OUTPUT:
</p>
<p>
4
</p>
<p>
<br/>
</p>
