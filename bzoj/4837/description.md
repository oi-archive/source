
# Description

<div class="content"><div>小Q同学在学习操作系统中内存管理的一种页面置换算法，LRU(LeastRecentlyUsed)算法。</div>
<div>为了帮助小Q同学理解这种算法，你需要在这道题中实现这种算法，接下来简要地介绍这种算法的原理：</div>
<div>1.初始化时，你有一个最大长度为n的空队列，用于暂时存储一些页面的地址。</div>
<div>2.当系统需要加载一个不在队列中的页面时，如果队列已满，则弹出队首元素，并将需要加载的页面加到队尾，</div>
<div>否则直接将需要加载的页面加到队尾。</div>
<div>3.当系统需要加载一个在队列中的页面时，将该页面移至队尾。</div>
<div>在这道题中，小Q同学需要处理有q个请求，每个请求会给定一个整数x，表示系统需要加载地址为x的页面，</div>
<div>而你需要在每个请求完成后给出整个队列中页面的地址之和。为了便于计算，设第i个请求给出的整数为x_i，</div>
<div>第i个请求后你给出的答案为y_i，则对于1&lt;i≤q有x_i=(A*x_(i-1)+B)modp，其中x_1,A,B,p是给</div>
<div>定的整数，并且你只需要输出sigma(i*y_i),1&lt;=i&lt;=Q对2^64取模的值，而不是每个y_i。</div>
<div></div>
<div></div>
<div></div></div>

# Input

<div class="content"><div>第一行包含一个正整数T，表示有T组数据，满足T≤20。</div>
<div>接下来依次给出每组测试数据。对于每组测试数据：</div>
<div>第一行包含两个正整数n和q，满足1≤n≤10^5,1≤q≤10^6。</div>
<div>第二行包含四个整数x_1,A,B和p，满足0≤x_1,A,B&lt;p,1≤p≤10^6+3。</div></div>

# Output

<div class="content"><p> 对于每组测试数据，输出一行一个非负整数，表示这组数据的答案。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
5 10<br/>
0 1 1 5<br/>
5 10<br/>
0 1 1 10</span></div>

# Sample Output

<div class="content"><span class="sampledata">485<br/>
1135<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供试题">鸣谢Tangjz提供试题</a></p></div>

