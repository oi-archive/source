<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<ul><li><p>描述</p></li><li><p>Problems involving the computation of exact values of very
large magnitude and precision are common. For example, the computation
of the national debt is a taxing experience for many computer systems. <br><br>This problem requires that you write a program to compute the exact value of R<sup>n</sup>where R is a real number ( 0.0 &lt; R &lt; 99.999 ) and n is an integer such that 0 &lt; n &lt;= 25.</p></li></ul>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<ul><li><p>输入</p></li><li><p>The input will consist of a set of pairs of values for R and n.
The R value will occupy columns 1 through 6, and the n value will be in
columns 8 and 9.</p></li></ul><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<ul class="problem-content list-paddingleft-2"><li><p>输出</p></li><li><p>The output will consist of one line for each line of input giving
the exact value of R^n. Leading zeros should be suppressed in the
output. Insignificant trailing zeros must not be printed. Don&#39;t print
the decimal point if the result is an integer.</p></li></ul><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<ul><li><p>样例输入</p></li><li><pre>95.123 12
0.4321 20
5.1234 15
6.7592  9
98.999 10
1.0100 12</pre></li></ul><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<ul><li><p>样例输出</p></li><li><pre>548815620517731830194541.899025343415715973535967221869852721
.00000005148554641076956121994511276767154838481760200726351203835429763013462401
43992025569.928573701266488041146654993318703707511666295476720493953024
29448126.764121021618164430206909037173276672
90429072743629540498.107596019456651774561044010001
1.126825030131969720661201</pre></li></ul><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<ul><li><p>提示</p></li><li><p>If you don't know how to determine wheather encounted the end of input:<br><em>s</em> is a string and <em>n</em> is an integer<br></p><pre>while(cin&gt;&gt;s&gt;&gt;n)
{
...
}

while(scanf("%s%d",s,&amp;n)==2) //to  see if the scanf read in as many items as you want
/*while(scanf(%s%d",s,&amp;n)!=EOF) //this also work    */
{
...
}</pre></li></ul><p><br></p>
</div>
</div>