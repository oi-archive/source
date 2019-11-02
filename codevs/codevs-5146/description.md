<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定一段Pascal代码，要求对其进行编译（当然是简易的）</p><p>给定程序中会出现如下错误中的一种或多种：</p><p>    1：缺少begin</p><p>    2：缺少end.</p><p>       <strong>只有end没有“.”也算2号错误。</strong></p><p>    3：有var但无变量声明</p><p>       例：var</p><p>          begin</p><p>          end.</p><p>    4：缺少分号<strong>（多分号也算4号错误）</strong></p><p>    5：非法的变量名：变量开头不可以是符号或数字，只可以是字母，不可以是保留字。</p><p>    6：变量未定义</p><p>    7：缺少左括号</p><p>    8：缺少右括号</p><p>    9：找不到的过程</p><p>    10：无效的数据类型名</p><p><br></p><p>注：保证数据只有一对begin和end.</p><p>    保证只有主程序。（无子程序）</p><p>    除了提到的错误，数据中不会再出现别的错误。</p><p>    end前的分号可以省略，也可以加很多。</p><p>    程序中的多余空格和换行不计入错误，保证不会出现缺少空格的情况。</p><p>    大小写不区分。</p><p>    关键字不可用于变量名。</p><p>    降低难度，不会出现循环语句和条件判断。</p><p>    不会出现数组、const、program、type、uses等。</p><p>    函数和过程不做区分，数据不会在这方面出错。</p><p>    可能的<span style="">数据类型</span><span style="">：longint，string，char。（不会出现类型匹配错误）</span></p><p>附：保留字（可能调用的过程）：read、readln、write、writeln、pos、str、val、copy、delete、inc、dec、var、begin、end.。</p><p>附：可能出现的语句（未提到的不会出现）</p><p>    1、赋值</p><p>    2、输入输出：read、readln、write或writeln</p><p>    3、变量定义</p><p>    4、系统自带过程（参数的填写不会出问题，注意变量即可）</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一段pascal程序，见题干。</p><p>（2&lt;=行数&lt;=100，每行字符数不超过string范围）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>按出现错误的次序输出错误号和首次出现的行数，一行一个。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>var</p><p> a,b:lngint</p><p> c:string;</p><p> pos:char;</p><p>begin</p><p> c:='123';</p><p> pos:=copy(c,1,2,,,,,,,);</p><p> writeln(pos);;;;;;;;;;;;</p><p>end</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10 2</p><p>4 2</p><p>5 4</p><p>4 8</p><p>2 9</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>（2&lt;=行数&lt;=100，每行字符数不超过string范围）</p><p>程序输入用while not eof do</p><p>有什么问题欢迎纠正。</p>
</div>
</div>