
# Description

<div class="content"><div>属于小Q管辖的n座摩天楼从左往右排成一排，编号依次为1到n，第i座摩天楼的高度为h_i。小Q会进行m次以下两种</div>
<div>操作之一：</div>
<div></div>
<div>1 l r，询问h_l+h_{l+1}+...+h_r。</div>
<div></div>
<div>2 l r，对于第l到r的每座摩天楼i，如果上次操作结束时h_i&lt;h_{i-1}，则将第i座摩天楼再往上造一层，即h_i增加1。</div>
<div>你可以认为h_0=正无穷。</div>
<div></div>
<div>请写一个程序回答小Q的每个询问。注意，此题操作一和操作二弄反了</div>
<div></div>
<div></div>
<div></div></div>

# Input

<div class="content"><div>第一行包含两个正整数n,m(1&lt;=n&lt;=100000,1&lt;=m&lt;=min(100000,2n))，分别表示摩天楼的数量以及操作的数量。</div>
<div></div>
<div>第二行包含n个正整数h_1,h_2,...,h_n(1&lt;=h_i&lt;=n)，表示每座楼的高度。</div>
<div></div>
<div>接下来m行，每行三个正整数op,l,r(1&lt;=op&lt;=2,1&lt;=l&lt;=r&lt;=n)，分别表示每个操作。</div>
<div></div>
<div>因为小Q觉得错乱不齐的建筑更加美观，因此你可以认为数据是完全随机的。</div>
<div></div></div>

# Output

<div class="content"><div>对于每个询问输出一行一个整数，即区间内所有摩天楼的高度之和。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 8<br/>
1 3 2 2 4<br/>
1 2 4<br/>
2 2 2<br/>
2 3 3<br/>
2 4 4<br/>
1 1 3<br/>
2 1 1<br/>
2 2 2<br/>
2 3 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
3<br/>
2<br/>
2<br/>
3<br/>
3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=claris原创，本oj版权所有,翻版必究">claris原创，本oj版权所有,翻版必究</a></p></div>

