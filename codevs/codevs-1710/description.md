<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>7月17日是Mr.W的生日，ACM-THU为此要制作一个体积为Nπ的M层生日蛋糕，每层都是一个圆柱体。</p>
<p>设从下往上数第i(1&lt;=i&lt;=M)层蛋糕是半径为R<sub>i</sub>,高度为H<sub>i</sub>的圆柱。当i&lt;M时，要求R<sub>i</sub>&gt;R<sub>i+1</sub>且H<sub>i</sub>&gt;H<sub>i+1</sub>。</p>
<p>由于要在蛋糕上抹奶油，为尽可能节约经费，我们希望蛋糕外表面（最下一层的下底面除外）的面积Q最小。</p>
<p>令Q= Sπ</p>
<p>请编程对给出的N和M，找出蛋糕的制作方案（适当的R<sub>i</sub>和H<sub>i</sub>的值），使S最小。</p>
<p><strong>（除Q外，以上所有数据皆为正整数）</strong></p>

<img src="/source/codevs/codevs-1710/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNzEwL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2NTIzMDM4Ni4zMC44NzU5MDgwMjIxNzIucG5n.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>有两行，第一行为N（N&lt;=10000），表示待制作的蛋糕的体积为Nπ；第二行为M(M&lt;=20)，表示蛋糕的层数为M。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一行，是一个正整数<span lang="EN-US">S</span>（若无解则<span lang="EN-US">S=0</span>）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>100<br>2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>68</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>体积V=πR<sup>2</sup>H</p>
<p>侧面积A’=2πRH</p>
<p>底面积A=πR<sup>2</sup></p>
</div>
</div>