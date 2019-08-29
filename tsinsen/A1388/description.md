<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　相信大家都知道C语言预处理指令的define，define用来定义宏。宏其实是在编译之前将指定token替换为对应的表达式。这个问题中不考虑带参数的宏。<br/>
　　例如宏sum的定义为x+y，那么程序中的sum会被替换为x+y，但注意asumb不会被替换为ax+yb，因为这里完整的token是asumb，而不是sum。<br/>
　　宏的定义中可以包含+、-、*、/四种运算符（四则运算，-不能表示负号）、非负整数常量、变量、圆括号和之前定义过的宏。<br/>
　　程序员通常利用宏来减少代码量，但使用不当会无法达到预期效果。例如宏sum被定义为x+y，那么表达式2*sum替换后会变为2*x+y，这时候就需要将sum定义为(x+y)，才能使得替换后变为2*(x+y)，以达到预期效果。<br/>
　　现在按照顺序给出N个宏的定义，最后给出一个表达式，问能否达到预期的效果。预期的效果是每个宏都会被当做整体被运算。</div>
# 输入格式

<div class="pdcont">　　第一行一个正整数T (T ≤ 10)，表示有T组输入需要解决。<br/>
　　每组输入第一行为一个非负整数N (N ≤ 100)，下面N行每行包含一个如下形式的宏定义：<br/>
　　#define name expression<br/>
　　其中宏名称name和expression中的变量名由大小写英文字母组成，输入中可能会有多余的空格，但能保证单词define、name和expression中的token之间没有空格。<br/>
　　最后一行给出一个表达式，表示需要判断的表达式。<br/>
　　输入保证每一行长度不超过100。</div>
# 输出格式

<div class="pdcont">　　输出共T行，依次表示每组输入的答案。如果能够达到预期效果就输出OK，否则输出Suspicious。</div>
# 样例输入

<div class="pddata">4<br/>
1<br/>
#define sum x + y<br/>
1 * sum<br/>
1<br/>
#define sum  (x + y)<br/>
sum - sum<br/>
4<br/>
#define sum  x + y<br/>
#define mul  a * b<br/>
#define div  a / b<br/>
#define expr sum + mul * div * mul<br/>
expr<br/>
3<br/>
#define SumSafe   (a+b)<br/>
#define DivUnsafe  a/b<br/>
#define DenominatorUnsafe  a*b<br/>
((SumSafe) + DivUnsafe/DivUnsafe + x/DenominatorUnsafe)</div>
# 样例输出

<div class="pddata">Suspicious<br/>
OK<br/>
OK<br/>
Suspicious</div>

</div>