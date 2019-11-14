<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>虽然fdy写代码从不压行，但他希望你编写程序给一份C++代码压行。具体而言，需要把所有能去掉的空白字符去掉，并把剩余的所有空白字符中能用空格代替的均用空格代替（具体参照样例）。其中，空白字符为空格' '、制表符'\t'、回车符'\r'及换行符'\n'。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一份包含若干行的C++代码。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>压行后的代码。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>#include &lt;cstdio&gt;
# define NIL (-1)
#define F(x) (-1)
int main( ){
puts("No solution");
}</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>#include&lt;cstdio&gt;
#define NIL (-1)
#define F(x)(-1)
int main(){puts("No solution");}</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>输入的源代码保证：通过编译；总长度不超过20k；不包含任何注释；不包含以续行符形式出现的'\'；所有字符的ASCII码均小于128；字符串字面值及字符字面值之中不会出现引号，之外的所有标点符号之间的空白均可以去掉（不会出现a- -b等情况）。标点符号指标识符不能包含的可打印字符。 </p><p>数据中的换行以linux为准，即用一个'\n'表示换行。数据不含'\r'。</p><p><br></p>
</div>
</div>