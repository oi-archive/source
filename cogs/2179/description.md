# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
给定两个整数 N 和 K。
</p>
<p>
请你计算有多少长度为 K 的序列 A<span style="font-size:9px;">1</span>, A<span style="font-size:9px;">2</span>, ..., A<span style="font-size:9px;">K</span>，(0&lt;=A<span style="font-size:9px;">i</span>) 满足：
</p>
<p>
    A<span style="font-size:9px;">1 </span>Or A<span style="font-size:9px;">2 </span>Or ...Or  A<span style="font-size:9px;">K</span> = N。
</p>
<p>
并且对于任意的 i = 1, ..., k - 1 有 A<span style="font-size:9px;">i </span> Or  A<span style="font-size:9px;">i + 1</span> = A<span style="font-size:9px;">i + 1</span>。
</p>
<h3>
【提示】
</h3>
<p>
 
</p>
<p>
Or 是按位或操作。
</p>
<p>
Pascal 为 or  ，C 和 C++为 |。
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
<span style="color:#E53333;"><strong>此题有多组数据</strong></span><span style="color:#E53333;"><strong>。</strong></span> 
</p>
<p>
第一行包含一个整数 T ，表示测试数据组数。
</p>
<p>
接下来有 T 行，每行包括两个整数 N 和 K ,意义如题目所述。
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
对于每组测试数据，输出一行表示对应的答案。考虑答案可能很大，输出模 1000000009 后的结果。
</p>
<h3>
【样例输入】
</h3>
<p>
<br/>
</p>
<p>
3
</p>
<p>
2 3
</p>
<p>
2 4
</p>
<p>
3 3
</p>
<h3>
【样例输出】
</h3>
<p>
<br/>
</p>
<p>
3
</p>
<p>
4
</p>
<p>
9
</p>
<h3>
【数据范围】
</h3>
<p>
<br/>
</p>
<p>
对于10%的数据，N&lt;=100,K&lt;=100 ；
</p>
<p>
对于30%的数据，N&lt;=1000,K&lt;=10000 ；
</p>
<p>
对于50%的数据，N&lt;=10000,K&lt;=100000 ；
</p>
<p>
对于70%的数据，N&lt;=10000000,K&lt;=100000000 ；
</p>
<p>
对于100%的数据，N&lt;=100000000,K&lt;=10000000000，T&lt;=100 。
</p>
<h3>
【来源】
</h3>
<p>
<br/>
</p>
<p>
By Zayin.
</p>
