# 题目描述


<h3>
【题目描述】
</h3>
<p class="MsoNormal">
这里是广袤无垠的宇宙这里是一泻千里的银河这里是独一无二的太阳系这里是蔚蓝色的地球这里，就是这里，是富饶的中国大陆！这里是神奇的河北大地这里是美丽的唐山
</p>
<p class="MsoNormal">
这里是神话般的唐山一中这里是<span>Akai</span>曾经的教室
</p>
<p class="MsoNormal">
黑板上还留有当年<span>Akai</span>做过的数学作业，其实也并不是什么很困难的题目<span>: </span> 
</p>
<p class="MsoNormal">
<span>“ </span> 
</p>
<p class="MsoNormal" style="margin-left:42.5pt;">
给出一个一元<span>n</span>次方程：
</p>
<p class="MsoNormal" style="margin-left:42.0pt;text-indent:21.0pt;">
<span>a</span><span style="font-size:8.0pt;line-height:111%;">0</span><span> + a</span><span style="font-size:8.0pt;line-height:111%;">1</span><span>x + a</span><span style="font-size:8.0pt;line-height:111%;">2</span><span>x</span><sup><span style="font-size:8.5pt;line-height:111%;">2</span></sup><span> +…+ a</span><span style="font-size:9.0pt;line-height:111%;">n</span><span>x</span><sup><span style="font-size:8.5pt;line-height:111%;">n</span></sup><span>= 0 </span>求此方程的所有有理数解。
</p>
<p class="MsoNormal">
<span>” </span> 
</p>
<p class="MsoNormal">
<span>Akai</span>至今还深刻记得当年熬夜奋战求解的时光他甚至还能记得浪费了多少草稿纸但是却怎么也想不起来最后的答案是多少了你能帮助他么？
</p>
<h3>
【输入格式】
</h3>
<p>
第一行一个整数<span>n</span>。第二行<span>n+1</span>个整数，分别代表<span>a</span><span style="font-size:8.0pt;line-height:111%;">0</span>到<span>a</span><span style="font-size:9.0pt;line-height:111%;">n</span><span></span> 
</p>
<h3>
【输出格式】
</h3>
<p class="MsoNormal">
第一行输出一个整数<span>t</span>，表示有理数解的个数接下来<span>t</span>行，每行表示一个解解以分数的形式输出，要求分子和分母互质，且分母必须是正整数特殊的，如果这个解是一个整数，那么直接把这个数输出等价的解只需要输出一次
</p>
<p class="MsoNormal">
所有解按照从小到大的顺序输出
</p>
<h3>
【样例输入】
</h3>
<pre><p class="MsoNormal" style="margin-left:-.25pt;">
<span>3 </span> 
</p>

<p class="MsoNormal" style="margin-left:-.25pt;">
<span>-24 14 29 6</span> 
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p class="MsoNormal" style="margin-left:-.25pt;">
<span>3 </span> 
</p>

<p class="MsoNormal" style="margin-left:-.25pt;">
<span>-4 </span> 
</p>

<p class="MsoNormal" style="margin-left:-.25pt;">
<span>-3/2 </span> 
</p>

<p class="MsoNormal" style="margin-left:-.25pt;">
<span>2/3 </span> 
</p>
</pre>
<h3>
【提示】
</h3>
<p class="MsoNormal" style="margin-left:-.25pt;">
对于<span>30%</span>的数据，<span>n&lt;=10 </span> 
</p>
<p class="MsoNormal" style="margin-left:-.25pt;">
对于<span>100%</span>的数据，<span>n &lt;=
100</span>，<span>|a</span><span style="font-size:9.0pt;line-height:111%;">i</span><span>| &lt;=
2*10</span><sup><span style="font-size:8.5pt;line-height:111%;">7</span></sup>，<span>a</span><span style="font-size:9.0pt;line-height:111%;">n</span><span>≠ 0<br/>
</span> 
</p>
<h3>
【来源】
</h3>
<p>
HEOI2012
</p>
