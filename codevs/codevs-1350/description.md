<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>大神写了一个C++程序 无奈没有编译器。。你能帮他写一个编译器出来吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个正整数n，表示程序行数。<br>以后n排是大神c++程序的代码</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出大神的程序应有的输出值.若编译失败或运行错误，输出&ldquo;Error!&rdquo;(忽略文末空格与回车)</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>9<br>#include&lt;iostream&gt;<br>using namespace std;</p>
<p>int main(){<br>int a=1;<br>int b=1;<br>cout&lt;&lt;a+b&lt;&lt;endl;<br>return 0;<br>}</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的数据，1&lt;=n&lt;=30.<br>行首没有空格<br>程序的第一排一定是 #include&lt;iostream&gt; 第二排一定是using namespace std;<br>第三排一定是空行 main函数一定是int形式 输出一定是数字<br>给出的其他保留字符仅会有 int cout if while return do endl for<br>数据类型只会出现int与int数组 保证字母全为小写。<br>出现的运算符：+,-,*,/,%,+=,-=,*=,/=</p>
</div>
</div>