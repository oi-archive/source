
# Description

<div class="content"><div id="psrc" style="margin-top: 20px; display: block">
<div class="pdsec"><span style="font-size: medium">　　A国和B国是两个超级大国，长期处于冷战状态；<br/>
　　A国在B国中设有N个情报站，编号为1,2,3,……,N，每个情报站有一个坐标(Xi,Yi)。<br/>
　　但是，A国的工作人员发现，每个情报站里都被埋上了炸弹！<br/>
　　这些炸弹非常特殊，只要同时拆除其中的三个炸弹，所有炸弹就都不会爆炸了。<br/>
　　由于各个情报站联络需要代价，拆除炸弹需要花费的总代价为这些炸弹两两之间的曼哈顿距离和。<br/>
　　现在A国的指挥部门找到了你，希望知道可能需要的最大代价和最小代价。<br/>
</span></div>
</div>
<div id="pcont1" style="margin-top: 20px; display: block"></div></div>

# Input

<div class="content"><div id="pcont1" style="margin-top: 20px; display: block">
<div class="pdcont"><span style="font-size: medium">　　输入的第一行包含一个整数N。接下来N行，第i+1行两个整数Xi,Yi，表示第i个情报站的坐标。<br/>
</span></div>
</div></div>

# Output

<div class="content"><div class="pdcont"><span style="font-size: medium">　　输出两行，每行包含一个整数，第一行表示可能的最大代价，第二行表示可能的最小代价。<br/>
</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 1<br/>
1 2<br/>
2 1<br/>
2 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
4<br/>
<br/>
数据规模和约定<br/>
　　对于30%的数据，N&lt;=500<br/>
　　对于另外10%的数据，每个点出现至少两遍<br/>
　　对于50%的数据，N&lt;=1000<br/>
　　对于60%的数据，N&lt;=8000<br/>
　　对于70%的数据，N&lt;=15000<br/>
　　对于80%的数据，N&lt;=50000<br/>
　　对于100%的数据，N&lt;=100000，0&lt;=Xi,Yi&lt;=10^8<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>注释<br/><br/>
　　对于两个点(X0,Y0),(X1,Y1)，<br/><br/>
　　它们之间的曼哈顿距离为abs(X0-X1)+abs(Y0-Y1)。<br/><br/>
　　其中abs(x)表示x的绝对值。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

