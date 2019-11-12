# 题目描述


<div class="jsk-padding-top guide-content">
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
Description
</h3>
There is a tree with <span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>n</mi></mrow><annotation encoding="application/x-tex">n</annotation></semantics></math></span></span> nodes. For each node, there is an integer value <span class="katex"><span class="katex-mathml"><math><semantics><mrow><msub><mi>a</mi><mi>i</mi></msub></mrow><annotation encoding="application/x-tex">a_i</annotation></semantics></math></span></span>, (<span class="katex"><span class="katex-html" aria-hidden="true"><span class="base textstyle uncramped"><span class="mord mathrm">1</span><span class="mrel">≤</span><span class="mord"><span class="mord mathit">a_</span><span class="msupsub"><span class="vlist"><span style="top:0.15em;margin-right:0.05em;margin-left:0em;"><span class="fontsize-ensurer reset-size5 size5"><span style="font-size:0em;"></span></span><span class="reset-textstyle scriptstyle cramped mtight"><span class="mord mathit mtight">i</span></span></span><span class="baseline-fix"><span class="fontsize-ensurer reset-size5 size5"><span style="font-size:0em;"></span></span></span></span></span></span><span class="mrel">≤</span><span class="mord mathrm">1</span><span class="mpunct">,</span><span class="mord mathrm">0</span><span class="mord mathrm">0</span><span class="mord mathrm">0</span><span class="mpunct">,</span><span class="mord mathrm">0</span><span class="mord mathrm">0</span><span class="mord mathrm">0</span><span class="mpunct">,</span><span class="mord mathrm">0</span><span class="mord mathrm">0</span><span class="mord mathrm">0</span></span></span></span> for <span class="katex"><span class="katex-html" aria-hidden="true"><span class="base textstyle uncramped"><span class="mord mathrm">1</span><span class="mrel">≤</span><span class="mord mathit">i</span><span class="mrel">≤</span><span class="mord mathit">n</span></span></span></span>). There is <span class="katex"><span class="katex-html" aria-hidden="true"><span class="base textstyle uncramped"><span class="mord mathit" style="margin-right:0.03588em;">q</span></span></span></span> queries which are described as follow: Assume the value on the path from node <span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>a</mi></mrow><annotation encoding="application/x-tex">a </annotation></semantics></math></span></span>to node <span class="katex"><span class="katex-html" aria-hidden="true"><span class="base textstyle uncramped"><span class="mord mathit">b</span></span></span></span> is <span class="katex"><span class="katex-mathml"><math><semantics><mrow><msub><mi>t</mi><mn>0</mn></msub><mo separator="true">,</mo><msub><mi>t</mi><mn>1</mn></msub><mo separator="true">,</mo><mo>⋯</mo><msub><mi>t</mi><mi>m</mi></msub></mrow><annotation encoding="application/x-tex">t_0, t_1, ... t_m. </annotation></semantics></math></span></span>You are supposed to calculate <span class="katex"><span class="katex-mathml"><math><semantics><mrow><msub><mi>t</mi><mn>0</mn></msub></mrow><annotation encoding="application/x-tex">t_0</annotation></semantics></math></span></span> xor <span class="katex"><span class="katex-mathml"><math><semantics><mrow><msub><mi>t</mi><mi>k</mi></msub></mrow><annotation encoding="application/x-tex">t_k</annotation></semantics></math></span></span> xor <span class="katex"><span class="katex-mathml"><math><semantics><mrow><msub><mi>t</mi><mrow><mn>2</mn><mi>k</mi></mrow></msub></mrow><annotation encoding="application/x-tex">t_2k</annotation></semantics></math></span></span> xor ... xor <span class="katex"><span class="katex-mathml"><math><semantics><mrow><msub><mi>t</mi><mrow><mi>p</mi><mi>k</mi></mrow></msub></mrow><annotation encoding="application/x-tex">t_pk</annotation></semantics></math></span></span> <span class="katex"><span class="katex-html" aria-hidden="true"><span class="base textstyle uncramped"><span class="mopen">(</span><span class="mord mathit">p</span><span class="mord mathit" style="margin-right:0.03148em;">k</span><span class="mrel">≤</span><span class="mord mathit">m</span><span class="mclose">)</span></span></span></span>.
<p>
<br/>
</p>
<h3>
Input Format
</h3>
<p>
There is only 1 dataset.<span class="katex"><span class="katex-html" aria-hidden="true"><span class="base textstyle uncramped"><span class="mopen">(</span><span class="mord mathit">n</span><span class="mrel">≤</span><span class="mord mathrm">5</span><span class="mord mathrm">0</span><span class="mpunct">,</span><span class="mord mathrm">0</span><span class="mord mathrm">0</span><span class="mord mathrm">0</span><span class="mpunct">,</span><span class="mord mathit" style="margin-right:0.03588em;">q</span><span class="mrel">≤</span><span class="mord mathrm">5</span><span class="mord mathrm">0</span><span class="mord mathrm">0</span><span class="mpunct">,</span><span class="mord mathrm">0</span><span class="mord mathrm">0</span><span class="mord mathrm">0</span><span class="mclose">)</span></span></span></span>.<br/>
First 2 integers n,q
</p>
<p>
In the first <span class="katex"><span class="katex-html" aria-hidden="true"><span class="base textstyle uncramped"><span class="mord mathit">n</span><span class="mbin">−</span><span class="mord mathrm">1</span></span></span></span> lines, there are two integers u<span class="katex"><span class="katex-html" aria-hidden="true"><span class="base textstyle uncramped"><span class="mpunct">,</span><span class="mord mathit" style="margin-right:0.03588em;">v</span></span></span></span>, indicates there is an edge connect node <span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>u</mi></mrow><annotation encoding="application/x-tex">u</annotation></semantics></math></span></span> and node <span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>v</mi></mrow><annotation encoding="application/x-tex">v</annotation></semantics></math></span></span>.
</p>
<p>
In the next <span class="katex"><span class="katex-html" aria-hidden="true"><span class="base textstyle uncramped"><span class="mord mathit">n</span></span></span></span> lines, There is an integer <span class="katex"><span class="katex-mathml"><math><semantics><mrow><msub><mi>a</mi><mi>i</mi></msub></mrow><annotation encoding="application/x-tex">a_i</annotation></semantics></math></span></span> (<span class="katex"><span class="katex-html" aria-hidden="true"><span class="base textstyle uncramped"><span class="mord mathrm">1</span><span class="mrel">≤</span><span class="mord"><span class="mord mathit">a</span><span class="msupsub"><span class="vlist"><span style="top:0.15em;margin-right:0.05em;margin-left:0em;"><span class="fontsize-ensurer reset-size5 size5"><span style="font-size:0em;"></span></span><span class="reset-textstyle scriptstyle cramped mtight"><span class="mord mathit mtight">i</span></span></span><span class="baseline-fix"><span class="fontsize-ensurer reset-size5 size5"><span style="font-size:0em;"></span></span></span></span></span></span><span class="mrel">≤</span><span class="mord mathrm">1</span><span class="mpunct">,</span><span class="mord mathrm">0</span><span class="mord mathrm">0</span><span class="mord mathrm">0</span><span class="mpunct">,</span><span class="mord mathrm">0</span><span class="mord mathrm">0</span><span class="mord mathrm">0</span><span class="mpunct">,</span><span class="mord mathrm">0</span><span class="mord mathrm">0</span><span class="mord mathrm">0</span></span></span></span>).
</p>
<p>
In the next <span class="katex"><span class="katex-html" aria-hidden="true"><span class="base textstyle uncramped"><span class="mord mathit" style="margin-right:0.03588em;">q</span></span></span></span> lines, There is three integers <span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>a</mi><mo separator="true">,</mo><mi>b</mi></mrow><annotation encoding="application/x-tex">a,b </annotation></semantics></math></span></span>and <span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>k</mi></mrow><annotation encoding="application/x-tex">k</annotation></semantics></math></span></span>. (<span class="katex"><span class="katex-html" aria-hidden="true"><span class="base textstyle uncramped"><span class="mord mathrm">1</span><span class="mrel">≤</span><span class="mord mathit">a</span><span class="mpunct">,</span><span class="mord mathit">b</span><span class="mpunct">,</span><span class="mord mathit" style="margin-right:0.03148em;">k</span><span class="mrel">≤</span><span class="mord mathit">n</span></span></span></span>).
</p>
<h3>
Output Format
</h3>
<p>
For each query, output an integer in one line, without any additional space.
</p>
<p>
<br/>
</p>
<div id="samples">
<div class="jsk-margin-vertical-sm">
<h4 class="title">
样例输入
</h4>
<pre class="jsk-text-danger jsk-text-default jsk-padding-vertical-xs">5 6
1 5
4 1
2 1
3 2
19
26
0
8
17
5 5 1
1 3 2
3 2 1
5 4 2
3 4 4
1 4 5</pre>
</div>
<div class="jsk-margin-vertical-sm">
<h4 class="title">
样例输出
</h4>
<pre class="jsk-text-danger jsk-text-default jsk-padding-vertical-xs">17
19
26
25
0
19</pre>
</div>
</div>
<h4 class="title jsk-margin-top-lg jsk-margin-bottom-sm">
题目来源
</h4>
<p class="jsk-margin-top-sm">
<a class="jsk-text-link" href="//nanti.jisuanke.com/?kw=2017 ACM-ICPC 亚洲区（西安赛区）网络赛">2017 ACM-ICPC 亚洲区（西安赛区）网络赛</a> 
</p>
</div>
