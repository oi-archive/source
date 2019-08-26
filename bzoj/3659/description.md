
# Description

<div class="content"><div><span style="font-size: medium">有n个房间，每个房间有若干把钥匙能够打开特定房间的门。</span></div>
<div><span style="font-size: medium">你会做这么件事情：</span></div>
<div><span style="font-size: medium">最初你在房间1。</span></div>
<div><span style="font-size: medium">每当你到达一个房间，你可以选择该房间的一把钥匙，前往该钥匙对</span></div>
<div><span style="font-size: medium">应的房间，并将该钥匙丢到垃圾桶中。</span></div>
<div><span style="font-size: medium">你希望：最终回到房间1，且垃圾桶中有所有的钥匙。</span></div>
<div><span style="font-size: medium">求方案数。两组方案不同，当且仅当使用钥匙的顺序不同。注意，每</span></div>
<div><span style="font-size: medium">把钥匙都是不同的。</span></div></div>

# Input

<div class="content"><div> <span style="font-size: medium">有多组数据。</span></div>
<div><span style="font-size: medium">对于每组数据第一行输入一个数n，表示房间数。</span></div>
<div><span style="font-size: medium">接下来n行依次描述每个房间：</span></div>
<div><span style="font-size: medium">首先一个数s，表示这个房间的钥匙数目，接下来s个数，分别描述每把</span></div>
<div><span style="font-size: medium">钥匙能够打开的房间的门。</span></div>
<div><span style="font-size: medium">输入以n-0结尾。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">对于每组数据，输出方案数，为了方便你的输出，请将答案对1000003取</span><span style="font-size: medium">模。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
0<br/>
2<br/>
1 1<br/>
1 2<br/>
0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> 1<br/>
0<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">在第一组样例中，没有钥匙，则方案数为1。<br/><br/>
在第二组样例中，你不可能使用第二个房间的钥匙，所以方案数为0。<br/><br/>
<br/><br/>
 <br/><br/>
 <br/><br/>
房间数小于等于100，钥匙数小于等于200000。<br/><br/>
数据组数也不是特别多。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

