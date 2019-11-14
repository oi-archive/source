<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">某一天，</span>tenshi<span style="">看了一本趣味数学书，上面提到了亲和数：定义数对</span> (x,y) <span style="">为亲和数对当且仅仅当</span>x<span style="">、</span>y<span style="">为不同正整数，且</span>x<span style="">、</span>y<span style="">各自的所有非自身正因子之和等于另一个数。例如</span> (220,284) <span style="">和</span> (280,224) <span style="">都是亲和数对，因为：</span></p><p>220<span style="">的所有非自身正因子之和为：</span>1 + 2 + 4 + 5 + 10 + 11 + 20 + 22 + 44 + 55 + 110 = 284</p><p>284<span style="">的所有非自身正因子之和为：</span>1 + 2 + 4 + 71 + 142 = 220</p><p style=""><span style="">数对</span> (x,y ) <span style="">跟</span> (y,x) <span style="">被认为是同一数对，所以我们只考虑</span> x&lt;y <span style="">的情况。</span></p><p><strong><span style="">任　务　：</span></strong>tenshi<span style="">对某个范围内的亲和数对的数量非常感兴趣，所以希望你能帮她编写一个程序计算给定范围内的亲和数对的数量。给定一个范围</span>A<span style="">到</span>B<span style="">，<em><span style="text-decoration: underline;">如果</span></em></span><em><span style="text-decoration: underline;">A</span></em><em><span style="text-decoration: underline;"><span style="">≤</span></span></em><em><span style="text-decoration: underline;"> </span></em><em><span style="text-decoration: underline;">x </span></em><em><span style="text-decoration: underline;"><span style="">≤</span></span></em><em><span style="text-decoration: underline;"><span style=""> B</span></span></em><em><span style="text-decoration: underline;"><span style="">，则我们称</span></span></em><em><span style="text-decoration: underline;"><span style=""> (x,y)</span></span></em><em><span style="text-decoration: underline;"><span style="">在范围</span></span></em><em><span style="text-decoration: underline;"><span style="">[A,B]</span></span></em><em><span style="text-decoration: underline;"><span style="">内。</span></span></em></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">从文件的第一行分别读入正整数</span>A<span style="">和</span>B</p><p><em>　　　　　</em></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent: 28px;"><span style="font-family:宋体">输出文件只有一行，就是</span>[A,B]<span style="font-family:宋体">内亲和数对的数量</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>200 1200</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><em style=""><span style="">1 </span></em><em style=""><span style="">≤</span></em><em style=""> </em><em style=""><span style="font-family: 'Courier New';">A</span></em><em style=""> </em><em style=""><span style="">≤</span></em><em style=""> </em><em style=""><span style="font-family: 'Courier New';">B</span></em><em style=""> </em><em style=""><span style="">≤</span></em><em style=""><span style=""> 10<sup>8 </sup> </span></em><span style="">且</span> <em style=""><span style="font-family: 'Courier New';">B-A</span></em><em style=""> </em><em style=""><span style="">≤</span></em><em style=""><span style=""> 10<sup>5</sup></span></em></p>
</div>
</div>