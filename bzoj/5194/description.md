
# Description

<div class="content"><div>到冬天了，这意味着下雪了！从农舍到牛棚的路上有N块地砖，方便起见编号为1…N，第i块地砖上积了fi英尺的雪</div>
<div>。在Farmer John的农舍的地窖中，总共有B双靴子，编号为1…B。其中某些比另一些结实，某些比另一些轻便。具</div>
<div>体地说，第i双靴子能够让FJ在至多si英尺深的积雪中行走，能够让FJ每步至多前进di。Farmer John从1号地砖出</div>
<div>发，他必须到达N号地砖才能叫醒奶牛们。1号地砖在农舍的屋檐下，N号地砖在牛棚的屋檐下，所以这两块地砖都</div>
<div>没有积雪。帮助Farmer John求出哪些靴子可以帮助他走完这段艰辛的路程。</div></div>

# Input

<div class="content"><p>第一行包含两个空格分隔的整数N和B（1≤N,B≤10^5）。</p>
<div>第二行包含N个空格分隔的整数；第i个整数为fi，即i号地砖的积雪深度（0≤fi≤10^9）。输入保证f1=fN=0</div>
<div>下面B行，每行包含两个空格分隔的整数。第i+2行的第一个数为si，表示第i双靴子能够承受的最大积雪深度。</div>
<div>第i+2行的第二个数为di，表示第i双靴子的最大步长。输入保证0≤si≤10^9以及1≤di≤N-1</div></div>

# Output

<div class="content"><p>输出包含N行</p>
<div>第i行包含一个整数：如果Farmer John能够穿着第i双靴子从1号地砖走到N号地砖，为1，否则为0</div></div>

# Sample Input

<div class="content"><span class="sampledata">8 7<br/>
0 3 8 5 6 9 0 0<br/>
0 5<br/>
0 6<br/>
6 2<br/>
8 1<br/>
10 1<br/>
5 3<br/>
150 7</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
1<br/>
1<br/>
0<br/>
1<br/>
1<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

