# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
<span style="font-size:18px;">对于一个递归函数w(a,b,c)</span> 
</p>
<p>
<span style="font-size:18px;">如果 a&lt;=0 或者 b&lt;=0 或者 c&lt;=0 就返回1. 否则</span> 
</p>
<p>
<span style="font-size:18px;">如果 a&gt;20 或者 b&gt;20 或者 c&gt;20 就返回w(20,20,20) 否则</span> 
</p>
<p>
<span style="font-size:18px;">如果 a&lt;b 并且 b&lt;c 就返回w(a,b,c-1)+w(a,b-1,c-1)-w(a,b-1,c) 否则</span> 
</p>
<p>
<span style="font-size:18px;">返回w(a-1,b,c)+w(a-1,b-1,c)+w(a-1,b,c-1)-w(a-1,b-1,c-1)</span> 
</p>
<p>
<span style="font-size:18px;">这是个简单的递归函数，但实现起来可能会有些问题。某些a、b、c的值会使函数运行时间无法忍受。</span> 
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件有n+1(0&lt;=n&lt;=10000)行，第i(1&lt;=i&lt;=n)行有三个整数ai,bi,ci(保证在pascal的longint 或 C/C++的long范围内)。
</p>
<p>
第n+1行必定是-1 -1 -1（同时保证其他行不会是-1 -1 -1）。
</p>
<h3>
【输出格式】
</h3>
<p>
输出文件有n行，第i行输出w(ai,bi,ci)的值（保证在pascal的int64 或 C/C++的long long范围内）。
</p>
<h3>
【样例输入】
</h3>
1 1 1<br/>
2 2 2<br/>
-1 -1 -1<br/>
<h3>
【样例输出】
</h3>
2<br/>
4<br/>
<h3>
【提示】
</h3>
<p>
输出的第一行是w(1,1,1)，输出的第2行是w(2,2,2)。
</p>
<h3>
【来源】
</h3>
<p>
题目提供者邮箱：darkgodz@qq.com
</p>
<p>
（感谢题目提供者对COGS评测系统的支持）
</p>
