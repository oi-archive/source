# 题目描述


<p>
【问题描述】
</p>
<p>
现在有一项时间紧迫的工程计算任务要交给你——国家高性能并行计算机的主管工程师——来完成。为了尽可能充分发挥并行计算机的优势，我们的计算任务应当划分成若干个小的子任务。
</p>
<p>
这项大型计算任务包括A和B两个互不相关的较小的计算任务。为了充分发挥并行计算机的运算能力，这些任务需要进行分解。研究发现，A和B都可以各自划分成很多较小的子任务，所有的A类子任务的工作量都是一样的，所有的B类子任务也是如此（A和B类的子任务的工作量不一定相同）。A和B两个计算任务之间，以及各子任务之间都没有执行顺序上的要求。
</p>
<p>
这台超级计算机拥有p个计算节点，每个节点都包括一个串行处理器、本地主存和高速cache。然而由于常年使用和不连贯的升级，各个计算节点的计算能力并不对称。一个节点的计算能力包括如下几个方面：<br/>
1. 就本任务来说，每个节点都有三种工作状态：待机、A类和B类。其中，A类状态下执行A类任务；B类状态下执行B类任务；待机状态下不执行计算。所有的处理器在开始工作之前都处于待机状态，而从其它的状态转入A或B的工作状态（包括A和B之间相互转换），都要花费一定的启动时间。对于不同的处理节点，这个时间不一定相同。用两个正整数<math><semantics><mrow><msubsup><mi>t</mi><mi>i</mi><mi>A</mi></msubsup></mrow></semantics></math>和<math><semantics><mrow><msubsup><mi>t</mi><mi>i</mi><mi>B</mi></msubsup><mtext>  </mtext><mo></mo><mo></mo></mrow></semantics></math> (i=1,2,...,p)分别表示节点i转入工作状态A和工作状态B的启动时间（单位：ns）。
</p>
<p>
2. 一个节点在连续处理同一类任务的时候，执行时间——不含状态转换的时间——随任务量（这一类子任务的数目）的平方增长，即：<br/>
若节点i连续处理x个A类子任务，则对应的执行时间为：<math><semantics><mrow><mi>t</mi><mo>=</mo><msubsup><mi>k</mi><mi>i</mi><mi>A</mi></msubsup><msup><mi>x</mi><mn>2</mn></msup></mrow></semantics></math><br/>
类似的，若节点i连续处理x个B类子任务，对应的执行时间为：<math><semantics><mrow><mi>t</mi><mo>=</mo><msubsup><mi>k</mi><mi>i</mi><mi>B</mi></msubsup><msup><mi>x</mi><mn>2</mn></msup></mrow></semantics></math><br/>
其中，<math><semantics><mrow><msubsup><mi>k</mi><mi>i</mi><mi>A</mi></msubsup></mrow></semantics></math>和<math><semantics><mrow><msubsup><mi>k</mi><mi>i</mi><mi>B</mi></msubsup></mrow></semantics></math>是系数，单位是ns，i=1,2,...,p。
</p>
<p>
任务分配必须在所有计算开始之前完成，所谓任务分配，即给每个计算节点设置一个任务队列，队列由一串A类和B类子任务组成。两类子任务可以交错排列。
</p>
<p>
计算开始后，各计算节点分别从各自的子任务队列中顺序读取计算任务并执行，队列中连续的同类子任务将由该计算节点一次性读出，队列中一串连续的同类子任务不能被分成两部分执行。
</p>
<p>
【编程任务】
</p>
<p>
现在需要你编写程序，给这 p 个节点安排计算任务，使得这个工程计算任务能够尽早完成。假定任务安排好后不再变动，而且所有的节点都同时开始运行，任务安排的目标是使最后结束计算的节点的完成时间尽可能早。
</p>
<p>
【输入输出】
</p>
<p>
输入文件名是 hpc.in 。
</p>
<p>
文件的第一行是对计算任务的描述，包括两个正整数 n<sub>A</sub> 和 n<sub>B</sub>，分别是 A 类和 B 类子任务的数目，两个整数之间由一个空格隔开。
</p>
<p>
文件的后面部分是对此计算机的描述：
</p>
<p>
文件第二行是一个整数 p ，即计算节点的数目。
</p>
<p>
随后连续的 p 行按顺序分别描述各个节点的信息，第 i 个节点由第 i+2 行描述，该行包括下述四个正整数（相邻两个整数之间有一个空格）：
</p>
<p>
<math><semantics><mrow><msubsup><mi>t</mi><mi>i</mi><mi>A</mi></msubsup></mrow></semantics></math>
<math><semantics><mrow><msubsup><mi>t</mi><mi>i</mi><mi>B</mi></msubsup></mrow></semantics></math>
<math><semantics><mrow><msubsup><mi>k</mi><mi>i</mi><mi>A</mi></msubsup></mrow></semantics></math>
<math><semantics><mrow><msubsup><mi>k</mi><mi>i</mi><mi>B</mi></msubsup></mrow></semantics></math>
</p>
<p>
输出文件名是 hpc.out 。其中只有一行，包含有一个正整数，即从各节点开始计算到任务完成所用的时间。
</p>
<p>
【样例】
</p>
<p>
设输入文件hpc.in为<br/>
5 5<br/>
3<br/>
15 10 6 4<br/>
70 100 7 2<br/>
30 70 1 6<br/>
 
</p>
<p>
对应的输出文件 hpc.out 为
</p>
<p>
93
</p>
<p>
【数据说明】
</p>
<p>
1 ≤ n<sub>A</sub> ≤ 60
</p>
<p>
1 ≤ n<sub>B</sub> ≤ 60
</p>
<p>
1 ≤ p ≤ 20
</p>
<p>
1 ≤ t<sub>A</sub> ≤ 1000
</p>
<p>
1 ≤ t<sub>B</sub> ≤ 1000
</p>
<p>
1 ≤ k<sub>A</sub> ≤ 50
</p>
<p>
1 ≤ k<sub>B</sub> ≤ 50
</p>
<h3>
 
</h3>
