
# Description

<div class="content"><div>ZCC loves studying,so he rarely goes home. One day he suddenly wants to go home,so he gets information about the city and calculates the minimal time to go home(He can start at any time after time 0 or exactly at time 0), if he thinks the time isn&#39;t too long, he will go home. But going home will make ZCC spend less time on study, ZCC&#39;s teacher GPS doesn&#39;t want him to go home, so GPS controls all the traffic lights and they will never become green twice(That means when a light becomes red,it will never become green). At the beginning all the lights are red.</div>
<div>As the end of the year is coming, in order to make the time shorter, ZCC can go through exactly one red light(Anyway, next year you will have 12 points again). But the problem becomes very hard and ZCC doesn&#39;t know how to calculate. He wants you to give him the answer.</div>
<div>ZCC&#39;s city is very rich, so the traffic network forms a grid graph. On each intersection point(except the 4 corners) there are traffic lights. When the red light is on, ZCC can only turn right; When the green lights is on, ZCC can go straight, turn right, turn left or turn around as he like(ZCC can only turn around on intersection points). When ZCC starts from school, he can choose any direction to go(That is, the traffic light on the starting point can&#39;t affect him).</div>
<p></p></div>

# Input

<div class="content"><div>There are multiple test cases end with EOF(no more than 10 test cases).</div>
<div>The first line: two integers n,m indicating the size of ZCC&#39;s city&#39;s traffic network(2&lt;=n,m&lt;=20) </div>
<div>Next n lines each line contain m numbers, the i+1-th line&#39;s j-th number w1[i][j] indicating the first red light&#39;s end time of the point (i,j)</div>
<div>Next n lines each line contain m numbers, the n+i+1-th line&#39;s j-th number w2[i][j] indicating the green light&#39;s end time of the point (i,j) (1&lt;=w1[i][j]&lt;=w2[i][j]&lt;=2000000)(If w1[i][j] equals to w2[i][j], it means that the light is always red. Otherwise, in [ w1[i][j]+1, w2[i][j] ] the green light is on)</div>
<div>(Because the corners don&#39;t have lights, you can ignore the value in the corners)</div>
<div>Next n lines each line contain m-1 numbers, the 2*n+i+1-th line&#39;s j-th number l1[i][j] indicating the length between point(i,j) and point(i,j+1)</div>
<div>Next n-1 lines each line contain m numbers, the 3*n+i+1-th line&#39;s j-th number l2[i][j] indicating the length between point(i,j) and point(i+1,j) (1&lt;=l1[i][j],l2[i][j]&lt;=100000)</div>
<div>Next line contain 4 numbers sx,sy,tx,ty indicating the school&#39;s coordinate is (sx,sy) and home&#39;s coordinate is (tx,ty).</div>
<p></p></div>

# Output

<div class="content"><div>
<div>Multiple test cases. Each test case output the minimal time to travel. If there&#39;s no solution, output -1.</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 2<br/>
0 0<br/>
0 0<br/>
0 0<br/>
0 0<br/>
1<br/>
2<br/>
3 5<br/>
1 1 2 2<br/>
4 3<br/>
0 1 0<br/>
1 1 1<br/>
8 1 1<br/>
0 9 0<br/>
0 1 0<br/>
1 1 1<br/>
9 1 1<br/>
0 99 0<br/>
1 1<br/>
1 1<br/>
1 1<br/>
1 1<br/>
9 4 1<br/>
1 1 1<br/>
1 1 1<br/>
1 2 4 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1: 5<br/>
Case #2: 8</span></div>

# Hint

<div class="content"><p></p><div>[Explanation of Sample 2]</div><br/>
<div>time 4:at (1,2)</div><br/>
<div>time 5:at (1,3)</div><br/>
<div>time 6:at (2,3)</div><br/>
<div>time 7:at (2,2)</div><br/>
<div>time 8:at (3,2)(7-&gt;8 run the red light)</div><br/>
<div>time 9:at (3,1)</div><br/>
<div>time 10:at (4,1)</div><br/>
<div>time 11:at (4,2)</div><br/>
<div>time 12:at (4,3)</div><br/>
<div>12-4=8, so ZCC spends 8 time to go home.</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 镇海中学">By 镇海中学</a></p></div>

