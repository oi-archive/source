# 题目描述


<p>
<span>众所周知，GF同学喜欢打dota，而且打得非常好。今天GF和Spartan同学进行了一场大战。</span> 
</p>
<p>
<span>现在GF拿到一张地图，地图上一共有n个地点，GF的英雄处于1号点，Spartan的基地位于n号点，</span> 
</p>
<p>
<span>GF要尽快地选择较短的路线让他的英雄去虐掉Spartan的基地。但是Spartan早就料到了这一点，</span> 
</p>
<p>
<span>他有可能会开挂(BS~)使用一种特别的魔法，一旦GF所走的路线的总长度等于最短路的总长度时，</span> 
</p>
<p>
<span>GF的英雄就要和这种魔法纠缠不休。这时GF就不得不选择非最短的路线。现在请你替GF进行规划。</span> 
</p>
<span><br/>
</span><br/>
<span>对于描述的解释与提醒：</span><br/>
<span>1.无向路径，花费时间当然为非负值。</span><br/>
<p>
<span>2.对于本题中非最短路线的定义：不管采取任何迂回、改道方式，</span> 
</p>
<p>
<span>只要GF所走的路线总长度不等于1到n最短路的总长度时，就算做一条非最短的路线。</span> 
</p>
<span>3.保证1~n有路可走。</span><br/>
<p>
<br/>
</p>
<p>
输入：
</p>
<p>
<span>第一行为n，m(表示一共有m条路径)</span><br/>
<span>接下来m行，每行3个整数a，b，c，表示编号为a,b的点之间连着一条花费时间为c的无向路径。</span><br/>
<span>接下来一行有一个整数p，p=0表示Spartan没有开挂使用这种魔法，p=1则表示使用了。</span> 
</p>
<p>
<br/>
</p>
<p>
输出：
</p>
<span>所花费的最短时间t，数据保证一定可以到达n。</span> 
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
<span>样例输入1：</span><br/>
<span>5 5</span><br/>
<span>1 2 1</span><br/>
<span>1 3 2</span><br/>
<span>3 5 2</span><br/>
<span>2 4 3</span><br/>
<span>4 5 1</span><br/>
<span>0</span><br/>
<span><br/>
</span><br/>
<span>样例输入2：</span><br/>
<span>5 5</span><br/>
<span>1 2 1</span><br/>
<span>1 3 2</span><br/>
<span>3 5 2</span><br/>
<span>2 4 3</span><br/>
<span>4 5 1</span><br/>
<span>1</span> 
</p>
<div>
<br/>
</div>
<span>样例输出1：</span><br/>
<span>4</span><br/>
<span>样例输出2：</span><br/>
<span>5</span> 
<p>
<br/>
</p>
<p>
<span><br/>
</span> 
</p>
<p>
<span>对于50%的数据，1&lt;=n,m&lt;=5000</span><br/>
<span>对于70%的数据，1&lt;=n&lt;=10000, 1&lt;=m&lt;=50000,p=0,</span><br/>
<span>对于100%的数据，1&lt;=n&lt;=10000, 1&lt;=m&lt;=50000,p=1</span><br/>
<span>无向图，花费时间c&gt;=0</span> 
</p>
<p>
<span>各个测试点1s</span> 
</p>
<div>
<br/>
</div>
<p>
<br/>
</p>
<span>来源：lydliyudong    Tyvj February二月月赛第二场  第2道</span> 
<p>
<br/>
</p>
