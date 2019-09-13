# 题目描述


<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
<span>题目描述：</span> 
</p>
<p style="text-indent:0.85cm;">
<span>近来</span><span><span><span>A</span></span></span><span>国和</span><span><span><span>B</span></span></span><span>国的矛盾激化，为了预防不测，</span><span><span><span>A</span></span></span><span>国准备修建一条长长的防线，当然修建防线的话，肯定要把需要保护的城市修在防线内部了。可是</span><span><span><span>A</span></span></span><span>国上层现在还犹豫不决，到底该把哪些城市作为保护对象呢？又由于</span><span><span><span>A</span></span></span><span>国的经费有限，所以希望你能帮忙完成如下的一个任务：</span> 
</p>
<ol>
<li>
<p>
<span>给出你所有的</span><span><span><span>A</span></span></span><span>国城市坐标</span> 
</p>
</li>
<li>
<p>
<span><span><span>A</span></span></span><span>国上层经过讨论，考虑到经济问题，决定取消对</span><span><span><span>i</span></span></span><span>城市的保护，也就是说</span><span><span><span>i</span></span></span><span>城市不需要在防线内了</span> 
</p>
</li>
<li>
<p>
<span><span><span>A</span></span></span><span>国上层询问对于剩下要保护的城市，修建防线的总经费最少是多少</span> 
</p>
</li>
</ol>
<p style="margin-left:0.74cm;">
<br/>
</p>
<p style="margin-left:0.74cm;">
<span>你需要对每次询问作出回答。注意单位</span><span><span><span>1</span></span></span><span>长度的防线花费为</span><span><span><span>1</span></span></span><span>。</span> 
</p>
<p>
<br/>
</p>
<p>
<span><span>A</span></span><span>国的地形是这样的，形如下图，</span><span><span>x</span></span><span>轴是一条河流，相当于一条天然防线，不需要你再修建</span> 
</p>
<p>
<span><span>A</span></span><span>国总是有两个城市在河边，一个点是</span><span><span>(0,0)</span></span><span>，一个点是</span><span><span>(n,0)</span></span><span>，其余所有点的横坐标均大于</span><span><span>0</span></span><span>小于</span><span><span>n</span></span><span>，纵坐标均大于</span><span><span>0</span></span><span>。</span><span><span>A</span></span><span>国有一个不在</span><span><span>(0,0)</span></span><span>和</span><span><span>(n,0)</span></span><span>的首都。</span><span><span>(0,0),(n,0)</span></span><span>和首都这三个城市是一定需要保护的。</span> 
</p>
<p>
<img alt="" src="/images/2.png" height="337" width="438"/> 
</p>
<p align="center">
<br/>
</p>
<p style="text-indent:0.85cm;">
<span>上图中，</span><span><span>A,B,C,D,E</span></span><span>点为</span><span><span>A</span></span><span>国城市，且目前都要保护，那么修建的防线就会是</span><span><span>A-B-C-D</span></span><span>，花费也就是线段</span><span><span>AB</span></span><span>的长度</span><span><span>+</span></span><span>线段</span><span><span>BC</span></span><span>的长度</span><span><span>+</span></span><span>线段</span><span><span>CD</span></span><span>的长度</span> 
</p>
<p style="text-indent:0.85cm;">
<span>如果，这个时候撤销</span><span><span>B</span></span><span>点的保护，那么防线变成下图</span> 
</p>
<p style="text-indent:0.85cm;">
<img alt="" src="/images/3.png" height="243" width="343"/> 
</p>
<p style="text-indent:0.85cm;" align="center">
<br/>
</p>
<p>
<span>输入格式：</span> 
</p>
<p>
<span>第一行，三个整数</span><span><span>n,x,y</span></span><span>分别表示河边城市和首都是</span><span><span>(0,0)</span></span><span>，</span><span><span>(n,0)</span></span><span>，</span><span><span>(x,y)</span></span><span>。</span> 
</p>
<p>
<span>第二行，一个整数</span><span><span>m</span></span><span>。</span> 
</p>
<p>
<span>接下来</span><span><span>m</span></span><span>行，每行两个整数</span><span><span>a,b</span></span><span>表示</span><span><span>A</span></span><span>国的一个非首都非河边城市的坐标为</span><span><span>(a,b)</span></span><span>。</span> 
</p>
<p>
<span>再接下来一个整数</span><span><span>q</span></span><span>，表示修改和询问总数。</span> 
</p>
<p>
<span>接下来</span><span><span>q</span></span><span>行每行要么形如</span><span><span>1 i</span></span><span>，要么形如</span><span><span>2</span></span><span>，分别表示撤销第</span><span><span>i</span></span><span>个城市的保护和询问。</span> 
</p>
<p>
<br/>
</p>
<p>
<span>输出格式：</span> 
</p>
<p>
<span>对于每个询问输出</span><span><span>1</span></span><span>行，一个实数</span><span><span>v</span></span><span>，表示修建防线的花费，保留两位小数</span> 
</p>
<p>
<br/>
</p>
<p>
<span>样例输入： </span> 
</p>
<p>
<span><span>4 2 1 </span></span> 
</p>
<p>
<span><span>2 </span></span> 
</p>
<p>
<span><span>1 2 </span></span> 
</p>
<p>
<span><span>3 2 </span></span> 
</p>
<p>
<span><span>5 </span></span> 
</p>
<p>
<span><span>2</span></span> 
</p>
<p>
<span><span>1 1</span></span> 
</p>
<p>
<span><span>2</span></span> 
</p>
<p>
<span><span>1 2</span></span> 
</p>
<p>
<span><span>2</span></span> 
</p>
<p>
<br/>
</p>
<p>
<span>样例输出：</span> 
</p>
<p>
<span><span>6.47</span></span> 
</p>
<p>
<span><span>5.84</span></span> 
</p>
<p>
<span><span>4.47</span></span> 
</p>
<p>
<br/>
</p>
<p>
<span>数据范围：</span> 
</p>
<p>
<span><span>30%</span></span><span>的数据</span><span><span>m&lt;=1000,q&lt;=1000</span></span> 
</p>
<p>
<span><span>100%</span></span><span>的数据</span><span><span>m&lt;=100000,q&lt;=200000,n&gt;1</span></span> 
</p>
<p>
<span>所有点的坐标范围均在</span><span><span>10000</span></span><span>以内</span><span><span>, </span></span><span>数据保证没有重点</span> 
</p>
