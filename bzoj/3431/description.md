
# Description

<div class="content"><p><span style="font-size: medium;"><span id="probtext-text" class="mono prewrap"> [Brian Dean, 2014]  Bessie the cow is competing in a cross-country skiing event at the winter Moolympic games.  She starts out at a speed of 1 meter per second.  However, as she becomes more tired over time, she begins to slow down.  Each time Bessie slows down, her speed decreases: she moves at 1/2 meter per second after slowing down once, then 1/3 meter per second after slowing down twice, and so on.  You are told when and where Bessie slows down, in terms of a series of events.  An event like this:  </span></span></p>
<p><span style="font-size: medium;"><span id="probtext-text" class="mono prewrap">T 17  </span></span></p>
<p><span style="font-size: medium;"><span id="probtext-text" class="mono prewrap">means that Bessie slows down at a specific time -- here, 17 seconds into the race.  An event like this:</span></span></p>
<p><span style="font-size: medium;"><span id="probtext-text" class="mono prewrap">  D 10  </span></span></p>
<p><span style="font-size: medium;"><span id="probtext-text" class="mono prewrap">means that Bessie slows down at a specific distance from the start -- in this case, 10 meters.  Given a list of N such events (1 &lt;= N &lt;= 10,000), please compute the amount of time, in seconds, for Bessie to travel an entire kilometer.  Round your answer to the nearest integer second (0.5 rounds up to 1).</span></span></p>
<p></p>
<div>贝西正在参加一项滑雪比赛。她从起点出发的时候，速度恒定为每秒 1 米。然而，随着比赛进程的增加，她会犯很多错误，每次失误都会使她的速度下降。当她第一次失误后，速度会下降到每秒1/2 米，第二次失误后，速度会下降到每秒 1/3 米，第 k 次失误后，速度会下降到每秒 1/(k +1) 米。约翰记录了贝西的所有失误，一共有 Q 个。有两种失误，一种发生在比赛开始后的某个时间点，</div>
<div>另一种发生在赛道的某个位置上。有时，贝西可能在某个时间点到达某个位置，而恰好在这个时间点和位置上都有一次失误的记录，这两个记录要算作不同的失误，会对贝西的速度造成两次影响。比赛的终点距离起点有 1000 米，请问贝西需要多少时间才能滑过终点？</div>
<p></p>
<div>
<div></div>
</div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium;"><span id="probtext-text" class="mono prewrap">* Line 1: The value of N.  </span></span></p>
<p><span style="font-size: medium;"><span id="probtext-text" class="mono prewrap">* Lines 2..1+N: Each line is of the form &#34;T x&#34; or &#34;D x&#34;, indicating a         time event or a distance event.  In both cases, x is an         integer that is guaranteed to place the event before Bessie         reaches one kilometer of total distance.  It is possible for         multiple events to occur simultaneously, causing Bessie to         slow down quite a bit all at once.  Events may not be listed         in order.</span></span></p></div>

# Output

<div class="content"><p><span style="font-size: medium;"><span id="probtext-text" class="mono prewrap">* Line 1: The total time required for Bessie to travel 1 kilometer.</span></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
 T 30<br/>
 D 10<br/>
<br/>
 INPUT DETAILS: Bessie slows down at time t = 30 and at distance d = 10.</span></div>

# Sample Output

<div class="content"><span class="sampledata">2970 <br/>
<br/>
OUTPUT DETAILS: Bessie travels the first 10 meters at 1 meter/second, taking 10 seconds. She then slows down to 1/2 meter/second, taking 20 seconds to travel the next 10 meters. She then reaches the 30 second mark, where she slows down again to 1/3 meter/second. The remaining 980 meters therefore take her 980 * 3 = 2940 seconds. The total time is therefore 10 + 20 + 2940 = 2970.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

