<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">（p.s.赶时间的可以直接跳到<em><strong><span style="font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, sans-serif;">数据范围及提示</span></strong></em>）</span></p><p><span style="">《三体》第三部《死神永生》中，圣母程心与其闺蜜艾AA乘坐曲率飞船“星环号”成功躲避了二向箔的打击，并离开被二维化的太阳系，前往云天明“送给她”的<span style="">DX3906星系。</span></span></p><p><span style="">（以下开始胡扯）</span></p><p><span style="">假如此时不止一张二向箔对太阳系进行打击，“星环号”必然要设计一种程序来对每张二向箔的打击进行评估并作出反应。而对这种空间降维武器进行评估的一项重要指标就是覆盖面积。为了方便起见，我们假设所有打击同时来到，所有二向箔都是平行于笛卡尔坐标平面的矩形，不同平面的二向箔会相互吸引并合成，而且不考虑合成后形状的变化。现在请你编一个程序，测算所有二向箔合成后覆盖的面积。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：一个数N<br></p><p>第二至N+1行：每行四个数，分别为x1,y1,x2,y2，表示矩形的左上角坐标和右下角坐标。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: 16px;">如题，一行一个数，表示<span style="color: rgb(51, 51, 51); font-family: arial, 宋体, sans-serif; line-height: 24px; text-indent: 28px; background-color: rgb(255, 255, 255);">所有二向箔合成后的面积。</span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p><p>0 5 4 1</p><p>2 4 6 2</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>20</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">如果你觉得<em><strong><span style="font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, sans-serif;">题目描述</span></strong></em></span><span style="">中的</span><span style="">文字的熵过高以至于难以理解的话，那么我把题目简化一下：</span><span style="">在一个笛卡尔平面直角坐标系中，有N个矩形，第i个矩形的左上角坐标是(x1, y1),右下角坐标是(x2,y2)。问这N个矩形所覆盖的面积是多少？（被重复覆盖的区域的面积只算一次）</span></p><p><span style="text-decoration: underline;"><strong><span style="text-decoration: underline;">对于100%的数据，-10^5&lt;=x1,y1,x2,y2&lt;=10^5,n&lt;=10，</span></strong></span><strong style=""><span style="text-decoration: underline;">保证答案在64位整型内</span></strong></p>
</div>
</div>