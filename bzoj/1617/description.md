
# Description

<div class="content"><p><span style="font-size: medium">Farmer John以及他的N(1 &lt;= N &lt;= 2,500)头奶牛打算过一条河，但他们所有的渡河工具，仅仅是一个木筏。 由于奶牛不会划船，在整个渡河过程中，FJ必须始终在木筏上。在这个基础上，木筏上的奶牛数目每增加1，FJ把木筏划到对岸就得花更多的时间。 当FJ一个人坐在木筏上，他把木筏划到对岸需要M(1 &lt;= M &lt;= 1000)分钟。当木筏搭载的奶牛数目从i-1增加到i时，FJ得多花M_i(1 &lt;= M_i &lt;= 1000)分钟才能把木筏划过河（也就是说，船上有1头奶牛时，FJ得花M+M_1分钟渡河；船上有2头奶牛时，时间就变成M+M_1+M_2分钟。后面的依此类推）。那么，FJ最少要花多少时间，才能把所有奶牛带到对岸呢？当然，这个时间得包括FJ一个人把木筏从对岸划回来接下一批的奶牛的时间。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第1行: 2个用空格隔开的整数：N 和 M </span></p>
<p><span style="font-size: medium">* 第2..N+1行: 第i+1为1个整数：M_i </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第1行: 输出1个整数，为FJ把所有奶牛都载过河所需的最少时间 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 10<br/>
3<br/>
4<br/>
6<br/>
100<br/>
1<br/>
<br/>
输入说明:<br/>
<br/>
    FJ带了5头奶牛出门。如果是单独把木筏划过河，FJ需要花10分钟，带上<br/>
1头奶牛的话，是13分钟，2头奶牛是17分钟，3头是23分钟，4头是123分钟，将<br/>
5头一次性载过去，花费的时间是124分钟。<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">50<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">输出说明:</span></p><br/>
<p><span style="font-size: medium">    Farmer John第一次带3头奶牛过河（23分钟），然后一个人划回来<br/><br/>
（10分钟），最后带剩下的2头奶牛一起过河（17分钟），总共花费的时间是<br/><br/>
23+10+17 = 50分钟。<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

