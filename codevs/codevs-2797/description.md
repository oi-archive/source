<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Smart<span style="">准备买一个计算器，可是这个计算器上面的数字让</span><span style="font-family: Times New Roman;">Smart</span><span style="">看着非常不习惯，</span><span style="font-family: Times New Roman;">Smart</span><span style="">喜欢</span><span style="font-family: Times New Roman;">7</span><span style="">节型数字。</span></p>
<p>可是购买来的计算器不具备切换功能，于是<span style="font-family: Times New Roman;">Smart</span><span style="">又找到了你，他将给你一串整数，希望你能将他们转换成规定尺寸的</span><span style="font-family: Times New Roman;">7</span><span style="">节型数字。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>包含多组测试数据，每组测试数据包含<span style="font-family: Times New Roman;">2</span><span style="">个整数</span><span style="font-family: Times New Roman;">size,num</span><span style="">，</span><span style="font-family: Times New Roman;">size</span><span style="">表示尺寸，</span><span style="font-family: Times New Roman;">num</span><span style="">表示要你转换的数字。最后一行以</span><span style="font-family: Times New Roman;">size=num=0</span><span style="">结束。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">对于每一组测试数据输出一个整数，表示你转换过后的数字。</p>
<p class="p0">每组测试数据间有一个空行。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 12345</p>
<p>3 67890</p>
<p>0 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>      --   --        -- </p>
<p>   |    |    | |  | |   </p>
<p>   |    |    | |  | |   </p>
<p>      --   --   --   -- </p>
<p>   | |       |    |    |</p>
<p>   | |       |    |    |</p>
<p>      --   --        -- </p>
<p> </p>
<p> ---   ---   ---   ---   --- </p>
<p>|         | |   | |   | |   |</p>
<p>|         | |   | |   | |   |</p>
<p>|         | |   | |   | |   |</p>
<p> ---         ---   ---       </p>
<p>|   |     | |   |     | |   |</p>
<p>|   |     | |   |     | |   |</p>
<p>|   |     | |   |     | |   |</p>
<p> ---         ---   ---   ---</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p>100%的的数据满足：size≤10<span style="">，</span><span style="font-family: Times New Roman;">num</span>≤108。</p>
<p>注意：<span style="font-family: Times New Roman;">'-'</span><span style="">和</span><span style="font-family: Times New Roman;">'_'</span><span style="">是两种字符，</span><span style="font-family: Times New Roman;">'-'</span><span style="">的</span><span style="font-family: Times New Roman;">ASCII</span><span style="">码值为</span><span style="font-family: Times New Roman;">45</span><span style="">，</span><span style="font-family: Times New Roman;">'</span>|'<span style="">的</span><span style="font-family: Times New Roman;">ASCII</span><span style="">码值为</span><span style="font-family: Times New Roman;">124</span><span style="">。</span></p>
</div>
</div>
</div>