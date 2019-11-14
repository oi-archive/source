<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一天，Jidder在<strong>C++</strong>中沉浸着。<br></p><p>但是他总是无法安静的打代码，因为他十分粗心，总是把定义句写错。</p><p>他没有办法，求你编一个程序，判断他的定义句有没有写错。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一行字符串，如int a;或char b[10];<br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>若正确，输出&quot;T&quot;，反之，输出&quot;F&quot;。<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1.unsigned int a[10];</p><p><br></p><p>2.chra che;</p><p><br></p><p>3.int array[10;]</p><p><br></p><p>4.long long b</p><p><br></p><p>5.long int<span style=""> x;</span></p><p><br></p><p>6.string a;</p><p><br></p><p>7.short xeri;</p><p><br></p><p>8.int codevs[rules];</p><p><br></p><p>9.long op;</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<ol style=""><li><p>T<br></p></li><li><p>F</p></li><li><p>F</p></li><li><p>F</p></li><li><p>T</p></li><li><p>F</p></li><li><p>T</p></li><li><p>T</p></li><li><p>T<br></p></li></ol><p>//6: 并没有考察string，所以是F。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>C++</strong>定义句。</p><p>只考察int,long,float,double,short,unsigned,char,以及以上各种拼起来的。</p><p>如 long double,unsigned char.</p><ol style=""><li><p>不会有赋值错误，只有一个定义语句，如"int a;"，不会有"int a[]={1,2,3};"、int x=23;等。</p></li><li><p>不会有指针，以及其它vector、map等。</p></li><li><p>不会有逗号，如"int a,b,c";</p></li><li><p>记得每一个字符都是挨着的如 "int a [_10_]_;"(  _ 指空格）&lt;-不会有这样的数据，但int和变量名之间是有空格的。</p></li><li><p>数组中的可以是另外一个变量，如int a[iroe];</p></li><li><p>变量名称有问题不考虑。如 "int float[10];","int k[int];","int array[-3-];"这都算"T"。</p></li><li><p>注意后面的分号，下划线。</p></li></ol>
</div>
</div>