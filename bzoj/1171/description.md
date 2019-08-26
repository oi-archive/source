
# Description

<div class="content"><p>大sz最近在玩一个由星球大战改编的游戏。话说绝地武士当前共控制了N个星球。但是，西斯正在暗处悄悄地准备他们的复仇计划。绝地评议会也感觉到了这件事。于是，准备加派绝地武士到各星球防止西斯的突袭。一个星球受到攻击以后，会尽快通知到总基地。需要的时间越长的星球就需要越多绝地武士来防御。为了合理分配有限的武士，大sz需要你帮他求出每个星球各需要多少时间能够通知到总基地。由于某种原因，N个星球排成一条直线，编号1至N。其中总基地建在1号星球上。每个星球虽然都是绝地武士控制的，但是上面居住的生物不一定相同，并且科技水平也不一样。第i个星球能收到并分析波长在[xi, yi]之间的信号，并且也能够发出在这个区间的信号，但是不能发出其他任何波长的信号。由于技术原因，每个星球只能发信号到比自己编号小的距离不超过L的星球。特别地，强大的总基地可以接收任何波长的信号。每个星球处理接收到的数据需要1个单位时间，传输时间可以忽略不计。</p></div>

# Input

<div class="content"><p>第一行两个正整数N、L。接下来N-1行，总共第i行包含了三个正整数xi、yi、li，其中li表示第i个星球距离1号星球li，满足li严格递增。</p></div>

# Output

<div class="content"><p>总共N-1行，每行一个数分别表示2到N号星球至少需要多少单位时间，总基地能够处理好数据，如果无法传到总基地则输出-1。</p></div>

# Sample Input

<div class="content"><span class="sampledata">input1<br/>
3 1<br/>
1 2 1<br/>
2 3 2<br/>
input 2<br/>
3 3<br/>
1 2 1<br/>
2 3 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">output1<br/>
1<br/>
2<br/>
output2<br/>
1<br/>
1<br/>
30%的数据满足N &lt;=20000; <br/>
100%的数据满足2 &lt;=N&lt;= 2.5*10^5、0&lt;=xi，yi，li&lt;=2*10^9，1&lt;=L&lt;=2*10^9,xi&lt;=yi． <br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 俞华程">By 俞华程</a></p></div>

