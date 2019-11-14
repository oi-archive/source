
# Description

<div class="content"><div>国家有一个大工程，要给一个非常大的交通网络里建一些新的通道。 </div>
<div>我们这个国家位置非常特殊，可以看成是一个单位边权的树，城市位于顶点上。 </div>
<div>在 2 个国家 a,b 之间建一条新通道需要的代价为树上 a,b 的最短路径。</div>
<div> 现在国家有很多个计划，每个计划都是这样，我们选中了 k 个点，然后在它们两两之间 新建 C(k,2)条 新通道。</div>
<div>现在对于每个计划，我们想知道：</div>
<div> 1.这些新通道的代价和</div>
<div> 2.这些新通道中代价最小的是多少 </div>
<div>3.这些新通道中代价最大的是多少</div>
<div></div></div>

# Input

<div class="content"><p>第一行 n 表示点数。</p>
<div>
<div> 接下来 n-1 行，每行两个数 a,b 表示 a 和 b 之间有一条边。</div>
<div>点从 1 开始标号。 接下来一行 q 表示计划数。</div>
<div>对每个计划有 2 行，第一行 k 表示这个计划选中了几个点。</div>
<div> 第二行用空格隔开的 k 个互不相同的数表示选了哪 k 个点。</div>
<div></div>
</div></div>

# Output

<div class="content"><p>输出 q 行，每行三个数分别表示代价和，最小代价，最大代价。 </p>
<div>
<div></div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">10 <br/>
2 1 <br/>
3 2 <br/>
4 1 <br/>
5 2 <br/>
6 4 <br/>
7 5<br/>
8 6 <br/>
9 7 <br/>
10 9 <br/>
5 <br/>
2 <br/>
5 4 <br/>
2 <br/>
10 4 <br/>
2 <br/>
5 2 <br/>
2 <br/>
6 1 <br/>
2 <br/>
6 1 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 3 3 <br/>
6 6 6 <br/>
1 1 1 <br/>
2 2 2 <br/>
2 2 2 </span></div>

# Hint

<div class="content"><p></p><p>n&lt;=1000000 </p><br/>
<div>q&lt;=50000并且保证所有k之和&lt;=2*n </div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢佚名上传">鸣谢佚名上传</a></p></div>

