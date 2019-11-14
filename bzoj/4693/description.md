
# Description

<div class="content"><div>每年的1月10日是温暖节，在这一天，化身出题人的C_SUNSHINE将会给OIer们送温暖。OIer们只要在门口放上一个</div>
<div>仙人掌，就能在早上的某个时刻听到门外传来一声：“开门，送温暖——”作为一个萌萌哒OIer，Salroey从C_SUN</div>
<div>SHINE那里收到了一个令人感到温暖的问题，她想与你分享分享。有一个K维空间，每个整点上都有一个信号灯，每</div>
<div>个信号灯的位置都可以由K 个整数(x1,x2...xk) 表示，信号灯的颜色定义如下：</div>
<div>1.如果存在i满足xi=0则(x1,x2...xk) 为绿色。</div>
<div>2.如果对于所有i满足xi=1 则 (x1,x2...xk)为红色。</div>
<div>3.对于信号灯(x1,x2...xk) ，定义它的k 个前驱为恰好某一维的坐标比这个信号灯恰好少1</div>
<div>其余坐标都与这个信号灯相等的信号灯，即(x1,x2..xi-1,xi+1...xk) 。如果这些前驱中有偶数个红灯</div>
<div>则这个信号灯为绿色，否则为红色。</div>
<div>现在给定k 和一个k 维矩形，求矩形内部红灯数目，包括边界。</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个正整数t 表示数据组数，对于每组数据：</div>
<div>第一行一个整数k 。</div>
<div>第二行 2k个整数L1,L2..Lk,R1,R2...Rk 描述一个矩形的两个顶点。</div>
<div>T&lt;=10,1&lt;=k&lt;=9,1&lt;=Li&lt;=Ri&lt;=10^15</div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据输出一个整数表示红灯的数目，答案对998244353取模。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
1<br/>
1 3<br/>
2<br/>
1 2 3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
5<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

