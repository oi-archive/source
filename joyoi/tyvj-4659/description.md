# 

 
 # 题目背景 
<pre class="problem-content" style="margin-top: 0px; margin-bottom: 0px; color: rgb(0, 0, 0); font-size: 15px; line-height: normal;">
一方通行收藏了一套书，这套书叫《某百合子的超loli控》（下面我们简称这套书）</pre> 

 
 # 题目描述 
<pre class="problem-content" style="margin-top: 0px; margin-bottom: 0px; color: rgb(0, 0, 0); font-size: 15px; line-height: normal;">
<span class="katex" style="font-family: sans-serif, Arial, Verdana, 'Trebuchet MS';"><span class="katex-mathml"><span class="katex-html"><span class="strut" style="height: 0.75em;"><span class="strut bottom" style="height: 1em; vertical-align: -0.25em;"><span class="base textstyle uncramped"><span class="mord mathit"><span class="mopen">这套书有n</span></span></span></span></span></span></span></span><span class="mrel" style="font-family: sans-serif, Arial, Verdana, 'Trebuchet MS';"><span class="mord"><span class="mord"><span class="mclose">本，每本书有一个编号，从<span class="katex"><span class="katex-mathml">1<span class="katex-html"><span class="strut" style="height: 0.64444em;"><span class="strut bottom" style="height: 0.64444em; vertical-align: 0em;"><span class="base textstyle uncramped"><span class="mord">号到n<span class="katex"><span class="katex-mathml"><span class="katex-html"><span class="strut" style="height: 0.43056em;"><span class="strut bottom" style="height: 0.43056em; vertical-align: 0em;"><span class="base textstyle uncramped"><span class="mord mathit">号。</span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></pre>

<pre class="problem-content" style="margin-top: 0px; margin-bottom: 0px; color: rgb(0, 0, 0); font-size: 15px; line-height: normal;">
<span class="katex"><span class="katex-mathml"><span class="katex-html"><span class="strut" style="height: 0.75em;"><span class="strut bottom" style="height: 1em; vertical-align: -0.25em;"><span class="base textstyle uncramped"><span class="mord mathit"><span class="mopen"><span class="mord mathit"><span class="mrel"><span class="mord"><span class="mord"><span class="mclose"><span class="katex"><span class="katex-mathml"><span class="katex-html"><span class="strut" style="height: 0.64444em;"><span class="strut bottom" style="height: 0.64444em; vertical-align: 0em;"><span class="base textstyle uncramped"><span class="mord"><span class="katex"><span class="katex-mathml"><span class="katex-html"><span class="strut" style="height: 0.43056em;"><span class="strut bottom" style="height: 0.43056em; vertical-align: 0em;"><span class="base textstyle uncramped"><span class="mord mathit">一方把这些书按编号从小到大，从上往下摞成一摞。她对这套书极其重视，不允许任何人动这套书。
有一天最后之作（我们简称LO）翻一方的书橱，一方因为和当妈有约会（黑人问号.jpg），所以家里只有LO。LO对这套书非常好奇，偷偷的看了一下，结果发现这里面竟然有当年当妈和一方相爱相杀（雾）的故事。LO看得出神，结果把一摞书的顺序打乱了。
眼看着一方就要回来了，为了防止手刀，LO需要尽快把这摞书恢复到原先排好序的状态。由于每本书都非常重，而LO的体型又非常娇小，所以LO能做的操作只有把一本书从书堆中抽出来，然后把这本书放到书堆的顶部。
给你打乱的书的顺序，你能帮LO算算最少需要几次上述的操作，她才能把这套书恢复顺序？假如你能算出来的话，LO答应送给你一个御坂妹












的护目镜</span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></pre> 

 
 # 输入格式 
<pre class="problem-content" style="margin-top: 0px; margin-bottom: 0px; color: rgb(0, 0, 0); font-size: 15px; line-height: normal;">
输入包含多组数据。
第一行包含一个正整数<span class="katex"><span class="katex-mathml">T<span class="katex-html"><span class="strut" style="height: 0.75em;"><span class="strut bottom" style="height: 1em; vertical-align: -0.25em;"><span class="base textstyle uncramped"><span class="mord mathit" style="margin-right: 0.13889em;"><span class="mopen">(<span class="mord mathit" style="margin-right: 0.13889em;">T<span class="mrel">&le;<span class="mord">3<span class="mord">0<span class="mclose">)表示数据组数。
对于每组数据，第一行为一个正整数<span class="katex"><span class="katex-mathml">n<span class="katex-html"><span class="strut" style="height: 0.43056em;"><span class="strut bottom" style="height: 0.43056em; vertical-align: 0em;"><span class="base textstyle uncramped"><span class="mord mathit">表示这套书中有多少本书。
接下来一行<span class="katex"><span class="katex-mathml">n<span class="katex-html"><span class="strut" style="height: 0.43056em;"><span class="strut bottom" style="height: 0.43056em; vertical-align: 0em;"><span class="base textstyle uncramped"><span class="mord mathit">个用空格分开的正整数，表示LO打乱后的这摞书的书号顺序（从上往下）。</span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></pre> 

 
 # 输出格式 
<pre class="problem-content" style="margin-top: 0px; margin-bottom: 0px; color: rgb(0, 0, 0); font-size: 15px; line-height: normal;">
对于每组数据，输出一行一个整数，表示LO最少需要几次操作才能将书恢复顺序。</pre>

<p>&nbsp;</p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<hr />
<p><strong>样例输入</strong></p>

<pre class="problem-content" style="margin-top: 0px; margin-bottom: 0px; color: rgb(0, 0, 0); font-size: 15px; line-height: normal;">
2
4
4&nbsp;1&nbsp;2&nbsp;3
5
1&nbsp;2&nbsp;3&nbsp;4&nbsp;5</pre>

<p>&nbsp;</p>

<p><strong>样例输出</strong></p>

<p>3</p>

<p>0</p>

<p><strong>解释</strong></p>

<p>对于第一组数据，我们先把3号书放到最上面，接着操作2号书，最后操作1号书，(4,1,2,3)&rarr;<span style="line-height: 20.8px;">(3,4,1,2)&rarr;(</span><span style="line-height: 20.8px;">2</span><span style="line-height: 20.8px;">,</span><span style="line-height: 20.8px;">3</span><span style="line-height: 20.8px;">,4,1)&rarr;(</span><span style="line-height: 20.8px;">1</span><span style="line-height: 20.8px;">,</span><span style="line-height: 20.8px;">2</span><span style="line-height: 20.8px;">,</span><span style="line-height: 20.8px;">3</span><span style="line-height: 20.8px;">,</span><span style="line-height: 20.8px;">4)&nbsp;这样就有序了</span></p>

<p><span style="line-height: 20.8px;">对于第二组数据，这摞书本来就有序了，所以不需要任何操作</span></p> 

 
 # 提示 
<p>50%的数据，n&le;10</p>

<p>另外存在30%的数据，n&le;1,000</p>

<p>对于100%的数据，n&le;100,000</p> 
