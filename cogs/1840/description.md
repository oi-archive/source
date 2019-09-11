# 题目描述


<h3>
【题目描述】
</h3>
<div class="content">
<p>
<span style="font-size:medium;">直线上N颗行星，X=i处有行星i,行星J受到行星I的作用力，当且仅当i&lt;=AJ.此时J受到作用力的大小为 Fi-&gt;j=Mi*Mj/(j-i) 其中A为很小的常量，故直观上说每颗行星都只受到距离遥远的行星的作用。请计算每颗行星的受力，只要结果的相对误差不超过5%即可.</span> 
</p>
</div>
<h3>
【输入格式】
</h3>
<div class="content">
<p>
第一行两个整数N和A. 1&lt;=N&lt;=10^5.0.01&lt; a &lt; =0.35 <br/>
接下来N行输入N个行星的质量Mi,保证0&lt;=Mi&lt;=10^7
</p>
</div>
<h3>
【输出格式】
</h3>
<div class="content">
<p>
N行，依次输出各行星的受力情况
</p>
</div>
<h3>
【样例输入】
</h3>
<pre>5 0.3
3
5
6
2
4</pre>
<h3>
【样例输出】
</h3>
<pre>0.000000
0.000000
0.000000
1.968750
2.976000</pre>
<h3>
【提示】
</h3>
<div class="content">
<p>
<span style="font-size:medium;">精确结果应该为0 0 0 2 3,但样例输出的结果误差不超过5%,也算对</span> 
</p>
</div>
<h3>
【题目来源】
</h3>
<a href="http://www.lydsy.com/JudgeOnline/problem.php?id=1011">耒阳大世界（衡阳八中） OJ 1011</a>
