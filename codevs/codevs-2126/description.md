<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小E在好友小W的家中发现一幅神奇的图画，对此颇有兴趣。它可以被看做一个包含<em>N</em>×<em>M</em>个像素的黑白图像，为了方便起见，我们用0表示白色像素，1表示黑色像素。小E认为这幅图画暗藏玄机，因此他记录下了这幅图像中每行、每列的黑色像素数量，以回去慢慢研究其中的奥妙。</p>
<p>有一天，小W不慎将图画打湿，原本的图像已经很难分辨。他十分着急，于是找来小E，希望共同还原这幅图画。根据打湿后的图画，他们无法确定真正的图像，然而可以推测出每个像素原本是黑色像素的概率<em>P<sub>ij</sub></em>%。那么，一个完整的图像的出现概率就可以定义为，其中<em>S<sub>ij</sub></em>表示在还原后的图像中，像素是白色(0)还是黑色(1)。换句话说，一个完整图像出现概率就等于其所有黑色像素的出现概率之积。显然，图像的黑色像素不能包含概率为0的像素。</p>
<p>然而，小E对此也无能为力。因此他们找到了会编程的小F，也就是你，请你根据以上信息，告诉他们最有可能是原始图像的答案是什么。</p>

<img src="/source/codevs/codevs-2126/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yMTI2L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2NzE2MDYzNi4xMTAuOTg2NTk5MjM2MDE1LnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是两个正整数<em>N</em>和<em>M</em>，表示图像大小。</p>
<p>接下来<em>N</em>行每行包含<em>M</em>个整数，表示每个像素是黑色像素的概率为<em>P<sub>ij</sub></em>%。0 ≤ <em>P<sub>ij</sub></em> &lt; 100。</p>
<p>接下来一行有<em>N</em>个非负整数，表示每一行中黑色像素的个数。</p>
<p>接下来一行有<em>M</em>个非负整数，表示每一列中黑色像素的个数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包含一个<em>N</em>&times;<em>M</em>的01矩阵，表示你还原出的图像。输出不包含空格。图像每行、每列中1的个数必须与输入一致，且是所有可能的图像中出现概率最大的一个。输入数据保证至少存在一个可能的图像。如果有多种最优图像，任意输出一种即可。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 2</p>
<p>90 10</p>
<p>20 80</p>
<p>1 1</p>
<p>1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10</p>
<p>01</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据，<em>N </em>, <em>M </em>≤ 5；</p>
<p>对于100%的数据，<em>N </em>, <em>M </em>≤ 100。</p>
</div>
</div>