# 

 
 # 题目背景 
<p>CF好题</p> 

 
 # 题目描述 
<div>
<p><span style="line-height: 1.6em;">给你一个含有n个元素的数组</span><span style="line-height: 1.6em;">，你必须用最少的移动数使他成为互质数组</span><span style="line-height: 1.6em;">。</span><span style="line-height: 1.6em;">每次移动中你可以在数组</span><span style="line-height: 1.6em;">的任意位置插入任意一个不超过</span><span class="tex-span" style="line-height: 1.6em;">10<sup class="upper-index">9</sup></span><span style="line-height: 1.6em;">的正整数。</span></p>

<p>矩阵是互质的定义是任意两个相邻的数组元素都是互质的。</p>

<p>在数字的定义中，两个整数a和b如果满足他俩同时只能被一个正整数1整除那个称a和b互质。</p>
</div>

<p>&nbsp;</p> 

 
 # 输入格式 
<div class="input-specification">
<div class="section-title"><span style="line-height: 1.6em;">输入</span></div>

<p>第一行包含整数n（<span class="tex-span">1&thinsp;&le;&thinsp;<i>n</i>&thinsp;&le;&thinsp;1000</span>），n是代表给定数组的元素个数。</p>

<p>第二行包含n个整数<span class="tex-span"><i>a</i><sub class="lower-index"><i>i</i></sub></span>&nbsp;(<span class="tex-span">1&thinsp;&le;&thinsp;<i>a</i><sub class="lower-index"><i>i</i></sub>&thinsp;&le;&thinsp;10<sup class="upper-index">9</sup></span>)&nbsp;-这些为数组a中的元素。</p>
</div>

<div class="output-specification">&nbsp;</div> 

 
 # 输出格式 
<div class="output-specification">
<div class="section-title">&nbsp;</div>

<div class="section-title">输出</div>

<p>第一行打印出整数k，k代表将至少k个元素插入到数组中才能使矩阵变为互质数组。</p>

<p>第二行应该包含n+k个整数&nbsp;<span class="tex-span"><i>a</i><sub class="lower-index"><i>j</i></sub></span>&nbsp;&nbsp;&nbsp;，<span class="tex-span"><i>a</i><sub class="lower-index"><i>j</i></sub></span>&nbsp;&nbsp;&nbsp;&nbsp;为数组a在添加了k个元素之后的数组。</p>

<p>&nbsp;</p>
</div> 

 
 # 提示 
<p>样例数据</p>

<div class="section-title">Example</div>

<div class="sample-test">
<div class="input">
<div class="title">Input</div>

<pre>
3
2&nbsp;7&nbsp;28
</pre>
</div>

<div class="output">
<div class="title">Output</div>

<pre>
1
2&nbsp;7&nbsp;9&nbsp;28</pre>
</div>
</div>

<p>新数组必须是互质的，因此任意两个相邻的的值必须是互质的。并且，新数组必须是原来数组添加k个元素之后得到的。</p> 
