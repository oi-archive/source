# 题目描述


<div>
USACO/prime3(译by Felicia Crazy )
<hr/>
</div>
<p>
描述
</p>
<p>
 
</p>
<p>
在下面的方格中，每行，每列，以及两条对角线上的数字可以看作是五位的素数。方格中的行按照从左到右的顺序组成一个素数，而列按照从上到下的顺序。两条对角线也是按照从左到右的顺序来组成。
</p>
<pre>+---+---+---+---+---+
| 1 | 1 | 3 | 5 | 1 |
+---+---+---+---+---+
| 3 | 3 | 2 | 0 | 3 |
+---+---+---+---+---+
| 3 | 0 | 3 | 2 | 3 |
+---+---+---+---+---+
| 1 | 4 | 0 | 3 | 3 |
+---+---+---+---+---+
| 3 | 3 | 3 | 1 | 1 |
+---+---+---+---+---+ 
</pre>
<ul>
<li>
这些素数各个数位上的和必须相等。
</li>
<li>
左上角的数字是预先定好的。
</li>
<li>
一个素数可能在方阵中重复多次。
</li>
<li>
如果不只有一个解，将它们全部输出（按照这25个数字组成的25位数的大小排序）。
</li>
<li>
一个五位的素数开头不能为0（例如：00003 不是五位素数）
</li>
</ul>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">PROGRAM NAME: prime3</span> 
</h3>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">INPUT FORMAT(file prime3.in)</span> 
</h3>
<h3>
<span style="font-weight:400;"><span style="font-size:small;">一行包括两个被空格分开的整数:各个位的数字和 和左上角的数字。</span></span> 
</h3>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">OUTPUT FORMAT(file prime3.out)</span> 
</h3>
<h3>
<span style="font-size:small;"><span style="font-weight:400;">对</span></span><span style="font-weight:400;"><span style="font-size:small;">于每一个找到的方案输出5行，每行5个字符, 每行可以转化为一个5位的质数.在两组方案中间输出一个空行. 如果没有解就单独输出一行&#34;NONE&#34;。</span></span> 
</h3>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE INPUT (file prime3.in) </span> 
</h3>
<h3>
<span style="font-weight:400;"><span style="font-size:small;">11 1</span></span> 
</h3>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE OUTPUT (file prime3.out)</span> 
</h3>
<h3>
<span style="font-size:small;"><span style="font-weight:400;">上面的例子有三组解。</span></span> 
</h3>
<h3>
<span style="font-weight:400;"><span style="font-size:small;">11351<br/>
14033<br/>
30323<br/>
53201<br/>
13313<br/>
<br/>
11351<br/>
33203<br/>
30323<br/>
14033<br/>
33311<br/>
<br/>
13313<br/>
13043<br/>
32303<br/>
50231<br/>
13331</span></span> 
</h3>
<p>
 
</p>
<p>
<br/>
</p>
