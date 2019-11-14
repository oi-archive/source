<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><br></p><p><br></p><p><br></p><p><br></p><p><br></p><p><br></p><p><br></p><p><br></p><p><br></p><p><br></p><p><strong><span style="">题目数据暂时有问题</span></strong></p><p><br></p><p>http://pan.baidu.com/s/1skSGRwT</p><p>所以测试数据请自己到这里下载。</p><p><br></p><p><br></p><p><br></p><p><br></p><p><br></p><p><br></p><p><br></p><p><br></p><p>任务管理器是windows系统中的常用进程管理器。</p><p>现有一大堆正在运行的进程，要以一定顺序放进任务管理器，然后尽量截掉这些进程。</p><p>但是你电脑的CPU冒出了一缕青烟（还没有备用的GPU），所以这个任务只能交给你人工去做←_←。</p><p><br></p><p>每个任务有几个属性：PID（p），启动这个进程的用户（u），占用的内存量（m）。</p><p>但是有些进程比较特殊，必须排在某个进程的前面。</p><p>而且——重要的是，要删除进程只能先删除排列在前面的——谁让你电脑CPU冒烟了╮(╯_╰)╭。</p><p><br></p><p>启动进程的用户可以有两种：</p><p>    u=“system”的是系统启动的——<strong>不可以被删除</strong>。</p><p>    u=“admin”的是用户启动的——随便删除。</p><p>（注意：如果有系统启动的进程必须排在用户的进程前面，那么这个系统进程后面的用户进程就不能被删除，占用内存就不能被释放。）</p><p><br></p><p>现在求出一种可行的排列方式，使释放的内存量最多，输出最多释放的内存量。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数n（1&lt;=n&lt;=100）</p><p>第2至n+1行每行三个参数：p，u，m用空格隔开（0&lt;=p,m&lt;=1000，u=“system”或“admin”——均为小写）</p><p>第n+2行是一个整数x（1&lt;=x&lt;=40）</p><p>接下来的x行每行两个整数Ai、Bi，是两个进程的PID号码，表示PID为Ai的进程必须在PID为Bi的进程前面。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>最大释放的内存总量<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p><p>1 admin 100</p><p>29 system 100</p><p>52 admin 1000</p><p>1</p><p>29 52</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>100</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=n&lt;=100<br></p><p>0&lt;=p,m&lt;=1000，u=“system”或“admin”——均为小写</p><p>1&lt;=x&lt;=40</p><p><br></p>
</div>
</div>