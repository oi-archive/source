# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">定义如下规则序列</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">字符串</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">：</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1<span>．空序列是规则序列；</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2<span>．如果</span><span>S</span><span>是规则序列，那么</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">S</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">和<span>[S]</span><span>也是规则序列；</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3<span>．如果</span><span>A</span><span>和</span><span>B</span><span>都是规则序列，那么</span><span>AB</span><span>也是规则序列。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">例如，下面的字符串都是规则序列：</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">()，[]，(())，([])，()[]，()[()]</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">而以下几个则不是：</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(，[，]，)(，())，([()</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    现在，给你一些由</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">‘</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">’</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">‘</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">’</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">‘</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">[</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">’</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">‘</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">]</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">’</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">构成的序列，你要做的，是找出一个最短规则序列，使得给你的那个序列是你给出的规则序列的子列。(对于序列</span><span style="font-style:italic;font-size:10.5000pt;font-family:&#39;宋体&#39;;">a</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-style:italic;font-size:10.5000pt;font-family:&#39;宋体&#39;;">a</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，…，</span>an<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">和序列</span><span style="font-style:italic;font-size:10.5000pt;font-family:&#39;宋体&#39;;">b</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">l</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-style:italic;font-size:10.5000pt;font-family:&#39;宋体&#39;;">b</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，…，</span>bn<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，如果存在一组下标</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">≤i</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><i< span=""><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">&lt;…&lt;</span>in<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">≤m，使得a</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">j</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">＝</span>bij<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">对一切</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">≤j≤n成立，那么</span><span style="font-style:italic;font-size:10.5000pt;font-family:&#39;宋体&#39;;">a</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-style:italic;font-size:10.5000pt;font-family:&#39;宋体&#39;;">a</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">…，</span>an<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">就叫做</span><span style="font-style:italic;font-size:10.5000pt;font-family:&#39;宋体&#39;;">b</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-style:italic;font-size:10.5000pt;font-family:&#39;宋体&#39;;">b</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，…，</span>bn<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">的子列。</span> </i<></span> 
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
输入文件仅一行，全部由‘(’，‘)’，‘]’，‘]’组成，没有其他字符，长度不超过<span>100</span><span>。</span> 
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输出文件也仅有一行，全部由</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">‘</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">’</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">‘</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">’</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">‘</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">]</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">’</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">‘</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">]</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">’</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">组成，没有其他字符，把你找到的规则序列输出即可。因为规则序列可能不止一个，因此要求输出的规则序列中嵌套的层数尽可能地少。</span> 
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre>([()</pre>
<h3>
【样例输出】
</h3>
<pre>()[]()</pre>
<pre>最多的嵌套层数为1，如层数为2时的一种为()[()]</pre>
<pre></pre>
