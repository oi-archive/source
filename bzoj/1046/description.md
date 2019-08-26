
# Description

<div class="content"><p>　　对于一个给定的S={a1,a2,a3,…,an},若有P={ax1,ax2,ax3,…,axm},满足(x1 &lt; x2 &lt; … &lt; xm)且（ ax1 &lt; ax<br/>
2 &lt; … &lt; axm)。那么就称P为S的一个上升序列。如果有多个P满足条件，那么我们想求字典序最小的那个。任务给<br/>
出S序列，给出若干询问。对于第i个询问，求出长度为Li的上升序列，如有多个，求出字典序最小的那个（即首先<br/>
x1最小，如果不唯一，再看x2最小……），如果不存在长度为Li的上升序列，则打印Impossible.</p></div>

# Input

<div class="content"><p>　　第一行一个N，表示序列一共有N个元素第二行N个数，为a1,a2,…,an 第三行一个M，表示询问次数。下面接M<br/>
行每行一个数L，表示要询问长度为L的上升序列。N&lt;=10000，M&lt;=1000</p></div>

# Output

<div class="content"><p>　　对于每个询问，如果对应的序列存在，则输出，否则打印Impossible.</p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
3 4 1 2 3 6<br/>
3<br/>
6<br/>
4<br/>
5</span></div>

# Sample Output

<div class="content"><span class="sampledata">Impossible<br/>
1 2 3 6<br/>
Impossible</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

