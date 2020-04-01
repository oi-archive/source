
# Description

<div class="content">奶牛的图片 
Farmer John希望给他的N(1&lt;=N&lt;=100,000)只奶牛拍照片,这样他就可以向他的朋友炫耀他的奶牛.这N只奶牛被标号为1..N.
在照相的那一天,奶牛们排成了一排.其中第i个位置上是标号为c_i(1&lt;=c_i&lt;=N)的奶牛.对于奶牛的站位,Farmer John有他自己的想法.
FJ是这么想的,标号为i(1&lt;=i&lt;=n-1)的奶牛只能站在标号为i+1的奶牛的左边,而标号为N的奶牛只能站在标号为1的奶牛的左边.当然,没有牛可以站在队列中最左边的奶牛的左边了.也就是说,最左边的奶牛编号是随意的.
这些奶牛都非常的饿,急切的希望吃到FJ承诺的在拍照后的大餐,所以FJ想尽快的拍照.奶牛们的方向感非常的不好,所以FJ每一分钟只可以选择相邻的两只奶牛然后让他们交换位置.FJ最小需要多少时间就能使奶牛站成一个可以接受的序列?
比方说一个有5只奶牛的例子,一开始序列是这样的:
     左边           右边
        3  5  4  2  1

第一分钟,FJ可以交换第二队奶牛(即5和4),交换后的队列:
        3  4  5  2 1
第二分钟,FJ交换最右边的一对,序列变成这样:
        3  4  5  1  2
这样,只用了2分钟,就是序列变为了一个FJ所希望的序列.
</div>

# Input

<div class="content">第1行:一个单独的数N
第2到n+1行:第i+1行上的数表示站在第i的位置上的奶牛的编号(即c_i).
</div>

# Output

<div class="content">一个整数,表示是奶牛的序列变为一个合法的序列的最小花费时间.
</div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
<br/>
3<br/>
<br/>
5<br/>
<br/>
4<br/>
<br/>
2<br/>
<br/>
1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

