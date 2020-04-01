
# Description

<div class="content"><p><span style="font-size: medium">Farmer John has returned to the County Fair so he can attend the special events (concerts, rodeos, cooking shows, etc.). He wants to attend as many of the N (1 &lt;= N &lt;= 10,000) special events as he possibly can. He&#39;s rented a bicycle so he can speed from one event to the next in absolutely no time at all (0 time units to go from one event to the next!). Given a list of the events that FJ might wish to attend, with their start times (1 &lt;= T &lt;= 100,000) and their durations (1 &lt;= L &lt;= 100,000), determine the maximum number of events that FJ can attend. FJ never leaves an event early.</span></p>
<p><span style="font-size: medium"> </span></p>
<p><span style="font-size: medium">有N个节日每个节日有个开始时间,及持续时间. 牛想尽可能多的参加节日,问最多可以参加多少. 注意牛的转移速度是极快的,不花时间.</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer, N. </span></p>
<p><span style="font-size: medium">* Lines 2..N+1: Each line contains two space-separated integers, T and L, that describe an event that FJ might attend.</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer that is the maximum number of events FJ can attend. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">7               <br/>
1 6<br/>
8 6<br/>
14 5<br/>
19 2<br/>
1 8<br/>
18 3<br/>
10 6<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
Graphic picture of the schedule:<br/>
         11111111112<br/>
12345678901234567890---------这个是时间轴.<br/>
--------------------<br/>
111111 2222223333344<br/>
55555555 777777  666<br/>
<br/>
这个图中1代表第一个节日从1开始,持续6个时间,直到6.<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
FJ can do no better than to attend events 1, 2, 3, and 4.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

