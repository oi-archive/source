
# Description

<div class="content"><p style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;">Just like humans enjoy playing the game of Hopscotch, Farmer John&#39;s cows have invented a variant of the game for themselves to play. Being played by clumsy animals weighing nearly a ton, Cow Hopscotch almost always ends in disaster, but this has surprisingly not deterred the cows from attempting to play nearly every afternoon.</p>
<p style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;">The game is played on an R by C grid (2 &lt;= R &lt;= 750, 2 &lt;= C &lt;= 750), where each square is labeled with an integer in the range 1..K (1 &lt;= K &lt;= R*C). Cows start in the top-left square and move to the bottom-right square by a sequence of jumps, where a jump is valid if and only if</p>
<p style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;">1) You are jumping to a square labeled with a different integer than your current square,</p>
<p style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;">2) The square that you are jumping to is at least one row below the current square that you are on, and</p>
<p style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;">3) The square that you are jumping to is at least one column to the right of the current square that you are on.</p>
<p style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;">Please help the cows compute the number of different possible sequences of valid jumps that will take them from the top-left square to the bottom-right square.</p>
<div>就像人类喜欢跳格子游戏一样，FJ的奶牛们发明了一种新的跳格子游戏。虽然这种接近一吨的笨拙的动物玩跳格子游戏几乎总是不愉快地结束，但是这并没有阻止奶牛们在每天下午参加跳格子游戏 </div>
<div>游戏在一个R*C的网格上进行，每个格子有一个取值在1-k之间的整数标号，奶牛开始在左上角的格子，目的是通过若干次跳跃后到达右下角的格子，当且仅当格子A和格子B满足如下条件时能从格子A跳到格子B： </div>
<div>1.B格子在A格子的严格右方(B的列号严格大于A的列号) </div>
<div>2.B格子在A格子的严格下方(B的行号严格大于A的行号) </div>
<div>3.B格子的标号和A格子的标号不同 </div>
<div>请你帮助奶牛计算出从左上角的格子到右下角的格子一共有多少种不同的方案</div>
<pre style="font-size: 14px;"></pre>
<p></p></div>

# Input

<div class="content"><div><span style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;">The first line contains the integers R, C, and K. The next R lines will each contain C integers, each in the range 1..K.</span></div>
<div>
<div>第一行包含两个整数R C K </div>
<div>接下来的R行，每行C个整数表示格子的标号</div>
</div>
<div>
<pre style="font-size: 14px;"></pre>
</div>
<p></p></div>

# Output

<div class="content"><h4 style="font-family: Raleway, &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px;">Output the number of different ways one can jump from the top-left square to the bottom-right square, mod 1000000007.</h4>
<div>一行，代表有多少种不同的方案，由于答案很大，请输出答案对1000000007取模的结果</div>
<div></div>
<pre style="font-size: 14px;"></pre>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4 4<br/>
1 1 1 1<br/>
1 3 2 1<br/>
1 2 4 1<br/>
1 1 1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

