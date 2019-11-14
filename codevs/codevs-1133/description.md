<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>对于 1 位二进制变量定义两种运算：</span><br><span>运算符 运算规则</span><br><span>⊕</span><br><span>0⊕0=0</span><br><span>0⊕1=1</span><br><span>1⊕0=1</span><br><span>1⊕1=1</span><br><span>×</span><br><span>0 × 0=0</span><br><span>0 × 1=0</span><br><span>1 × 0=0</span><br><span>1 × 1=1</span><br><br><span>运算的优先级是：</span><br><span>1. 先计算括号内的，再计算括号外的。</span><br><span>2. “×”运算优先于“⊕”运算，即计算表达式时，先计算×运算，再计算⊕运算。</span><br><span>例如：计算表达式A⊕B × C 时，先计算B × C，其结果再与A 做⊕运算。</span><br><span>现给定一个未完成的表达式，例如_+(_*_)，请你在横线处填入数字0 或者1，请<span>有多少种填法可以使得表达式的值为0。</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第 1 行为一个整数L，表示给定的表达式中除去横线外的运算符和括号的个数。<br>第 2 行为一个字符串包含L 个字符，其中只包含’（’、’）’、’+’、’*’这4 种字符，其中’（’、’）’是左右括号，’+’、’*’分别表示前面定义的运算符“⊕”和“×”。这行字符按顺序给出了给定表达式中除去变量外的运算符和括号。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共1 行。包含一个整数，即所有的方案数。注意：这个数可能会很大，请输出方案数对10007 取模后的结果。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4<br>+(*)</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>给定的表达式包括横线字符之后为：_+(_*_)<br>在横线位置填入(0、0、0)、(0、1、0)、(0、0、1)时，表达式的值均为0，所以共有3种填法。</p>
<p><br>数据范围<br>对于 20%的数据有0 ≤L≤ 10。<br>对于 50%的数据有0 ≤L≤ 1,000。<br>对于 70%的数据有0 ≤L≤ 10,000。<br>对于 100%的数据有0 ≤L≤ 100,000。<br>对于 50%的数据输入表达式中不含括号。</p>
</div>
</div>