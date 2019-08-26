
# Description

<div class="content"><div>Farmer John决定为他的所有奶牛都配备手机，以此鼓励她们互相交流。不过，为此FJ必须在奶牛们居住的N(1 &lt;= </div>
<div>N &lt;= 10,000)块草地中选一些建上无线电通讯塔，来保证任意两块草地间都存在手机信号。所有的N块草地按1..N </div>
<div>顺次编号。 所有草地中只有N-1对是相邻的，不过对任意两块草地A和B(1 &lt;= A &lt;= N; 1 &lt;= B &lt;= N; A != B)，都</div>
<div>可以找到一个以A开头以B结尾的草地序列，并且序列中相邻的编号所代表的草地相邻。无线电通讯塔只能建在草地</div>
<div>上，一座塔的服务范围为它所在的那块草地，以及与那块草地相邻的所有草地。 请你帮FJ计算一下，为了建立能</div>
<div>覆盖到所有草地的通信系统，他最少要建多少座无线电通讯塔。</div></div>

# Input

<div class="content"><div>* 第1行: 1个整数，N</div>
<div>* 第2..N行: 每行为2个用空格隔开的整数A、B，为两块相邻草地的编号</div></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第1行: 输出1个整数，即FJ最少建立无线电通讯塔的数目 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 3<br/>
5 2<br/>
4 3<br/>
3 5<br/>
输入说明:<br/>
 Farmer John的农场中有5块草地：草地1和草地3相邻，草地5和草地2、草地<br/>
4和草地3，草地3和草地5也是如此。更形象一些，草地间的位置关系大体如下：<br/>
（或是其他类似的形状）<br/>
               4  2<br/>
               |  |<br/>
            1--3--5<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
输出说明:<br/>
FJ可以选择在草地2和草地3，或是草地3和草地5上建通讯塔。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

