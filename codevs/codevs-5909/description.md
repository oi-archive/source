<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>九连环是由九个彼此套接的圆环和一根横杆组成，九个环从左到右依次为1～9，每个环有两种状 态：1和0，1表示环在杆上，0表示环不在杆上。初始状态是九个环都在杆上，即：111111111，目标状态是九个环都不在杆上，即：000000000，由初始状态到目标状态的变化规则是：</p><p>(1)第一环为无论何时均可自由上下横行；</p><p>(2)第二只环只有在第一环为1时，才能自由上下；</p><p>(3)想要改变第n(n&gt;2)个环的状态，需要先使第一到</p><p>    第(n-2)环均为下杆，且第n-1个环为上杆，而与</p><p>    第n+1个到第9环状态无关；</p><p>(4)每改变一个环，记为一步。现在九连环由111111111变到000000000，求中间第i步的状态。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>仅包含一个整数i。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含中间第i步的状态。如果输入的步数大于实际变换所需的步数，则输出-1。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p><p>500</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>010111111</p><p>-1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>无</p>
</div>
</div>