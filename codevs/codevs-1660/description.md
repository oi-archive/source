<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>相信大家都用过计算器，一般来说，计算机都可以计算简单的 加、减、乘、除这几种运算。简易计算器的功能和一般的计算器一样，只是它更加简单，只能处理整数运算，也就是说，它没有小数点按钮，并且它的除法运算是整除运算。</p>
<p> </p>
<p>现在，我们给出简易计算器上的按钮序列，请你编程序，模拟简易计算器的功能，输出最终的结果。</p>
<p> </p>
<p> </p>
<p> </p>
<p>【计算器组成】</p>
<p> </p>
<p>简易计算器由以下按钮组成：</p>
<p> </p>
<p>数字按钮： <span style="font-family: 'Times New Roman';">0 1 2 3 4 5 6 7 8 9</span></p>
<p> </p>
<p>运算按钮： <span style="font-family: 'Times New Roman';">+ - * / </span></p>
<p> </p>
<p>等于号按钮：<span style="font-family: 'Times New Roman';">=</span></p>
<p> </p>
<p>正负转换按钮：<span style="font-family: 'Times New Roman';">+/- </span></p>
<p> </p>
<p>为了表述方便，<span style="font-family: 'Times New Roman';">+/- </span><span style="">按钮用 </span><span style="font-family: 'Times New Roman';">F </span><span style="">表示 ，</span></p>
<p> </p>
<p> </p>
<p> </p>
<p>【计算器逻辑处理】</p>
<p> </p>
<p>   计算器内存有<span style="font-family: 'Times New Roman';">3</span><span style="">个值，</span><span style="font-family: 'Times New Roman';">M1</span><span style="">，</span><span style="font-family: 'Times New Roman';">M2</span><span style="">，</span><span style="font-family: 'Times New Roman';">OP</span><span style="">，</span><span style="font-family: 'Times New Roman';">ST</span></p>
<p> </p>
<p>M1<span style="">为计算器的左运算值，初始值为</span><span style="font-family: 'Times New Roman';">0</span></p>
<p> </p>
<p>M2<span style="">为计算器的右运算值，初始值</span><span style="font-family: 'Times New Roman';">0</span></p>
<p> </p>
<p>OP<span style="">为计算器的当前运算符，初始值为空</span></p>
<p> </p>
<p>ST<span style="">为状态标记，初始值为</span><span style="font-family: 'Times New Roman';">0</span></p>
<p> </p>
<p> </p>
<p> </p>
<p>状态装换逻辑如下：</p>
<p> </p>
<p> </p>
<p> </p>
<p>ST=0   (M1/OP<span style="">输入态</span><span style="font-family: 'Times New Roman';">)</span><span style="">：</span></p>
<p> </p>
<p>显示值：<span style="font-family: 'Times New Roman';">M1</span></p>
<p> </p>
<p> 输入数字<span style="font-family: 'Times New Roman';">N </span><span style="">： </span></p>
<p> </p>
<p>M1=N <span style="">，转 </span><span style="font-family: 'Times New Roman';">ST=1</span><span style="">状态</span></p>
<p> </p>
<p> 输入<span style="font-family: 'Times New Roman';">F </span><span style="">： </span></p>
<p> </p>
<p>M1=-M1<span style="">，转 </span><span style="font-family: 'Times New Roman';">ST=0</span><span style="">状态</span></p>
<p> </p>
<p> 输入运算符： </p>
<p> </p>
<p>OP=<span style="">运算符，转</span><span style="font-family: 'Times New Roman';">ST=2</span><span style="">状态</span></p>
<p> </p>
<p> 输入“<span style="font-family: 'Times New Roman';">=</span><span style="">”：  </span></p>
<p> </p>
<p>转 <span style="font-family: 'Times New Roman';">ST=0</span><span style="">状态</span></p>
<p> </p>
<p> </p>
<p> </p>
<p>ST=1   (M1+/OP<span style="">输入态</span><span style="font-family: 'Times New Roman';">)</span><span style="">：</span></p>
<p> </p>
<p>显示值：<span style="font-family: 'Times New Roman';">M1</span></p>
<p> </p>
<p> 输入数字<span style="font-family: 'Times New Roman';">N </span><span style="">： </span></p>
<p> </p>
<p>如果<span style="font-family: 'Times New Roman';">M1&gt;=0</span><span style="">则 </span><span style="font-family: 'Times New Roman';">M1=M1*10+N </span><span style="">否则</span><span style="font-family: 'Times New Roman';">M1=M1*10-N;</span></p>
<p> </p>
<p>转 <span style="font-family: 'Times New Roman';">ST=1</span><span style="">状态；</span></p>
<p> </p>
<p> 输入<span style="font-family: 'Times New Roman';">F </span><span style="">： </span></p>
<p> </p>
<p>M1=-M1<span style="">，转 </span><span style="font-family: 'Times New Roman';">ST=1</span><span style="">状态；</span></p>
<p> </p>
<p> 输入运算符： </p>
<p> </p>
<p>OP=<span style="">运算符，转</span><span style="font-family: 'Times New Roman';">ST=2</span><span style="">状态</span></p>
<p> </p>
<p> 输入“<span style="font-family: 'Times New Roman';">=</span><span style="">”：  </span></p>
<p> </p>
<p>转 <span style="font-family: 'Times New Roman';">ST=0</span><span style="">状态</span></p>
<p> </p>
<p> </p>
<p> </p>
<p>ST=2   (OP/M2<span style="">输入态</span><span style="font-family: 'Times New Roman';">)</span><span style="">：</span></p>
<p> </p>
<p>显示值：<span style="font-family: 'Times New Roman';">M1</span></p>
<p> </p>
<p> 输入数字<span style="font-family: 'Times New Roman';">N</span><span style="">： </span></p>
<p> </p>
<p>M2=N<span style="">，转</span><span style="font-family: 'Times New Roman';">ST=3</span><span style="">状态</span><span style="font-family: 'Times New Roman';">;</span></p>
<p> </p>
<p>输入<span style="font-family: 'Times New Roman';">F</span><span style="">： </span></p>
<p> </p>
<p>M2=0<span style="">，转 </span><span style="font-family: 'Times New Roman';">ST=3</span><span style="">状态；</span></p>
<p> </p>
<p> 输入运算符：</p>
<p> </p>
<p>OP=<span style="">运算符，转</span><span style="font-family: 'Times New Roman';">ST=2</span><span style="">状态</span></p>
<p> </p>
<p> 输入“<span style="font-family: 'Times New Roman';">=</span><span style="">”： </span></p>
<p> </p>
<p> 转 <span style="font-family: 'Times New Roman';">ST=0</span><span style="">状态</span></p>
<p> </p>
<p> </p>
<p> </p>
<p>ST=3   (M2+/OP<span style="">输入态</span><span style="font-family: 'Times New Roman';">)</span><span style="">：</span></p>
<p> </p>
<p>显示值：<span style="font-family: 'Times New Roman';">M2</span></p>
<p> </p>
<p> 输入数字<span style="font-family: 'Times New Roman';">N</span><span style="">： </span></p>
<p> </p>
<p>如果<span style="font-family: 'Times New Roman';">M2&gt;=0</span><span style="">则 </span><span style="font-family: 'Times New Roman';">M2=M2*10+N </span><span style="">否则</span><span style="font-family: 'Times New Roman';">M2=M2*10-N</span><span style="">；</span></p>
<p> </p>
<p>转<span style="font-family: 'Times New Roman';">ST=3</span><span style="">状态；</span></p>
<p> </p>
<p>输入<span style="font-family: 'Times New Roman';">F</span><span style="">： </span></p>
<p> </p>
<p>M2=-M2<span style="">，转 </span><span style="font-family: 'Times New Roman';">ST=3</span><span style="">状态；</span></p>
<p> </p>
<p> 输入运算符：</p>
<p> </p>
<p>M1=[M1][OP][M2] <span style="">的值</span></p>
<p> </p>
<p>OP=<span style="">运算符；</span></p>
<p> </p>
<p>转<span style="font-family: 'Times New Roman';">ST=2</span><span style="">状态 </span></p>
<p> </p>
<p> 输入“<span style="font-family: 'Times New Roman';">=</span><span style="">”：  转 </span><span style="font-family: 'Times New Roman';">ST=0</span><span style="">状态</span></p>
<p> </p>
<p>M1=[M1][OP][M2] <span style="">的值</span></p>
<p> </p>
<p>转<span style="font-family: 'Times New Roman';">ST=0</span><span style="">状态 </span></p>
<p> </p>
<p> </p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入只有一行，表示在计算器输入的按钮，长度<span>&lt;=100</span><span>，里面只包含如下字符 </span><span>:</span></p>
<p>0123456789+-*/=F</p>
<p>输入数据保证不会出现除以<span>0</span><span>的 情况，运算过程中各个内存的值的范围在</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;输出包含一行整数，表示最后在计算器显示的结果</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>123=*2F-+/3+-=</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p> -82</p>

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