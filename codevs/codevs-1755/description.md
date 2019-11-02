<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>这是一个很古老的游戏。用木棒在桌上拼出一个不成立的等式，移动且只移动一根木棒<br>使得等式成立。现在轮到你了。<br>从文件读入一个式子。<br>如果移动一根木棒可以使等式成立，则输出新的等式，否则输出No。</p>

<img src="/source/codevs/codevs-1755/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNzU1L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTc1NS5ibXA=.bmp" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>从文件 game.in 中读入一行字符串。该串中包括一个以“#”字符结尾的式子（ASCII<br>码35)，式子中没有空格或其他分隔符。输入数据严格符合逻辑。字符串的长度小于等于<br>1000。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出结果到文件game.out，输出仅一行。<br />如果有解，则输出正确的等式，格式与输入的格式相同（以&ldquo;#&rdquo;结尾，中间不能有分<br />隔符，也不要加入多余字符）。<br />如果无解，则输出&ldquo;No&rdquo;（N 大写，o 小写）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【输入样例 1】<br>1+1=3#<br>【输入样例2】<br>1+1=3+5#<br>【输入样例3】<br>11+77=34#</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【输出样例1】<br>1+1=2#<br>【输出样例2】<br>No<br>【输出样例3】<br>17+17=34#</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1． 式子中只会出现加号和减号（包括负号），并且有且仅有一个等号，不会出现括号、乘<br>号或除号，也不会有++,--,+-或-+出现。<br>2． 式子中不会出现8 个或8 个以上的连续数字。<br>3． 你只能移动用来构成数字的木棒，不能移动构成运算符（+ -=）的木棒，所以加号、减<br>号、等号是不会改变的。移动前后，木棒构成的数字必须严格与图2 中的0~9 相符。<br>4． 修改前的等式中的数不会以0 开头，但允许修改后的等式中的数以数字０开头。</p>
<p>注意：“#”字符后面可能会有一些与题目无关的字符。</p>
</div>
</div>