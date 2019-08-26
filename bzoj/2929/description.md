
# Description

<div class="content"><div>
<div>洞穴学者在Byte Mountain的Grate Cave里组织了一次训练。训练中，每一位洞穴学者要从最高的一个室到达最底下的一个室。他们只能向下走。一条路上每一个连续的室都要比它的前一个低。此外，每一个洞穴学者都要从最高的室出发，沿不同的路走到最低的室。</div>
<div>限制：</div>
<div>1.起点连接的通道同一时间只能容纳一个人通过</div>
<div>2.终点连接的通道同一时间只能容纳一个人通过</div>
<div>3.其他边都很宽敞，同一时间可以容纳无限多的人</div>
<div>问：可以有多少个人同时参加训练？</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div> </div>
<div style="text-indent: 21.75pt"><span style="font-size: medium">第一行有一个整数n(2&lt;=n&lt;=200)，等于洞穴中室的个数。用1~n给室标号，号码越大就在越下面。最高的室记为1，最低的室记为n。以下的n-1行是对通道的描述。第I+1行包含了与第I个室有通道的室（只有比标号比I大的室）。这一行中的第一个数是m,0<i>&lt;=</i>m<i>&lt;=</i>(n-i+1)，表示被描述的通道的个数。接着的m个数字是与第I个室有通道的室的编号。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div> </div>
<div style="text-indent: 21.75pt"><span style="font-size: medium">输出一个整数。它等于可以同时参加训练的洞穴学者的最大人数。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">12<br/>
4 3 4 2 5<br/>
1 8<br/>
2 9 7<br/>
2 6 11<br/>
1 8<br/>
2 9 10<br/>
2 10 11<br/>
1 12<br/>
2 10 12<br/>
1 12<br/>
1 12</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

