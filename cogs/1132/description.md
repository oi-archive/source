# 题目描述


<h3>
	【题目描述】
</h3>

<p>
	二项式展开系数大家已经十分熟悉了：
</p>
<p>
	$$ (x+y)^n = \sum^n_{i=0}{\rm C}_n^i x^iy^{n-1} $$
</p>
<p>
	现在我们将问题推广到任意<span>t</span><span>个实数的和的</span><span>n</span><span>次方 $(x_1+x_2+\cdots +x_t)^n$ 的展开式。我们想知道多项式 $(x_1+x_2+\cdots+x_t)^n$ 中的任意一项 $x_1^{n_1}x_2^{n_2}\cdots x_t^{n_t}$ 的系数。例如，将一个三项式 $(x_1+x_2+x_3)^3$ 展开后，可以得到：</span> 
</p>
<p>
	\[\begin{array}{ll}  (x_1+x_2+x_3)^3 &amp; = x_1^3+x_2^3+x_3^3 \\ &amp; + 3x_1^2x_2+3x_1^2x_3 \\ &amp; + 3x_1x_2^2+3x_1x_3^2 \\ &amp; + 3x_2^2x_3+3x_2x_3^2 \\ &amp; + 6x_1x_2x_3 \end{array} \]
</p>
<p>
	其中， $x_1^2x_2$ 的系数为<span>3</span> 
</p>

<h3>
	【输入格式】
</h3>

<p>
	第一行，两个整数<span>n</span><span>和</span><span>t</span><span>，中间用空格分隔。分别表示多项式幂和项数。</span> 
</p>
<p>
	第二行，<span>t</span><span>个整数</span><span>n</span>1, n2, <span>…， </span><span>n</span>t，中间用空格分隔。分别表示<span>x</span>1, x2, <span>…</span><span>, x</span>n的幂。（<span>n</span>1+n2+<span>…</span><span>+n</span>t=n<span>，</span><span>1</span><span>≤</span><span>n, t</span><span>≤</span><span>12</span><span>）</span> 
</p>

<h3>
	【输出格式】
</h3>
<p>
	仅一行，一个整数（保证在长整型范围内）。表示多项式(x1+x2+<span>…</span><span>+x</span>t)n中的项的系数。
</p>

<h3>
	【样例输入】
</h3>
<pre>3 3
2 1 0</pre>
<h3>
	【样例输出】
</h3>
<pre>3</pre>
