<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">对于方程x<sup>2</sup><span style="">≡<span style="">a(mod m)</span></span></span><span style="">，已知a，m，求x∈[0,m-1]使得方程成立</span><span style="">的所有解。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">多组输入数据。</span></p><p><span style="">第一行输入</span><span style="">T，表示有T组输入数据。</span></p><p><span style="">对于每组输入数据，</span><span style="">共一行，</span><span style="">包含</span><span style="">两个数</span><span style="">a</span><span style="">，m。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 宋体;font-size: 14px">对于每组输入数据，</span><span style="font-family: 宋体;font-size: 14px">共一行，</span><span style="font-family: 宋体;font-size: 14px">按大小顺序输出所有解</span><span style="font-family: 宋体;font-size: 14px">。</span></p><p><span style="font-family: 宋体;font-size: 14px">如果对于给定的</span><span style="font-family: 宋体;font-size: 14px">a，m，方程无解，输出-1。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">3</span></p><p><span style="">3 7</span></p><p><span style="">36 77</span></p><p><span style="">18 97</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">-1</span></p><p><span style="">6 27 50 71</span></p><p><span style="">42 55</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<table width="567"><tbody><tr><td style="" valign="top" width="125"><p style=""><span style="">测试点编号</span></p></td><td style="" valign="top" width="115"><p style=""><span style="">m<span style="">的规模</span></span></p></td><td style="" valign="top" width="327"><p style=""><span style="">备注</span></p></td></tr><tr><td style="" valign="top" width="125"><p style=""><span style="">1</span></p></td><td style="" valign="top" width="115"><p style=""><span style="">2</span><span style="">≤</span><span style="">m</span><span style="">≤</span><span style="">10^6</span></p></td><td style="" valign="center" width="327"><p style=""><span style="">无</span></p></td></tr><tr><td style="" valign="top" width="125"><p style=""><span style="">2</span></p></td><td style="" valign="top" width="115"><p style=""><span style="">2</span><span style="">≤</span><span style="">m</span><span style="">≤</span><span style="">10^6</span></p></td></tr><tr><td style="" valign="top" width="125"><p style=""><span style="">3</span></p></td><td style="" valign="top" width="115"><p style=""><span style="">2</span><span style="">≤</span><span style="">m</span><span style="">≤</span><span style="">10^</span><span style="">9</span></p></td><td style="" valign="center" width="327"><p style=""><span style="">m<span style="">为奇质数</span></span></p></td></tr><tr><td style="" valign="top" width="125"><p style=""><span style="">4</span></p></td><td style="" valign="top" width="115"><p style=""><span style="">2</span><span style="">≤</span><span style="">m</span><span style="">≤</span><span style="">10^</span><span style="">9</span></p></td></tr><tr><td style="" valign="top" width="125"><p style=""><span style="">5</span></p></td><td style="" valign="top" width="115"><p style=""><span style="">2</span><span style="">≤</span><span style="">m</span><span style="">≤</span><span style="">10^</span><span style="">9</span></p></td><td style="" valign="center" width="327"><p style=""><span style="">m<span style="">为奇质数的幂，幂指数≥</span><span style="font-family: Times New Roman;">3</span></span></p></td></tr><tr><td style="" valign="top" width="125"><p style=""><span style="">6</span></p></td><td style="" valign="top" width="115"><p style=""><span style="">2</span><span style="">≤</span><span style="">m</span><span style="">≤</span><span style="">10^</span><span style="">9</span></p></td></tr><tr><td style="" valign="top" width="125"><p style=""><span style="">7</span></p></td><td style="" valign="top" width="115"><p style=""><span style="">2</span><span style="">≤</span><span style="">m</span><span style="">≤</span><span style="">10^</span><span style="">9</span></p></td><td style="" valign="center" width="327"><p style=""><span style="">m<span style="">为互不相同的奇质数的积，奇质数个数≥</span><span style="font-family: Times New Roman;">3</span></span></p></td></tr><tr><td style="" valign="top" width="125"><p style=""><span style="">8</span></p></td><td style="" valign="top" width="115"><p style=""><span style="">2</span><span style="">≤</span><span style="">m</span><span style="">≤</span><span style="">10^</span><span style="">9</span></p></td></tr><tr><td style="" valign="top" width="125"><p style=""><span style="">9</span></p></td><td style="" valign="top" width="115"><p style=""><span style="">2</span><span style="">≤</span><span style="">m</span><span style="">≤</span><span style="">10^</span><span style="">9</span></p></td><td style="" valign="center" width="327"><p style=""><span style="">无</span></p></td></tr><tr><td style="" valign="top" width="125"><p style=""><span style="">10</span></p></td><td style="" valign="top" width="115"><p style=""><span style="">2</span><span style="">≤</span><span style="">m</span><span style="">≤</span><span style="">10^</span><span style="">9</span></p></td></tr></tbody></table><p><span style=""> <span style="">0</span><span style="">≤</span><span style="">a</span><span style="">≤<span style=""><span style="">m-1</span></span></span></span></p><p><span style=""><span style=""><span style=""><span style="">1<span style="">≤</span>T<span style="">≤5</span></span></span></span></span></p>
</div>
</div>