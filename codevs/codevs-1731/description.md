<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>考古学发现，几千年前古梅文明时期的数学非常的发达，他们懂得多位数的加法和乘法，其表达式和运算规则等都与现在<strong><span style="text-decoration: underline;">通常所用</span></strong>的方式完全相同（如整数是十进制，左边是高位，最高位不能为零；表达式为中缀运算，先乘后加等），唯一的区别是其符号的写法与现在不同。有充分的证据表明，古梅文明的数学文字一共有13个符号，与 0,1,2,3,4,5,6,7,8,9,+,*,= 这13个数字和符号（称为现代算符）一一对应。为了便于标记，我们用13个小写英文字母a,b,…m代替这些符号（称为古梅算符）。但是，还没有人知道这些古梅算符和现代算符之间的具体对应关系。</p>
<p>在一个石壁上，考古学家发现了一组用古梅算符表示的等式，根据推断，每行有且仅有一个等号，等号左右两边为运算表达式（只含有数字和符号），并且等号两边的计算结果相等。</p>
<p>假设这组等式是成立的，请编程序破译古梅算符和现代算符之间的对应关系。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>l  输入文件的第一行为等式的个数N（1&lt;=N&lt;=1000），以下N行每行为一个等式。</p>
<p>l  每个等式的长度为5个字符到11个字符。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>l&nbsp; 如果不存在对应关系能够满足这组等式，输出&ldquo;noway&rdquo;和一个换行/回车符。</p>
<p>l&nbsp; 如果有对应关系能够满足这组等式，输出所有能够确定的古梅算符和现代算符的对应关系。每一行有两个字符，其中第一个字符是古梅算符，第二个字符是对应的现代算符。输出按照字典顺序排序。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<div>
<p>2</p>
<p>abcdec</p>
<p>cdefe</p>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<div>
<p>a6</p>
<p>b*</p>
<p>d=</p>
<p>f+</p>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>在上例中，可能对应的现代表达式为{6*2=12，2=1+1}，{6*4=24，4=2+2}，{6*8=48，8=4+4}。可见，能够确定的对应关系只有a对应6，b对应*，d对应=，f对应+，应该输出；而{c,e}虽然能够找到对应的现代算符使得等式成立，但没有唯一的对应关系，不能输出。其他古梅算符{g,h…m}完全不能确定，也不能输出。</p>
</div>
</div>