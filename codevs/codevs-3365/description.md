<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>JYY</span><span>有个奇怪的计算器，有一天这个计算器坏了，</span><span>JYY</span><span>希望你能帮助他写一个程序来模拟这个计算器的运算。 </span></p>
<p><span>JYY</span><span>的计算器可以执行</span><span>N</span><span>条预设好的指令。每次</span><span>JYY</span><span>向计算器输入一个正整数</span><span>X</span><span>，计算器就会以</span><span>X</span><span>作为初始值，接着依次执行预设的</span><span>N</span><span>条指令，最后把最终得出的结果返回给</span><span>JYY</span><span>。 </span></p>
<p><span>每一条指令可以是以下四种指令之一：（这里</span><span>a</span><span>表示一个正整数。） </span></p>
<p><span>1</span><span>、</span><span>+ </span><span>a</span><span>：表示将当前的结果加上</span><span>a</span><span>； </span></p>
<p><span>2</span><span>、</span><span>- </span><span>a</span><span>：表示将当前的结果减去</span><span>a</span><span>； </span></p>
<p><span>3</span><span>、</span><span>* </span><span>a</span><span>：表示将当前的结果乘以</span><span>a</span><span>； </span></p>
<p><span>4</span><span>、</span><span>@ </span><span>a</span><span>：表示将当前的结果加上</span><span>a </span><span>* </span><span>X</span><span>（</span><span>X</span><span>是一开始</span><span>JYY</span><span>输入的数）。 </span></p>
<p><span>计算器用于记录运算结果的变量的存储范围是有限的，所以每次运算结束之后会有计算结果溢出的问题。 </span></p>
<p><span>JYY</span><span>的计算器中，存储每计算结果的变量只能存储</span><span>L</span><span>到</span><span>R</span><span>之间的正整数，如果一次指令执行过后，计算结果超过了</span><span>R</span><span>，那么计算器就会自动把结果变成</span><span>R</span><span>，然后再以</span><span>R</span><span>作为当前结果继续进行之后的计算。同理，如果运算结果小于</span><span>L</span><span>，计算器也会把结果变成</span><span>L</span><span>，再接着计算。 </span></p>
<p><span>比如，假设计算器可以存储</span><span>1</span><span>到</span><span>6</span><span>之间的值，如果当前的计算结果是</span><span>2</span><span>，那么在执行 </span><span>+ 5 </span><span>操作之后，存储结果的变量中的值将会是</span><span>6</span><span>。虽然</span><span>2+5</span><span>的实际结果是</span><span>7</span><span>，但是由于</span><span>7</span><span>超过了存储范围的上界，所以结果就被自动更正成了上界的大小，也就是</span><span>6</span><span>。 </span></p>
<p><span>JYY</span><span>一共想在计算器上输入</span><span>Q</span><span>个值，他想知道这</span><span>Q</span><span>个值输入计算器之后，分别会得到什么结果呢？ </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>输入文件的第一行包含三个正整数，</span><span>N</span><span>，</span><span>L</span><span>和</span><span>R</span><span>； </span></p>
<p><span>第接下来</span><span>N</span><span>行，每行一个指令，每个指令如题述，由一个字符和一个正整数组成，字符和正整数中间有一个空格隔开； </span></p>
<p><span>第</span><span>N</span><span>+2</span><span>行包含一个整数</span><span>Q</span><span>，表示</span><span>JYY</span><span>希望输入的数的数量；</span></p>
<p>第接下来Q行每行一个正整数，第k个正整数Xk表示JYY在第k次输入的整数。</p>
<p><span><br></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出Q行每行一个正整数，第k行的整数表示输入Xk后，依次经过N个指令进行计算所得到的结果。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 1 6 </p>
<p>+ 5 </p>
<p>- 3 </p>
<p>* 2 </p>
<p>- 7 </p>
<p>@ 2 </p>
<p>3 </p>
<p>2 </p>
<p>1 </p>
<p>5 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5 </p>
<p>3 </p>
<p>6</p>

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
<p>对于10%的数据满足N, Q ≤ 100 并且指令仅含有 + 和 -； </p>
<p>对于30%的数据满足N ≤ 3000 并且指令值仅含有 + 和 -； </p>
<p>对于50%的数据满足N ≤ 3000，R, a ≤ 106并且指令值仅含有 +，- 和 *； </p>
<p>对于额外30%的数据满足指令值仅含有 +，- 和 @； </p>
<p>对于100%的数据满足1 ≤ N, Q ≤ 105，1 ≤ L ≤ Xk ≤ R ≤ 109，1 ≤ a ≤ 109。  </p>
</div>
</div>
</div>