# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
有两个$n$元素组成的数组$P$和$Q$。$P$数组每个元素占$S_P$个字节，$Q$数组每个元素占$S_Q$个字节。有时需要直接根据$P$数组中某个元素$P(i)$的偏移量$P_{ofs}(i)$算出对应的$Q(i)$的偏移量$Q_{ofs}(i)$。当两个数组的元素均为连续存储时$P_{ofs}(i)=P_{ofs}(i)/S_P*S_Q$，但因为除法慢，可以把式子改写成速度较快的$Q_{ofs&#39;}=(P_{ofs}(i)+P_{ofs}(i)&lt;&lt;A)&gt;&gt;B$。为了让式子成立，在$P$数组仍然连续存储的前提下，$Q$数组可以不连续存储（但不同数组元素的存储空间不能重叠）。这样做虽然会浪费一些空间， 但是提升了速度， 是一种用空间换时间的方法。
</p>
<p>
输入$N,S_P,S_Q(N\leq 2^{20},1\leq S_P,S_Q \leq 2^{10})$，你的任务是找到最优的$A$和$B$，使得占用的空间尽量小。输出的$K,A,B$值。多解时让$A$尽量小，如果仍多解让$B$尽量小。
</p>
<p>
<br/>
</p>
<p>
英文原题:
</p>
<p>
<img src="/upload/image/20181028/20181028190441_50709.png" alt=""/> 
</p>
<p>
<img src="/upload/image/20181028/20181028190456_76900.png" alt=""/> 
</p>
<p>
<img src="/upload/image/20181028/20181028190509_21895.png" alt=""/> 
</p>
<h3>
【输入格式】
</h3>
<p>
输入包含若干数据集。对于每个数据集包含三个由空格隔开的整数$N$（$1\leq N\leq 2^{20}$）, $S_P, S_Q$($1\leq S_P,S_Q\leq 2^{10})$输入由EOF结束。
</p>
<h3>
【输出格式】
</h3>
<p>
对于每一个数据集，输出一行包括有空格隔开的三个整数$K$，$A$，$B$。
</p>
<h3>
【样例输入】
</h3>
<pre>20 3 5
1024 7 1</pre>
<h3>
【样例输出】
</h3>
<pre>119 0 0
1119 2 5</pre>
<h3>
【提示】
</h3>
<p>
在此键入。
</p>
<h3>
【来源】 
</h3>
<p>
<a href="https://uva.onlinejudge.org/index.php?option=com_onlinejudge&amp;Itemid=8&amp;category=833&amp;page=show_problem&amp;problem=4466" target="_blank">UVa 1591 ACM/ICPC NEERC 2003</a> 
</p>
