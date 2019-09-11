# 题目描述


<h3>
【题目描述】
</h3>
<div class="content">
<p>
<span style="font-size:medium;">小T准备在家里摆放几幅画，为此他买来了N幅画和N个画框。为了体现他的品味，小T希望能合理地搭配画与画框，使得其显得既不过于平庸也不太违和。对于第 幅画与第 个画框的配对，小T都给出了这个配对的平凡度Aij 与违和度Bij 。整个搭配方案的总体不和谐度为每对画与画框平凡度之和与每对画与画框违和度的乘积。具体来说，设搭配方案中第i幅画与第Pi个画框配对，则总体不和谐度为</span> 
</p>
<p>
<span style="font-size:medium;"><img alt="" src="http://www.lydsy.com/JudgeOnline/upload/201405/11.jpg" height="96" width="364"/></span> 
</p>
<p>
<span style="font-size:medium;">小T希望知道通过搭配能得到的最小的总体不和谐度是多少。<br/>
</span> 
</p>
</div>
<h3>
【输入格式】
</h3>
<div class="content">
<p>
<span style="font-size:medium;">输入文件第 行是一个正整数T ，表示数据组数，接下来是T组数据。<br/>
对于每组数据，第 行是一个正整数N，表示有N对画和画框。<br/>
第2到第N+1行，每行有N个非负整数，第i+1 行第j个数表示Aij 。<br/>
第N+2到第2*N+1行，每行有N个非负整数，第i+N+1 行第j个数表示Bij 。</span> 
</p>
</div>
<h3>
【输出格式】
</h3>
<div class="content">
<p>
包含T行，每行一个整数，表示最小的总体不和谐度
</p>
</div>
<h3>
【样例输入】
</h3>
<pre>1
3
4 3 2
2 3 4
3 2 1
2 3 2
2 2 4
1 1 3</pre>
<h3>
【样例输出】
</h3>
<pre>30</pre>
<h3>
【提示】
</h3>
<div class="content">
<p>
<br/>
</p>
<p>
<span style="font-size:medium;">第1幅画搭配第3个画框，第2幅画搭配第1个画框，第3 幅画搭配第2个画框，则总体不和谐度为30</span> 
</p>
<br/>
<p>
<span style="font-size:medium;"><br/>
<br/>
N&lt;=70,T&lt;=3,Aij&lt;=200,Bij&lt;=200</span> 
</p>
<p>
<br/>
</p>
</div>
<h3>
【来源】
</h3>
<div class="content">
<p>
<a href="problemset.php?search="></a> 
</p>
</div>
<h3>
【题目来源】
</h3>
<a href="http://www.lydsy.com/JudgeOnline/problem.php?id=3571">耒阳大世界（衡阳八中） OJ 3571</a>
