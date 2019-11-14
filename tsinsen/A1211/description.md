<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　小明最近课上刚刚学习了矩阵，今天他在一本书上翻到一个神奇的式子：<br/>
<img width="151" height="30" src="source/tsinsen/A1211/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9TkY0UlROSDg=.do"/><br/>
<br/>
　　其中，A表示一个 的矩阵，A<sup>T</sup>是A的转置，将矩阵 沿着主对角线翻转得到的一个N*1 的矩阵(即矩阵A<sup>T</sup> 的第i行第j列的元素值等于矩阵A 的第j行第i列)。例如，当<img width="119" height="27" src="source/tsinsen/A1211/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9RGJOUUhHQU4=.do"/> ，那么<img width="69" height="107" src="source/tsinsen/A1211/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9bXJUSjd0dEU=.do"/> 。B 是一个N*N 的矩阵，C 是一个1*N 的矩阵，&#34;*&#34; 和 &#34;-&#34;表示矩阵的乘法和减法。<br/>
　　根据矩阵运算的性质，我们会惊奇的发现得到的结果 D是一个1*1 的矩阵，这是多么美妙的性质啊，小明顿时对此产生了浓厚的兴趣，希望自己亲手算算来验证一下。<br/>
　　书本上已经给出了 B，C 矩阵，都是只包含非负整数的矩阵。但是写有A 矩阵的那一页不幸的丢失了，于是小明决定自己构造A 矩阵，为了使自己的计算方便，他希望构造出来的A 矩阵的元素非0即1。当然 A矩阵不是随便构造的，小明希望算出来的D 矩阵的元素值最大。<br/>
　　现在，构造A 矩阵并计算这个神奇式子的重任就落到了你的肩上。</div>
# 输入格式

<div class="pdcont">　　输入第1行有一个整数N。<br/>
　　第2～N+1行每行N个非负整数，用空格隔开，描述B 矩阵。<br/>
　　第N+2行，有N个非负整数，用空格隔开，描述C 矩阵。<br/>
　　输入数据保证没有多余的空格和换行。</div>
# 输出格式

<div class="pdcont">　　只需要输出一个整数，表示你找到的元素值最大 D矩阵。</div>
# 样例输入

<div class="pddata">3<br/>
1 2 1<br/>
3 1 0<br/>
1 2 3<br/>
2 3 7</div>
# 样例输出

<div class="pddata">2</div>
# 样例说明

<div class="pdcont">　　矩阵 可能为：( 0 , 0 , 0 ) ， ( 0 , 0 , 1 ) ， ( 0 , 1 , 0 ) ，( 0 , 1 , 1 ) ，( 1 , 0 , 0 ) ，( 1 , 0 , 1 ) ，( 1 , 1 , 0 ) 或( 1 , 1 , 1 )  ,对应得到的 结果依次为：0 ，-4 ，-2 ，-4 ，-1 ，-3 ，2 和 2 。<br/>
　　其中当A=( 1 , 1 , 0 ) 或A=( 1 , 1  , 1 ) ，D=(2) ，此时 D矩阵的元素值最大。</div>
# 数据规模和约定

<div class="pdcont">　　30%的数据中N≤20；<br/>
　　70%的数据中N≤200；<br/>
　　100%的数据中N≤600，B 矩阵元素的和&lt;2<sup>31</sup> , C矩阵元素的和&lt; 2<sup>31</sup>；</div>
# 友情提示（对于使用C/C++的同学）

<div class="pdcont">　　由于题目读入的数据规模较大，使用cin或者scanf读入可能会导致超时，所以推荐使用gets读入，这里友情提供一个gets读入的过程，可以直接使用：<br/>
<br/>
　　void getline(int data[])<br/>
　　{<br/>
　　int i=0,k=0; char ch[20000];<br/>
　　gets(ch);<br/>
　　for (;ch[k]!=&#39;\0&#39;;k++)<br/>
　　{<br/>
　　data[i]=0;<br/>
　　for (;ch[k]!=&#39;\0&#39; &amp;&amp; ch[k]!=&#39; &#39;;k++) data[i]=data[i]*10+ch[k]-&#39;0&#39;;<br/>
　　i++;<br/>
　　};<br/>
　　}<br/>
<br/>
　　假设a是你的程序定义的一个一维int数组，当调用getline(a)时，这个过程会读入下一行的所有数字。假设当前行有x个数字，那么这些数字会存放在a[0]~a[x-1]中(注意：需要保证a数组的大小足够）。</div>

</div>