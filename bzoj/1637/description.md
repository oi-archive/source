
# Description

<div class="content"><div>Farmer John 决定给他的奶牛们照一张合影，他让 N (1 ≤ N ≤ 50,000) 头奶牛站成一条直线，每头牛都有它的</div>
<div>坐标(范围: 0..1,000,000,000)和种族(0或1)。 一直以来 Farmer John 总是喜欢做一些非凡的事，当然这次照相</div>
<div>也不例外。他只给一部分牛照相，并且这一组牛的阵容必须是“平衡的”。平衡的阵容，指的是在一组牛中，种族</div>
<div>0和种族1的牛的数量相等。 请算出最广阔的区间，使这个区间内的牛阵容平衡。区间的大小为区间内最右边的牛</div>
<div>的坐标减去最做边的牛的坐标。 输入中，每个种族至少有一头牛，没有两头牛的坐标相同。</div></div>

# Input

<div class="content"><p>行 1: 一个整数: N 行 2..N + 1: 每行两个整数，为种族 ID 和 x 坐标。</p></div>

# Output

<div class="content"><p>行 1: 一个整数，阵容平衡的最大的区间的大小。</p></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
0 11<br/>
1 10<br/>
1 25<br/>
1 12<br/>
1 4<br/>
0 13<br/>
1 22<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">11</span></div>

# Hint

<div class="content"><p></p><p>输入说明 </p><br/>
<div>有7头牛，像这样在数轴上。 </div><br/>
<div><img src="/source/bzoj/1637/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwNy8xMS5qcGc=.jpg" width="1153" height="123" alt=""/></div><br/>
<div></div><br/>
<div>输出说明 </div><br/>
<div></div><br/>
<div>牛 #1 (at 11), #4 (at 12), #6 (at 13), #7 (at 22) 组成一个平衡的最大的区间，大小为 22-11=11 个单位长度。 </div><br/>
<div><img src="/source/bzoj/1637/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwNy8yMi5wbmc=.png" width="1156" height="142" alt=""/> </div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

