
# Description

<div class="content"><p><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;">Bessie is out at the movies.  Being mischievous as always, she has decided to hide from Farmer John for L (1 &lt;= L &lt;= 100,000,000) minutes, during which time she wants to watch movies continuously. She has N (1 &lt;= N &lt;= 20) movies to choose from, each of which has a certain duration and a set of showtimes during the day.  Bessie may enter and exit a movie at any time during one if its showtimes, but she does not want to ever visit the same movie twice, and she cannot switch to another showtime of the same movie that overlaps the current showtime.  Help Bessie by determining if it is possible for her to achieve her goal of watching movies continuously from time 0 through time L.  If it is, determine the minimum number of movies she needs to see to achieve this goal (Bessie gets confused with plot lines if she watches too many movies).<br/>
</span><font face="monospace"><span style="font-size: 14px; white-space: pre-wrap;">PoPoQQQ要在电影院里呆L分钟，这段时间他要看小型电影度过。电影一共N部，每部都播放于若干段可能重叠的区间，PoPoQQQ决不会看同一部电影两次。现在问他要看最少几部电影才能度过这段时间？  注：必须看电影才能在电影院里呆着，同时一场电影可以在其播放区间内任意时间入场出场。</span></font></p>
<p></p></div>

# Input

<div class="content"><div><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;">The first line of input contains N and L. The next N lines each describe a movie.  They begin with its integer duration, D (1 &lt;= D &lt;= L) and the number of showtimes, C (1 &lt;= C &lt;= 1000).  The remaining C integers on the same line are each in the range 0..L, and give the starting time of one of the showings of the movie.  Showtimes are distinct, in the range 0..L, and given in increasing order. <br/>
</span></div>
<div>
<p></p>
</div></div>

# Output

<div class="content"><div>A single integer indicating the minimum number of movies that Bessie</div>
<div>needs to see to achieve her goal.  If this is impossible output -1</div>
<div>instead.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 100<br/>
50 3 15 30 55<br/>
40 2 0 65<br/>
30 2 20 90<br/>
20 1 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
<br/>
SOLUTION NOTES:<br/>
<br/>
Bessie should attend the first showing of the fourth movie from time 0<br/>
to time 20.  Then she watches the first showing of the first movie<br/>
from time 20 to time 65.  Finally she watches the last showing of the<br/>
second movie from time 65 to time 100.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold&amp;鸣谢18357">Gold&amp;鸣谢18357</a></p></div>

