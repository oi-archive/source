<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给你一个中缀表达式,请你转换成后缀表达式</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一个中缀表达式</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个后缀表达式</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>((5+7)/3*7-(3*2))+(7-3)*3+2*5+4*5+1*6+1*5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>57+3/7*32*-73-3*+25*+45*+16*+15*+</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>好好想,亲们!</p>
<p>我想说的是：这题是没有数据范围的，但是里面的数字都是int范围的正整数，表达式求出结果也一定是int范围的整数，尽管...你不需要求的。</p>
<p>某种方法：</p>
<p>平常我们书写的表达式称为中缀表达式，因为它将运算符放在两个操作数中间，许多情况下为了确定运算顺序，括号是不可少的，而中缀表达式就不必用括号了。</p>
<p>后缀标记法：书写表达式时采用运算紧跟在两个操作数之后，从而实现了无括号处理和优先级处理，使计算机的处理规则简化为：从左到右顺序完成计算，并用结果取而代之。</p>
<p>例如：<span>8</span><span>–</span><span>(3+2*6)/5+4</span><span>可以写为：</span><span>8</span> 3 2 6*+5/<span>–</span><span>4+</span></p>
<p>其计算步骤为：<span>8  3   2  6  *  +  5  /  </span><span>–  </span><span>4  + </span></p>
<p>              8  3  12  +  5  /  <span>–  </span><span>4  + </span></p>
<p>              8  15  5  /  <span>–  </span><span>4  + </span></p>
<p>              8  3  <span>–  </span><span>4  + </span></p>
<p>              5  4  + </p>
</div>
</div>