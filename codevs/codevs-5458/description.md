<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小明对操作系统 的原理十分好奇。课外时间他写了个程序来模拟操作系统的运行（相关）。</p><p>本题要求：</p><p>（大小写敏感）</p><p>1、实现开关机，开机命令为（下同）systemstate on，关机为systemstate off。</p><p>2、实现对象管理，需要新建是Process</p><p>新建命令：newObjectType [+object名称， 不包含这个括号]</p><p>3、实现打开关闭进程句柄，创建进程，结束进程</p><p>命令：</p><p>1、openProcess [+PID名称]</p><p>2、closeHandle [+PID名称]</p><p>3、terminateProcess [+PID名称]</p><p>4、createProcess [+PID名称]</p><p>//按照PID创建进程</p><p>Notice：只有打开进程才能操作，打开进程即使PID相同也会同时被打开，关闭类似</p><p>4、实现枚举进程和判断是否存在，存在多少个</p><p>命令：</p><p>1、enum all</p><p>     输出格式 [直接输出PID数字，每个PID完后换行]</p><p>2、query [+PID名称]</p><p>      输出格式 [PID] [空格加次数]</p><p>5、程序检验</p><p>1、如果运行时有误那么立马报错，</p><p>cout &lt;&lt;"Invaild Instruction"&lt;&lt;endl;</p><p>然后结束运行</p><p>2、如果没有closeHandle或者没有关机的话也要报错</p><p style="">cout &lt;&lt;"System error."&lt;&lt;endl;</p><p style="">然后结束运行</p><p style="">如果没有错误，那么</p><p style="">cout &lt;&lt;"All Done."&lt;&lt;endl;</p><p>检验输入：</p><p>check result</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>例子：</p><p>systemstate on</p><p>newObjectType Process</p><p>createProcess 6666</p><p>openProcess 6666</p><p>enum all</p><p>createProcess 6666</p><p>query 6666</p><p>terminateProcess 6666</p><p>closeHandle 6666</p><p>systemstate off</p><p>check result</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>6666</p><p>6666 2</p><p>All Done.<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>写上面了...<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>写上面了...</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>写上面了...</p>
</div>
</div>