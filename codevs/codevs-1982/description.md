<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Rivest是密码学专家。近日他正在研究一种数列E={E[1],E[2],……,E[n]}，<br>且E[1]=E[2]=p（p为一个质数），E[i]=E[i-2]*E[i-1] （若2&lt;i&lt;=n）。<br>例如{2,2,4,8,32,256,8192,……}就是p=2的数列。在此基础上他又设计了一种加密<br>算法，该算法可以通过一个密钥q (q&lt;p)将一个正整数n加密成另外一个正整数d，计<br>算公式为：d=E[n] mod q。现在Rivest想对一组数据进行加密，但他对程序设计不太<br>感兴趣，请你帮助他设计一个数据加密程序。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>读入m，p。其中m表示数据个数，p用来生成数列E。<br>以下有m行，每行有2个整数n，q。n为待加密数据，q为密钥。<br>规模：0&lt;p,n&lt;2^31；0&lt;q&lt;p；0&lt;m&lt;=5000。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>将加密后的数据按顺序输出到文件a.out。<br />第i行输出第i个加密后的数据。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 7<br>4 5<br>4 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3<br>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>