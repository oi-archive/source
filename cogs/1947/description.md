# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
因为担心牛们的健康问题，FJ把为它们报了各种健身训练班。他最引以为傲的奶牛Bessie加入了一个长跑训练班，它期待自己经过训练之后能去参加马拉松比赛，赛场离FJ的牧场不远，需要穿过镇子。
</p>
<p>
马拉松场地由N（3 &lt;= N &lt;= 500）个检查站组成，选手需要按顺序经过这N个检查站，1号检查站为起点，N号检查站为终点，按规定Bessie也必须这样做，但是这个懒丫头决定偷个懒，它要跳过不超过K(K &lt; N)个检查站以缩短赛程。不过，它还算有节制，不会跳过起点和终点，毕竟这样做显得太不尊重举办方了。
</p>
<p>
请帮Bessie计算一下，如果要跳过不超过K个检查站的话，它的最小行程是多少。
</p>
<p>
由于赛场是一块划分成网格的空地，站与站之间距离的计算方法是：如果两个检查站的坐标分别为（x1,y1）和(x2,y2)，则它们之间的距离为|x1-x2|+|y1-y2|。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
第一行有两个整数，即N和K；
</p>
<p>
接下来有N行，每行有两个空格隔开的整数，x和y，表示一个检查站的坐标。检查站给出的顺序正是比赛时要求依次经过的顺序。注意跑步的路线有可能跟自己有若干次的交叉，也就是说会有一些检查站设在同一个位置，当Bessie决定跳过一个这样的检查站时，不意味着它要把设在这个点的检查站全都跳过。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
输出Bessie跳过不超过K个检查站后的最小行程数。
</p>
<h3>
【样例输入】
</h3>
<pre>5 2
0 0
8 3
1 1
10 -5
2 2</pre>
<h3>
【样例输出】
</h3>
<pre>4</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
样例解释：
</p>
<p>
跳过(8, 3)和(10, -5)两个点，得到最小行程为4.
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
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
