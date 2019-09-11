# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p class="p1">
<span class="s1">线段树的结构非常简单，它简单到只支持两类操作，修改和查询。<span class="Apple-tab-span"> </span> </span> 
</p>
<p class="p1">
<span class="s1"><span class="Apple-tab-span"> </span>HA实验有一棵线段树，调皮的HtBest想对它进行一些操作，并实时查看他的状态。HtBest会对线段树进行以下三种操作：</span> 
</p>
<p class="p1">
<span class="s1">1.让线段树维护的区间中[l,r]全部加上一个正整数<span class="Apple-converted-space"> </span> </span> 
</p>
<p class="p1">
<span class="s1">2.让线段树维护的区间中[l,r]全部乘以一个正整数<span class="Apple-converted-space"> </span> </span> 
</p>
<p class="p1">
<span class="s1">3.HtBest希望知道区间[l,r]的数值之和</span> 
</p>
<p class="p1">
<span class="s1"><span class="Apple-tab-span"> </span>由于答案可能很大，你只需要输出答案模p后的值。(线段树初始值全为0)</span> 
</p>
<br/>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p class="p1">
<span class="s1">第一行包含三个正整数n(维护的最大区间)m(操作个数)和p(需要模的值)。接下来有n行，每行描述一个操作，有以下三种形式：“1 l r v” 表示为[l,r]中的每个数都加上v，“2 l r v”表示为[l,r]中的每个数都乘以v，“3 l r”表示查询[l,r]的数值之和。</span> 
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p class="p1">
<span class="s1">对于每个询问操作，输出一个整数占一行，表示询问的答案。</span> 
</p>
<p>
<br/>
</p>
<h3>
【样例输入1】
</h3>
<pre>3 3 5
2 2 2 2
1 1 1 1
3 1 2			
</pre>
<h3>
【样例输出1】
</h3>
<pre>1</pre>
<h3>
【样例输入2】
</h3>
<pre>3 3 5
2 2 3 2
1 1 3 5
3 1 2
</pre>
<h3>
【样例输出2】
</h3>
<pre>0</pre>
<h3>
【样例输入3】
</h3>
<pre>7 7 1000
1 3 5 8
1 2 4 13
2 6 7 2
2 2 4 1
3 1 4
3 4 6
2 1 4 6
</pre>
<h3>
【样例输出3】
</h3>
<pre>55
29
</pre>
<h3>
【提示】
</h3>
<p>
对于前30%的数据，1≤n，m≤1000
</p>
<p>
另有20%的数据，无操作2
</p>
<p>
对于前100%的数据，1≤n，m≤100000
</p>
<p>
对于所有输入数据，不超过100000000。
</p>
<p>
<strong><span style="font-size:18px;"></span><span style="color:#E53333;font-size:18px;">暴力程序请加大数据剪枝，否则会卡评测机。</span></strong> 
</p>
<h3>
【来源】
</h3>
By : HtBest
