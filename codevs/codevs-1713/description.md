<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>内存是计算机重要的资源之一，程序运行的过程中必须对内存进行分配。 <br>经典的内存分配过程是这样进行的： <br>1、 内存以内存单元为基本单位，每个内存单元用一个固定的整数作为标 识，称为地址。地址从 0 开始连续排列，地址相邻的内存单元被认为是 逻辑上连续的。我们把从地址i开始的s个连续的内存单元称为首地址为i 长度为s的地址片。</p>
<p>2、 运行过程中有若干进程需要占用内存，对于每个进程有一个申请时刻 T，需要内存单元数M及运行时间P。在运行时间P内（即T时刻开始， T+P时刻结束），这M个被占用的内存单元不能再被其他进程使用。</p>
<p><br>3、假设在 T 时刻有一个进程申请 M 个单元，且运行时间为 P，则：</p>
<p><br>1. 若 T 时刻内存中存在长度为 M 的空闲地址片，则系统将这 M 个空闲单元分配给该进程。若存在多个长度为 M 个空闲地址片，则系统将首地址最小的那个空闲地址片分配给该进程。</p>
<p>2. 如果T时刻不存在长度为M的空闲地址片，则该进程被放入一个等待队列 。对于处于等待队列队头的进程，只要在任一时刻，存在长度为M的空 闲地址片，系统马上将该进程取出队列，并为它分配内存单元。注意，在进行内存分配处理过程中，处于等待队列队头的进程的处理优先级最 高，队列中的其它进程不能先于队头进程被处理。 </p>
<p>现在给出一系列描述进程的数据，请编写一程序模拟系统分配内存的过程</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是一个数 N，表示总内存单元数（即地址范围从 0 到 N-1） </p>
<p>第二行开始每行描述一个进程的三个整数 T、M、P（M&lt;=N）。 数据已按 T 从小到大排序。 </p>
<p>最后一行用三个 0 表示结束。 输入文件最多 10000 行，且所有数据都小于 109。</p>
<p>输入文件中同一行的相邻两项间用一个或多个空格隔开</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包括 2 行。</p>
<p>第一行是全部进程都运行完毕的时刻。</p>
<p>第二行是被放入过等待队列的进程总数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10</p>
<p>1 3 10</p>
<p>2 4 3</p>
<p>3 4 4</p>
<p>4 1 4</p>
<p>5 3 4</p>
<p>0 0 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>12</p>
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
<p>1 A <br>进程 A 申请空间（M=3,P=10）&lt;成功&gt; <br>2 A B 进程 B 申请空间（M=4,P=3）&lt;成功&gt; <br>3 A B <br>进程 C 申请空间（M=4,P=4）&lt;失败进入等待队列&gt; <br>4 A B D 进程 D 申请空间 （M=1,P=4）&lt;成功&gt;  </p>
<p>5 A C D <br>进程 B 结束，释放空间 <br>进程 C 从等待队列取出，分配空间<br>进程 E 申请空间（M=3,P=4）&lt;失败进入等待队列&gt; <br>6 A C D <br>7 A C D <br>8 A C E <br>进程 D 结束，释放空间 <br>进程 E 从等待队列取出，分配空间 <br>9 A E 进程 C 结束，释放空间</p>
<p>10 A E </p>
<p>11 E 进程 A 结束，释放空间 <br>12 进程 E 结束，释放空间</p>
</div>
</div>