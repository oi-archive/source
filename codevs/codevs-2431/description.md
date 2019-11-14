<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一个简单的脚本语言，只有赋值语句、条件语句和返回语句三种。变量名必须是单个大写字母，且变量都是32位带符号整数。 <br>该语言的每条语句必须单独占一行。程序中不含空行，且每行的行首行末均无空格。每行的不同token之间用单个空格隔开。该语言的BNF如下： <br> <br>&lt;line&gt; :: &lt;head&gt; | &lt;assignment&gt; | &lt;if&gt; | ELSE | END IF | &lt;return&gt; <br>&lt;head&gt; :: PARAM &lt;paramlist&gt; | PARAM <br>&lt;assignment&gt; :: &lt;variable&gt; = &lt;rvalue&gt; <br>&lt;if&gt; :: IF &lt;variable&gt; &lt;relation&gt; &lt;value&gt; THEN <br>&lt;return&gt; :: RETURN &lt;value&gt; <br>&lt;paramlist&gt; :: &lt;variable&gt; | &lt;variable&gt; &lt;paramlist&gt; <br>&lt;rvalue&gt; :: &lt;value&gt; | &lt;value&gt; &lt;operator&gt; &lt;value&gt; <br>&lt;value&gt; :: &lt;variable&gt; | &lt;integer&gt; <br>&lt;operator&gt; :: + | - | * | / <br>&lt;relation&gt; :: &lt; | = | &gt; <br>&lt;variable&gt; :: A | B | ... | Z <br>&lt;integer&gt; :: 不含前导0的32位带符号整数 <br> <br>程序的第一行是一条&lt;head&gt;语句，定义了函数的参数，而最后一行一定是<br>&lt;return&gt;语句。&lt;head&gt;语句不能在除了第一行之外的其他任何地方出现，但<br>&lt;return&gt;语句可以在程序中多次出现。行号从1开始编号。 <br>每条IF语句一定有一个配套的END IF语句， 还有一个可选的ELSE语句（注<br>意没有ELSE IF语句） 。IF语句可以嵌套，它总是比较一个变量和一个整数或者<br>另一个变量。 <br> <br>你应该分析一个给定的程序，并输出两类警告信息（格式见样例输出）： <br>l 第一类警告：无法到达的代码行。不管各条 IF 语句的布尔表达式是真还是<br>假（假设每条 IF 语句的布尔表达式都是既可能为真也可能为假，不受其他<br>IF 语句结果影响） 。 <br>l 第二类警告：可能未初始化的变量。该语句用到了某个变量的值，但这个变<br>量既不在第一行指定的参数列表里，也没有在此之前由赋值语句赋值过。如<br>果这条语句无法到达，那么不应该给出这类警告。 <br> <br>注意，语句ELSE和END IF不是可执行语句，因此不应该收到任何警告信息。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>  最多包含50行，即你要处理的程序。保证该程序合法。 </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>警告按照行号从小到大排序。如果同一行内有多个可能未初始化的变量，按照字母顺序从小到大排列。如果没有任何警告信息，你的输出应该为空。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>PARAM T C <br>B = T <br>A = 4 <br>IF A &lt; 4 THEN <br>IF B &gt; 3 THEN <br>Q = 100 + F <br>ELSE <br>IF C = -1111111111 THE<br>Q = T - A <br>IF Q = 0 THEN <br>V = V - 1 <br>END IF <br>ELSE <br>RETURN I <br>E = A <br>END IF <br>END IF <br>ELSE <br>Q = 1 <br>END IF <br>RETURN Q</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Line 6: variable F might not have been <br>initialized <br>Line 11: variable V might not have <br>been initialized <br>Line 14: variable I might not have <br>been initialized <br>Line 15: unreachable code</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>行数&lt;=50</p>
</div>
</div>