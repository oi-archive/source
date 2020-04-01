<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">在如今的网络中，</span>TCP<span style="">是一种被广泛使用的网络协议，它在传输层提供了可靠的通信服务。众所周知，网络是存在时延的，例如用户先后向服务器发送了两个指令</span>op1<span style="">和</span>op2<span style="">，并且希望服务器先处理指令</span>op1<span style="">，再处理指令</span>op2<span style="">；但由于网络时延，这两个指令可能会失序到达，而导致服务器先执行了指令</span>op2<span style="">，这是我们不希望看到的。</span>TCP<span style="">协议拥有将失序到达的报文按顺序重组的功能，一种方法是给每一个报文打上一个时间戳。而你今天要实现的功能比这个要简单很多。我们需要你维护一个服务器，这个服务器的功能是一个简单的栈，你会接收三种用户的指令：</span></p><p>push x t --- <span style="">表示将</span>x<span style="">元素入栈，这条指令的时间戳为</span>t</p><p>pop t --- <span style="">表示将栈顶元素弹出，这条指令的时间戳为</span>t</p><p>peak t --- <span style="">用户询问现在栈顶元素的值，这条指令的时间戳为</span>t</p><p> </p><p><span style="">当一条时间戳为</span>t<span style="">的指令到达时，你需要进行如下处理：</span></p><p>1.<span style="">将所有之前执行的时间戳大于</span>t<span style="">的</span>push<span style="">和</span>pop<span style="">指令全部撤销</span></p><p>2.<span style="">执行当前这条指令</span></p><p>3.<span style="">按时间戳顺序重新执行在第</span>1<span style="">步被撤销的指令</span></p><p> </p><p><span style="">注意你不需要撤销以及重新执行之前已经执行过的</span>peak<span style="">指令，也就是说每一条</span>peak<span style="">指令只有在它到达的时候会被执行一次。</span></p><p> </p><p><span style="">我们保证每一条指令的时间戳都是唯一的；若你在需要执行一条</span>pop<span style="">指令时发现当前栈为空，则当前你可以忽略这条指令。</span></p><p> </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行包含一个整数</span>n<span style="">，表示指令总数。</span></p><p><span style="">接下来</span>n<span style="">行按指令到达服务器的顺序给出每一条指令，有三种类型</span></p><p>push x t</p><p>pop t</p><p>peak t</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family:宋体">对于每一条</span>peak<span style="font-family:宋体">指令，输出对应的答案占一行；若栈为空，输出</span>-1<span style="font-family:宋体">。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7</p><p>push 100 3</p><p>push 200 7</p><p>peak 4</p><p>push 50 2</p><p>pop 5</p><p>peak 6</p><p>peak 8</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>100</p><p>50</p><p>200</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">对于</span>10%<span style="">的数据，</span>1 &lt;= n &lt;= 1000<span style="">；</span></p><p><span style="">对于</span>40%<span style="">的数据，</span>1 &lt;= n &lt;= 80000<span style="">；</span></p><p><span style="">对于</span>100%<span style="">的数据，</span>1 &lt;= n &lt;= 300000<span style="">，</span>0 &lt;= x<span style="">，</span>t &lt;= 1000000000<span style="">。</span></p><p><br></p>
</div>
</div>