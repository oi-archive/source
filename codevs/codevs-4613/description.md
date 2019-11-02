<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在广东省，初二有一个最学渣的人叫做黄俊儒，对三角函数运算一窍不通。最近，他还自不量力想研究一下倍角公式，请聪明且学神的你写一个程序，帮助黄学渣计算三角函数。<br></p><p>（补充知识：</p><p style="font-family: arial, sans-serif;">sin(α+β)=sinαcosβ+cosαsinβ</p><p style="font-family: arial, sans-serif;">sin(α-β)=sinαcosβ-cosαsinβ</p><p style="font-family: arial, sans-serif;">cos(α+β)=cosαcosβ-sinαsinβ</p><p style="font-family: arial, sans-serif;">cos(α-β)=cosαcosβ+sinαsinβ</p><p style="font-family: arial, sans-serif;">tan(α+β)=(tanα+tanβ)/(1-tanαtanβ)</p><p style="font-family: arial, sans-serif;">tan(α-β)=(tanα-tanβ)/(1+tanαtanβ)</p><p style="font-family: arial, sans-serif;"><span style="">versinθ =1-cosθ</span><span style=""> </span></p><p style="font-family: arial, sans-serif;"><span style="">vercosθ =1-sinθ</span></p><p style="font-family: arial, sans-serif;"><span style=""></span></p><p>常用泰勒展开式<br>e^x =
1+x+x^2/2!+x^3/3!+……+x^n/n!+……<br>ln(1+x)=x-x^2/2+x^3/3-……+(-1)^(k-1)*(x^k)/k +
……(|x|&lt;1)</p><p> &lt;wbr/&gt;</p><p>sin x = x-x^3/3!+x^5/5!-……+(-1)^(k-1)*(x^(2k-1))/(2k-1)!+……。(-∞<br>cos x =
1-x^2/2!+x^4/4!-……+(-1)k*(x^(2k))/(2k)!+…… (-∞</p><p> &lt;wbr/&gt;</p><p>arcsin x = x + 1/2*x^3/3 + 1*3/(2*4)*x^5/5 + ……(|x|&lt;1)<br>arccos x = π - (
x + 1/2*x^3/3 + 1*3/(2*4)*x^5/5 + …… ) (|x|&lt;1)<br>arctan x = x - x^3/3 +
x^5/5 -……(x≤1)<br></p><p style="font-family: arial, sans-serif;"><span style=""><br></span><br></p><p>（不准用N倍角公式）  JSY=ZJY LXM=ZJY    FXR=LXY=LT WYL=LSY MKQ=LSY</p><p>LH=LSY ZB=KX GMD=RXQ DJZ=KZQ HXY=LT=LGR ZWJ=KZQ=LT=ZJY=RXQ=LGR DLH=YJL</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入共4行；</p><p>第一行为三角函数类型（如：正弦函数 sin   余弦函数 cos   正切函数 tan   余切函数 cot   正割函数 sec   余割函数 csc   正<span style="font-family: arial;">矢函数</span> versin  <span style=""> 余<span style="font-family: arial;">矢函数</span></span> <span style="">vercos）</span></p><p><span style="">第二行为度数（如pai/6,pai/10)</span></p><p style="">第三行为函数的值（如第一行为 cos ，第二行为pai/6 ，则此行输出0.866(保留三位小数））</p><p style=""> </p><p style="">第四行为他要求的N倍角的倍数（如10,11,19,33,46等）</p><p style=""><img src="/source/codevs/codevs-4613/img/aHR0cDovL3AwLnNvLnFoaW1nLmNvbS90MDFhODQzOTdiODNjOWM2YjE1LnBuZw==.png" style="" title="点击查看源网页"><br></p><p><span style=""><br></span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行，输出N倍角的值。（不会有错误数值）（保留1位小数）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>tan<br></p><p>pai/6</p><p>0.577<br></p><p>2</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1.7<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>100%的数据&lt;20</p><p>50%的数据&lt;10</p>
</div>
</div>