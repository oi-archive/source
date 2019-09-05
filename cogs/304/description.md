# 题目描述


<p>
问题描述
</p>
<p>
已知一个n元高次方程：
</p>
<p>
<span><img alt="Image:Equation1.gif" src="../../../../mw/images/f/fb/Equation1.gif" border="0" height="41" width="308"/></span> 
</p>
<p>
<span>\[ k_1x_1^{p_1} + k_2x_2^{p_2} + \cdots + k_nx_n^{p_n} = 0 \]</span> 
</p>
<p>
其中：x1, x2, …,xn是未知数，k1,k2,…,kn是系数，p1,p2,…pn是指数。且方程中的所有数均为整数。
</p>
<p>
假设未知数1≤ xi ≤M, i=1,,,n，求这个方程的整数解的个数。
</p>
<p>
输入文件
</p>
<p>
文件的第1行包含一个整数n。第2行包含一个整数M。第3行到第n+2行，每行包含两个整数，分别表示ki和pi。两个整数之间用一个空格隔开。第3行的数据对应i=1，第n+2行的数据对应i=n。
</p>
<p>
<br/>
输出文件
</p>
<p>
文件仅一行，包含一个整数，表示方程的整数解的个数。
</p>
<p>
输入样例
</p>
<pre>3
150
1 2
-1 2
1 2
</pre>
<p>
输出样例
</p>
<pre>178
</pre>
<p>
<br/>
约束条件
</p>
<p>
1&lt;=n&lt;=6；1&lt;=M&lt;=150；
</p>
<p>
<span><img alt="Image:Equation2.gif" src="../../../../mw/images/4/4a/Equation2.gif" border="0" height="36" width="300"/></span> 
</p>
<p>
<span>\[ |k_1M^{p_1}| + |k_2M^{p_2}| + \cdots + |k_nM^{p_n}| &lt; 2^{31} \]</span> 
</p>
<p>
方程的整数解的个数小于2^31。
</p>
<p>
★本题中，指数Pi(i=1,2,……,n)均为正整数。
</p>
