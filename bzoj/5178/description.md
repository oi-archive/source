
# Description

<div class="content"><div>Coffee的世界里也是有棒棒糖卖的，Coffee买了N(1≤N≤50000)只连着的。这N只棒棒糖包裹在小塑料袋中，排成</div>
<div>一列，相邻的两只棒棒糖的塑料袋是接起来的。为了方便，我们把棒棒糖从左到右编号为1..N。每只棒棒糖有一种</div>
<div>口味。第i只的口味是ci(1≤ci≤50000)。两只棒棒糖i,j的口味相同，当且仅当ci=cj。Coffee对m只棒棒糖总体口</div>
<div>味的评价比较奇怪。如果这m只棒棒糖中，有一种口味c0的数量严格大于总数的一半m/2，那么Coffee认为这m只棒</div>
<div>棒糖主要是c0口味的。Coffee知道，这里的c0如果存在就一定是唯一的。而当c0不存在时，Coffee认为这m只棒棒</div>
<div>糖是混合口味的。Coffee暂时舍不得吃棒棒糖，它在想一些好玩的问题。如果考虑棒棒糖序列的一个连续子序列s.</div>
<div>.t(1≤s≤t≤N)，包括棒棒糖s和t。那么这t-s+1只棒棒糖的总体口味是什么呢？</div>
<div>Coffee有一堆这样的问题，一共M(1≤M≤50000)个。</div>
<div>第i个问题是棒棒糖子序列si..ti的总体口味。请你帮忙解决。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第1行：两个用空格隔开的整数，分别表示N,M。</div>
<div>第2..N+1行：每行一个整数，第i+1行表示ci。</div>
<div>第N+2..N+M+1行：每行两个用空格隔开的整数</div>
<div>第i+N+1行表示，si,ti。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>第1..M行：每行一个整数</div>
<div>第i个整数表示你对第i个问题的回答，也就是si..ti的总体口味。</div>
<div>如果总体口味是c0，那么回答用c0表示。</div>
<div>如果总体口味是混合口味，那么回答用0表示</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3 <br/>
1 <br/>
2 <br/>
2<br/>
1<br/>
1<br/>
1 5<br/>
2 5<br/>
2 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
0<br/>
2<br/>
棒棒糖1..5中，口味1的棒棒糖有3只，一共5只棒棒糖，而3&gt;5/2=2.5，所以主要口味为1。棒棒糖2..5中，一共4只<br/>
棒棒糖，没有一种口味的棒棒糖个数严格大于4/2=2，所以是混合口味的。棒棒糖2..4中，一共3只棒棒糖，口味2<br/>
的棒棒糖有2只，2&gt;3/2=1.5，主要口味为2。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

