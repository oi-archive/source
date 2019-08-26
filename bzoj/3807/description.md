
# Description

<div class="content"><div>某座大桥上有n1条从左至右的车道，n2(n1,n2≤10)</div>
<div>条从右至左的车道，还有一条潮汐车道。</div>
<div>在早上从左向右行驶的车辆较多，潮汐车道的方向是</div>
<div>从左向右；晚上正好相反。</div>
<div>也就是说早上有n1+1条左右车道，n2条右左车道；晚</div>
<div>上有n1条左右车道，n2+1条右左车道。</div>
<div>交通是很复杂的问题，我们有如下的抽象模型：</div>
<div>从早到晚被分为m(m≤100000)个离散的时刻，编号从1开始。</div>
<div>在每个时刻，两侧均有一些车抵达。</div>
<div>设左右车道和右左车道各有L,R条车道，那么左侧通行L辆车</div>
<div>（即减少L辆车），右侧通行R辆车。</div>
<div>剩下的车等待下一时刻。</div>
<div>如果在时刻m后仍有车辆在等待，那么后面的时刻仍按同样模</div>
<div>型进行，只是不会有新到达的车辆了。</div>
<div>你的任务是决定在哪一时刻改变潮汐车道的方向，能</div>
<div>使所有车辆等待时间的总和最小化。</div>
<div>不过潮汐车道也不是瞬间就能改变方向的，它需要r</div>
<div>个时刻来改变方向。也就是说，如果在t时刻改变方向，那么在[t,t+r-1]</div>
<div>时刻内潮汐车道不能使用，即左右和右左车道各有n1和n2条。</div>
<p></p></div>

# Input

<div class="content"></div>

# Output

<div class="content"></div>

# Sample Input

<div class="content"><span class="sampledata">2 2 10 2<br/>
1 0<br/>
2 1<br/>
3 2<br/>
4 2<br/>
3 3<br/>
2 3<br/>
1 5<br/>
0 3<br/>
1 2<br/>
0 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

