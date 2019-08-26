
# Description

<div class="content"><div>ls最近开了一家图书馆，大家听说是ls开的，纷纷过来借书，自然就会出现供不应求的情况，<span class="Apple-tab-span" style="white-space:pre">	</span>并且借书的过程类</div>
<div>似一个队列，每次有人来借书就将它加至队尾，每次有人来还书就把书借给队头的若干个人，定义每个人的等待时</div>
<div>间为拿到书的时刻减去加至队列的时刻，如果一个人根本就拿不到书，则等待时间为inf，现在给出所有时刻借书</div>
<div>还书的情况，和若干个询问，每次询问当图书馆初始有x本书时所有人的等待时间之和是多少（如果存在一个人根</div>
<div>本拿不到书，则输出INFINITY）。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数n,q（1&lt;=n,q&lt;=100000),表示有n个时刻有借书还书的情况，以及有q个询问。</div>
<div>接下来n行，每行表示一个操作，操作如下：</div>
<div>1.&#34;+ t k&#34; 在t时刻有k本书被还回来。</div>
<div>2.&#34;- t k&#34; 在t时刻有k个人来借书。</div>
<div>（1&lt;=t&lt;=1e9,1&lt;=k&lt;=10000）</div>
<div>输入顺序保证t递增。</div>
<div>接下来一行q个数，第i个数bi（1&lt;=bi&lt;=1e9）表示图书馆初始有bi本书，询问所有人的等待时间之和为多少。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>一共q行，每行一个数表示等待时间之和，如果存在一个人根本拿不到书，则输出INFINITY。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 4<br/>
- 1 1<br/>
- 2 2<br/>
+ 4 1<br/>
- 6 1<br/>
+ 7 2<br/>
0 3 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">INFINITY<br/>
0<br/>
8<br/>
3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

