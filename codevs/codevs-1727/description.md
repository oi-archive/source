<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>iny Basm语言(简称为TB语言)的巴科斯-瑙尔范式(BNF)为：</p>
<p>&lt;程序&gt;      ::= &lt;语句&gt; ¿ { &lt;语句&gt; ¿ }</p>
<p>&lt;语句&gt;      ::= &lt;行号&gt; ÿ &lt;语句体&gt;</p>
<p>&lt;语句体&gt;    ::= &lt;累加语句&gt; | &lt;输出语句&gt; | &lt;转移语句&gt; | &lt;条件语句&gt; | &lt;结束语句&gt;</p>
<p>&lt;累加语句&gt;  ::= &lt;变量&gt; + &lt;整数&gt;</p>
<p>&lt;输出语句&gt;  ::= &lt;变量&gt; ?</p>
<p>&lt;转移语句&gt;  ::= GO ÿ &lt;行号&gt;</p>
<p>&lt;条件语句&gt;  ::= IF ÿ &lt;变量&gt; = &lt;整数&gt; ÿ &lt;转移语句&gt;</p>
<p>&lt;结束语句&gt;  ::= END</p>
<p>&lt;变量&gt;      ::= &lt;字母&gt;</p>
<p>&lt;行号&gt;      ::= &lt;整数&gt;</p>
<p>&lt;整数&gt;      ::= &lt;数字&gt; { &lt;数字&gt; }</p>
<p>&lt;字母&gt;      ::= A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z</p>
<p>&lt;数字&gt;      ::= 0|1|2|3|4|5|6|7|8|9</p>
<p>注：其中“::=”表示<strong><span style="text-decoration: underline;">定义为</span></strong>，“|”表示<strong><span style="text-decoration: underline;">或</span></strong>，{}内的项<strong><span style="text-decoration: underline;">可以重复任意多次或不出现</span></strong>，“ÿ”表示<strong><span style="text-decoration: underline;">空格</span></strong>(一个字符，ASCII码为32)，“¿”表示<strong><span style="text-decoration: underline;">回车/换行</span></strong>(两个字符，ASCII码分别为13和10)。</p>
<p> </p>
<p>错误语句示例(在输入文件中不会出现任何错误语句)：</p>
<p>10ÿA+1.5                    <em>（不符合累加语句的定义，所加的不是整数）</em></p>
<p>20ÿAÿ?                      <em>（不符合输出语句的定义，多加了一个空格）</em></p>
<p>30ÿIFÿA=BÿGOÿ10             <em>（不符合条件语句的定义，不应变量=变量）</em></p>
<p> </p>
<p>TB程序的执行：</p>
<p>l  程序从行号最小的一条语句开始执行，在未遇到条件语句时按行号由小至大顺序执行。</p>
<p>l  所有变量在程序执行前被自动初始化为0。</p>
<p>l  累加语句将语句中变量的值加上语句中的整数送回该变量。</p>
<p>l  输出语句将语句中变量的值在监视器上显示出来。</p>
<p>l  执行条件语句时，当且仅当该语句中的变量与紧跟在等号后面的整数值相等，后面的转移语句才被执行。该语句中的所有整数值至多为4位。</p>
<p>l  转移语句被执行后，程序将转去执行GO后面指定的行号的语句。</p>
<p>l  当程序执行结束语句后，结束整个程序的执行。</p>
<p>l  假设该系统能处理任意大小的整数，而不会发生溢出。</p>
<p> </p>
<p>请编程，对于给定的TB语言程序P，求该程序所执行的语句数(执行条件语句不论是否成功转移，仅记为执行一条语句)。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>l  输入文件为一个TB语言程序P，语句数不超过100行。</p>
<p>l  P中每条语句的长度不超过20个字符。</p>
<p>l  P中转移语句里GO后面的行号一定有对应的语句。</p>
<p>l  P中可能有多个不同行号的结束语句。</p>
<p>l  P中行号最大的语句一定是结束语句。</p>
<p>l  P中的行号都不大于3000。</p>
<p>l  输入文件不一定是按行号递增顺序给出P的。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件有且仅有一行：</p>
<p>如果程序能够正常结束，输出该程序所执行的语句数；</p>
<p>如果程序不能正常结束，输出-1。</p>

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
<p>10 A+1</p>
<p>20 IF A=5 GO 60</p>
<p>60 END</p>
<p>30 A+2</p>
<p>40 A?</p>
<p>50 GO 20</p>
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
<p>11</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>执行语句行号按顺序为</p>
<p>10-〉20-〉30-〉40-〉50-〉20-〉30-〉40-〉50-〉20-〉60</p>
<p>共11条语句被执行。</p>
</div>
</div>