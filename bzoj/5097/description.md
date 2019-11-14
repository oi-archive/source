
# Description

<div class="content"><div>告别了随机的国度，这回小Q来到了一个陌生的国度。这个国度由n座城市和若干条单向道路构成，城市依次编号为</div>
<div>1到n。这个国度的路况变化非常频繁，而充满好奇的小Q想在这里进行许多次旅行，在每次出发之前，他会使用导</div>
<div>航系统计算两点间最少需要多少时间。请写一个程序，帮助小Q计算两点间的最短路，你需要支持以下两种操作：</div>
<div>C x y z 从x点出发到y结束的单向道路通过时间变为了z(1&lt;=z&lt;=4)，z=0表示不可通行。</div>
<div>Q x 令d_i为x出发到i的最短路，若无解则为0，计算sum_{i=1}^n i*d_i。</div></div>

# Input

<div class="content"><p>第一行包含两个正整数n,m(1&lt;=n&lt;=500,1&lt;=m&lt;=50000)，分别表示点数和操作次数。</p>
<div>接下来n行，每行n个整数w_{i,j}(0&lt;=w_{i,j}&lt;=4)，其中w_{i,j}表示i出发到j的单向道路的通过时间，0表示不可通行。</div>
<div>接下来m行，每行描述一个操作。</div>
<div>输入数据保证询问次数不超过5000次。</div></div>

# Output

<div class="content"><p>对于每个询问输出一行一个整数，即sum_{i=1}^n i*d_i。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
0 1 2 3<br/>
2 0 4 2<br/>
0 0 0 3<br/>
4 0 4 0<br/>
Q 1<br/>
C 1 3 0<br/>
Q 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">20</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=claris原创，本oj版权所有,翻版必究">claris原创，本oj版权所有,翻版必究</a></p></div>

