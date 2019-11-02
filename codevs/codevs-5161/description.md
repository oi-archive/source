<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style=""><strong><br></strong></span></p><p><span style=""><strong><br></strong></span></p><p><span style=""><strong><br></strong></span></p><p><span style=""><strong><br></strong></span></p><p><span style=""><strong><br></strong></span></p><p><span style=""><strong>测试数据有问题！！！！！！无法上传。</strong></span></p><p><span style="text-decoration: underline;"><em><span style="">http://pan.baidu.com/s/1milNRyK</span></em></span><span style=""> </span></p><p><span style="text-decoration: underline;">所以测试数据请到这里下载。</span></p><p><span style=""><strong><br></strong></span></p><p><span style=""><strong><br></strong></span></p><p><span style=""><strong><br></strong></span></p><p><span style=""><strong><br></strong></span></p><p><span style=""><strong><span style=""></span></strong></span></p><p><span style=""><strong>请使用宋体对齐查看样例</strong></span></p><p><br></p><p><span style="">HTML是一种静态网页语言，文件后缀名是.htm或.html，</span></p><p><span style="">普遍应用于网站建设，常与PHP等动态语言结合使用。</span></p><p><br></p><p><span style="">现给出一段HTML的程序，请参照下文进行运行，显示出一个“网页界面”。</span></p><p><span style="">    说明：</span></p><p><span style=""><span style=""></span>1、段落（回车也要输出）</span></p><p><br></p><p><span style="">代码：</span></p><p><span style="">  1 |&lt;p&gt;内容</span></p><p><span style="">  2 |文字&lt;/p&gt;</span></p><p><span style="">           </span></p><p><span style="">应该输出：</span></p><p><span style="">  1 |    内容</span></p><p><span style="">  2 |文字</span></p><p><span style="">（每个段落段落前有四个空格）</span></p><p><br></p><p><span style=""><span style=""></span>2、图片（每个图片另，而不是一个紧接着一个）</span></p><p><br></p><p><span style="">代码：</span></p><p><span style="">  1 |&lt;img src="图片名称" /&gt;</span></p><p><br></p><p><span style="">应该输出：</span></p><p><span style="">  1 |*--------*</span></p><p><span style="">  2 ||图片名称|</span></p><p><span style="">  3 |*--------*</span></p><p><br></p><p><span style=""><span style=""></span>3、分隔符</span></p><p><br></p><p><span style="">代码：</span></p><p><span style="">  1 |&lt;br /&gt;</span></p><p><br></p><p><span style="">应该输出：（50个“-”）</span></p><p><span style="">  1 |--------------------------------------------------</span></p><p><br></p><p><span style=""><span style=""></span>4、表格（内部换行也要输出）</span></p><p><br></p><p><span style="">代码：</span></p><p><span style="">  1 |&lt;table&gt;</span></p><p><span style="">  2 |  &lt;tr&gt;</span></p><p><span style="">  3 |    &lt;td&gt;月份</span></p><p><span style="">  4 |Test1</span></p><p><span style="">  5 |</span></p><p><span style="">  6 |Test2&lt;/td&gt;</span></p><p><span style="">  7 |    &lt;td&gt;存款&lt;/td&gt;</span></p><p><span style="">  8 |  &lt;/tr&gt;</span></p><p><span style="">  9 |  &lt;tr&gt;</span></p><p><span style=""> 10 |    &lt;td&gt;一&lt;/td&gt;</span></p><p><span style=""> 11 |    &lt;td&gt;$10000&lt;/td&gt;</span></p><p><span style=""> 12 |  &lt;/tr&gt;</span></p><p><span style=""> 13 |&lt;/table&gt;</span></p><p><br></p><p><span style="">应该输出：</span></p><p><span style="">  1 |*-----*------*</span></p><p><span style="">  2 ||月份 |存款  |</span></p><p><span style="">  3 ||Test1|      |</span></p><p><span style="">  4 ||     |      |</span></p><p><span style="">  5 ||Test2|      |</span></p><p><span style="">  6 |*-----*------*</span></p><p><span style="">  7 ||一   |$10000|</span></p><p><span style="">  8 |*-----*------*</span></p><p><br></p><p><span style=""><span style=""></span>5、嵌套语句</span></p><p><br></p><p><span style=""><span style=""></span>很多语句都可以进行嵌套，具体如下</span></p><p><span style=""><span style=""></span>1、图片嵌套在&lt;p&gt;&lt;/p&gt;中。</span></p><p><span style=""><span style=""></span>代码：</span></p><p><span style=""><span style=""></span>  1 |&lt;p&gt;&lt;img src="GRAPH" /&gt;HEHEHE</span></p><p><span style=""><span style=""></span>  2 |HAHA&lt;/p&gt;</span></p><p><span style=""><span style=""></span>应该输出：</span></p><p><span style=""><span style=""></span>  1 |    *-----*</span></p><p><span style=""><span style=""></span>  2 |    |GRAPH|</span></p><p><span style=""><span style=""></span>  3 |    *-----*HEHEHE</span></p><p><span style=""><span style=""></span>  4 |HAHA</span></p><p><span style=""><span style=""></span>2、表格嵌套在段落中：</span></p><p><span style=""><span style=""></span>与 图片嵌套在段落中 的演示同理</span></p><p><span style=""><span style=""></span>3、段落嵌套在段落中：</span></p><p><span style=""><span style=""></span>代码：</span></p><p><span style=""><span style=""></span>  1 |&lt;p&gt;A&lt;p&gt;B&lt;p&gt;C</span></p><p><span style=""><span style=""></span>  2 |&lt;p&gt;D&lt;/p&gt;&lt;/p&gt;&lt;/p&gt;&lt;/p&gt;</span></p><p><span style=""><span style=""></span>应该输出：</span></p><p><span style=""><span style=""></span>  1 |    A    B    C</span></p><p><span style=""><span style=""></span>  2 |    D</span></p><p><span style=""><span style=""></span>4、图片嵌套在表格中：</span></p><p><span style=""><span style=""></span>代码：</span></p><p><span style=""><span style=""></span>  1 |&lt;table&gt;</span></p><p><span style=""><span style=""></span>  2 |  &lt;tr&gt;</span></p><p><span style=""><span style=""></span>  3 |    &lt;td&gt;&lt;img src="GRAPH1" /&gt;&lt;/td&gt;</span></p><p><span style=""><span style=""></span>  4 |    &lt;td&gt;None.&lt;/td&gt;</span></p><p><span style=""><span style=""></span>  5 |  &lt;/tr&gt;</span></p><p><span style=""><span style=""></span>  6 |&lt;/table&gt;</span></p><p><span style=""><span style=""></span>应该输出：</span></p><p><span style=""><span style=""></span>  1 |*--------*-----*</span></p><p><span style=""><span style=""></span>  2 ||*------*|None.|</span></p><p><span style=""><span style=""></span>  3 |||GRAPH1||     |</span></p><p><span style=""><span style=""></span>  4 ||*------*|     |</span></p><p><span style=""><span style=""></span>  5 |*--------*-----*</span></p><p><span style=""><span style=""></span>5、分隔符嵌套在表格中：</span></p><p><span style=""><span style=""></span>表格里也可以放分隔符</span></p><p><span style=""><span style=""></span>代码：</span></p><p><span style=""><span style=""></span>  1 |&lt;table&gt;</span></p><p><span style=""><span style=""></span>  2 |  &lt;tr&gt;</span></p><p><span style=""><span style=""></span>  3 |    &lt;td&gt;</span></p><p><span style=""><span style=""></span>  4 |123</span></p><p><span style=""><span style=""></span>  5 |&lt;br /&gt;</span></p><p><span style=""><span style=""></span>  6 |456</span></p><p><span style=""><span style=""></span>  7 |    &lt;/td&gt;</span></p><p><span style=""><span style=""></span>  8 |    &lt;td&gt;HEHE&lt;/td&gt;</span></p><p><span style=""><span style=""></span>  9 |  &lt;/tr&gt;</span></p><p><span style=""><span style=""></span> 10 |&lt;/table&gt;</span></p><p><span style=""><span style=""></span>应该输出：</span></p><p><span style=""><span style=""></span>  1 |*--------------------------------------------------*----*</span></p><p><span style=""><span style=""></span>  2 ||123                                               |HEHE|</span></p><p><span style=""><span style=""></span>  3 ||--------------------------------------------------|    |</span></p><p><span style=""><span style=""></span>  4 ||456                                               |    |</span></p><p><span style=""><span style=""></span>  5 |*--------------------------------------------------*----*</span></p><p><br></p><p><span style="">注：本题不完全按照HTML的完整语法来写，不要被误导。（但是放进去也是可以编译正确的~）</span></p><p><span style="">    本题数据代码保证无编译错误。</span></p><p><span style="">    每一行前面可能会有空格。</span></p><p><span style="">    除了嵌套，每行只会有一个起始或结束标签。</span></p><p><span style="">    保证数据严格按照格式。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一段代码</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>应当显示的东西</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>&lt;p&gt;EXAMPLE&lt;/p&gt;</p><p>&lt;img src="EXAMPLEGRAPH1" /&gt;</p><p>&lt;p&gt;&lt;img src="EXAMPLEGRAPH2" /&gt;&lt;/p&gt;</p><p>&lt;br /&gt;</p><p>&lt;table&gt;</p><p>  &lt;tr&gt;</p><p>    &lt;td&gt;月份&lt;/td&gt;</p><p>    &lt;td&gt;存款&lt;/td&gt;</p><p>  &lt;/tr&gt;</p><p>  &lt;tr&gt;</p><p>    &lt;td&gt;一&lt;/td&gt;</p><p>    &lt;td&gt;$10000&lt;/td&gt;</p><p>  &lt;/tr&gt;</p><p>&lt;/table&gt;</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>    EXAMPLE</p><p>*-------------*</p><p>|EXAMPLEGRAPH1|</p><p>*-------------*</p><p>    *-------------*</p><p>    |EXAMPLEGRAPH2|</p><p>    *-------------*</p><p>--------------------------------------------------</p><p>*----*------*</p><p>|月份|存款  |</p><p>*----*------*</p><p>|一  |$10000|</p><p>*----*------*</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>给大家介绍个学HTML等语言的好网站：<br></p><p>w3school</p><p><br></p>
</div>
</div>