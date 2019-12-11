<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>平常我们书写的表达式称为中缀表达式，因为它将运算符放在两个操作数中间，许多情况下为了确定运算顺序，括号是不可少的，而中缀表达式就不必用括号了。</p>
<p>后缀标记法：书写表达式时采用运算紧跟在两个操作数之后，从而实现了无括号处理和优先级处理，使计算机的处理规则简化为：从左到右顺序完成计算，并用结果取而代之。</p>
<p>例如：<span style="font-family: 'Times New Roman';">8</span><span style="">–</span><span style="font-family: 'Times New Roman';">(3+2*6)/5+4</span><span style="">可以写为：</span><span style="font-family: 'Times New Roman';">8</span> 3 2 6*+5/<span style="">–</span><span style="font-family: 'Times New Roman';">4+</span></p>
<p>其计算步骤为：<span style="font-family: 'Times New Roman';">8  3   2  6  *  +  5  /  </span><span style="">–  </span><span style="font-family: 'Times New Roman';">4  + </span></p>
<p>              8  3  12  +  5  /  <span style="">–  </span><span style="font-family: 'Times New Roman';">4  + </span></p>
<p>              8  15  5  /  <span style="">–  </span><span style="font-family: 'Times New Roman';">4  + </span></p>
<p>              8  3  <span style="">–  </span><span style="font-family: 'Times New Roman';">4  + </span></p>
<p>              5  4  + </p>
<p>              9</p>
<p>   编写一个程序，完成这个转换，要求输出的每一个数据间都留一个空格。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>就一行，是一个后缀表达式。输入的符号中只有这些基本符号“<span style="font-family: 'Times New Roman';">0123456789+-*/^()</span><span style="">”，并且不会出现形如</span><span style="font-family: 'Times New Roman';">2*-3</span><span style="">的格式。</span></p>
<p>表达式中的基本数字也都是一位的，不会出现形如<span style="font-family: 'Times New Roman';">12</span><span style="">形式的数字。</span></p>
<p>所输入的字符串不要判错。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">&nbsp; &nbsp;若干个中缀表达式，第I+1<span style="font-family: 宋体;">行比第</span><span style="font-family: 'Times New Roman';">I</span><span style="font-family: 宋体;">行少一个运算符和一个操作数，最后一行只有一个数字，表示运算结果。</span></p>
<p class="p0">&nbsp;&nbsp;&nbsp;&nbsp;运算的结果可能为负数，&ldquo;<span style="font-family: 'Times New Roman';">/</span><span style="font-family: 宋体;">&rdquo;以整除运算。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>8<span style="">–</span><span style="font-family: 'Times New Roman';">(3+2*6)/5+4</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8  3   2  6  *  +  5  /  <span style="">–  </span><span style="font-family: 'Times New Roman';">4  + </span></p>
<p>8  3  12  +  5  /  <span style="">–  </span><span style="font-family: 'Times New Roman';">4  + </span></p>
<p>8  15  5  /  <span style="">–  </span><span style="font-family: 'Times New Roman';">4  + </span></p>
<p>8  3  <span style="">–  </span><span style="font-family: 'Times New Roman';">4  + </span></p>
<p>5  4  + </p>
<p>9</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>输入 表达式长度 不超过 255</p>
<p>中间不需要高精度计算。每步运算量小于2^31</p>
</div>
</div>