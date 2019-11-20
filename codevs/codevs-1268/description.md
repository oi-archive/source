<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>In Waterloo, you probably have seen some geese. How can you see geese with your calculator? Start with 6, add 7, multiply by 6, multiply by 8, add 7, multiply by 8, and multiply by 7, giving 35336. Then if you ﬂip your calculator upside down, it says gEESE:</p>
<p>在水城，你可能会看到一些鹅。你怎么在计算器上看到鹅呢？方法是输入35536，然后把计算器倒过来看，你就能看到gEESE——鹅了。</p>
<p>You want to write a program to help automatically build tricks of this type. However, your calcula- tor has a lot of broken buttons: the only mathematical operators that work are + and ×, and only a few of the digits work. Your goal is to ﬁgure out whether your half-broken calculator can achieve a given target value, using single-digit inputs and a ﬁxed number of operations.</p>
<p>现在你的计算器的减号不给力了，只有+号和×号可以用，而且也只有部分数字可以工作。现在的任务是对于这个破烂的计算器能否通过简单的数字和固定数目的运算次数得到一个给定的目标值。</p>
<p>Note: the calculator performs the operations as soon as they are entered, rather than following any rules for order of operations (see Sample Input 2).</p>
<p>注意这个计算器的运算在被按下的时候就立即执行了，而不需要按照运算符优先级的规则。（见样例2）</p>

<img src="/source/codevs/codevs-1268/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xMjY4L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2MDQ4OTkyNi4zNTAuNjQ3MTQ2OTU0MTkxLnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>The ﬁrst line of input is W, the exact number of operations you must use. W will be an integer between 0 and 6. The second line of input is 1 ≤ D ≤ 10, the number of working digit keys. On each of the D following lines, a working digit is given; these values are distinct integers from 0 to 9. Finally, an integer 1 ≤ V ≤ 5 is given, the number of target values; on each of the following V lines there is an integer between 0 and 5000000 (inclusive) giving a target value which you’d like to achieve on your calculator.</p>
<p>第一行输入一个整数W，表示你能够且必须使用的运算个数。W是是一个介于0到6之间的整数。结下来的一行是一个整数D(1 ≤ D ≤ 10)，可以工作的数字键的个数。接下来的D行给出了这D个可以工作的数字键，这些数字键是0-9之间的互不重复的整数。然后给出一个整数V(1 ≤ V ≤ 5)，即目标值的个数，接下来的V行每行一个介于0到5,000,000(包含)的整数，代表你需要用过计算器算出来的数值。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>The output consists of V lines corresponding to the target values; each line contains &ldquo;Y&rdquo; if that target value can be achieved, and &ldquo;N&rdquo; if it cannot be achieved, using exactly W operations with the D given digits.<br />Precisely, a target value T can be achieved if, starting with one of the D digits, and then by adding or multiplying exactly W times by one of the digits, you end up with T. Digits can be re-used, and you do not need to use all of the digits. You cannot enter multi-digit numbers.</p>
<p>输出包含V行，对应着V个目标值。每行是Y或者N，代表对应的目标值能在使用这D个数字并且刚好在W次运算的情况下被计算得到或者不能被计算得到。精确的说，一个目标值T能够计算得到的话，那是通过从D个数字钟的某个数字开始，通过加或乘其这些数字刚好W次，然后最后得到数值T。数字是可以重复使用的。数字也不需要全部被用完。但注意你不可以输入多位数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例输入1</p>
<p>6</p>
<p>3</p>
<p>6</p>
<p>7</p>
<p>8</p>
<p>1</p>
<p>35336</p>
<p> </p>
<p>样例输入2</p>
<p>3</p>
<p>2</p>
<p>4</p>
<p>9</p>
<p>2</p>
<p>97</p>
<p>88</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例输出1：</p>
<p>Y</p>
<p>样例输出2：</p>
<p>N</p>
<p>Y</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>First line: we cannot achieve 97 using the rules of this calculator, so the output is N (even despite that 4×4+9×9 = 97, when the typical order of operations rules are taken into account). Second line: start with 9, add 9, add 4, and multiply by 4; this gives 88.</p>
<p>对于第二个数据，虽然4×4+9×9 = 97，但是由于计算的顺序是从左往右依次进行的，所以输出N。第二行，9+9+4*4就得到了88.</p>
</div>
</div>