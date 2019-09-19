# 题目描述


<h3>
【题目描述】
</h3>
<div class="content">
<p>
<span style="font-size:medium;">您需要写一种数据结构（可参考题目标题），来维护一些数，其中需要提供以下操作：<br/>
1. 插入x数<br/>
2. 删除x数(若有多个相同的数，因只删除一个)<br/>
3. 查询x数的排名(若有多个相同的数，因输出最小的排名)<br/>
4. 查询排名为x的数<br/>
5. 求x的前驱(前驱定义为小于x，且最大的数)<br/>
6. 求x的后继(后继定义为大于x，且最小的数)<br/>
</span> 
</p>
</div>
<h3>
【输入格式】
</h3>
<div class="content">
<p>
<span style="font-size:medium;">第一行为n，表示操作的个数,下面n行每行有两个数opt和x，opt表示操作的序号(1&lt;=opt&lt;=6)</span> 
</p>
</div>
<h3>
【输出格式】
</h3>
<div class="content">
<p>
<span style="font-size:medium;">对于操作3,4,5,6每行输出一个数，表示对应答案</span> 
</p>
</div>
<h3>
【样例输入】
</h3>
<pre>10
1 106465
4 1
1 317721
1 460929
1 644985
1 84185
1 89851
6 81968
1 492737
5 493598</pre>
<h3>
【样例输出】
</h3>
<pre>106465
84185
492737</pre>
<h3>
【提示】
</h3>
<div class="content">
<div>
<span style="font-size:medium;">1.n的数据范围：n&lt;=100000</span> 
</div>
<br/>
<div>
<span style="font-size:medium;">2.每个数的数据范围：[-1e7,1e7]</span> 
</div>
</div>
